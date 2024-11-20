Fork of Chess.NET with added board display in ASCII / Unicode mode. 

Used for a mod for a game that uses an older version of Unity, so Chess projects that utilize newer .NET functionality were not compatible.

---

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

I don't intend to continue maintaining this project. See https://github.com/thomas-daniels/Chess.NET/issues/29#issuecomment-599210147 for the details.

Chess.NET [![](https://travis-ci.org/ProgramFOX/Chess.NET.svg?branch=master)](https://travis-ci.org/ProgramFOX/Chess.NET)
=
Chess.NET is a chess library for .NET, written in C#.

It contains the following features:

 - Move validation (including castling and en passant).
 - Check validation.
 - Checkmate and stalemate validation.
 - FEN string parsing and game-to-FEN conversion.
 - Support of the Atomic chess variant - http://lichess.org/variant/atomic
 - Support of the King of the Hill chess variant - https://en.lichess.org/variant/kingOfTheHill
 - Support of the Three-check chess variant - https://en.lichess.org/variant/threeCheck
 - Support of the Antichess variant - https://en.lichess.org/variant/antichess
 - Support of the Horde variant - https://en.lichess.org/variant/horde
 - Support of the Racing Kings variant - https://en.lichess.org/variant/racingKings
 - Support for claiming draw for the 50 move rule.

Planned features:

 - Draw on threefold repetition
 - Draw on insufficient mating material

## NuGet

Chess.NET is available on NuGet, compiled for .NET Standard 1.3.

https://www.nuget.org/packages/ChessDotNet/  
https://www.nuget.org/packages/ChessDotNet.Variants/


