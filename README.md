# RNR Anti-Cheat

An experimental client-side anti-cheat for Counter-Strike 1.6, written in C++. This repository is an archived snapshot of work from around 2014–2017.

## What is included

- GoldSrc client and engine integration
- Runtime memory hotspot checks
- Module whitelist and blacklist support
- Experimental code-checksum and loaded-module inspection routines
- Time-based token generation exposed through the `rnr_auth` client cvar

Some checks are unfinished or disabled in the source, so this should be treated as a prototype rather than a production security system.

## Building

Open `rnr_ac.sln` in Visual Studio. The included legacy project builds a 32-bit Windows DLL and uses the older `.vcproj` format. Importing or upgrading the project will likely be necessary in a modern Visual Studio version.

## Status

Archived and unmaintained. The implementation relies on old GoldSrc structures, offsets, and Windows APIs and is not expected to work unchanged with current game builds.

This code is available for historical and defensive research. Test only on systems and game environments you own or are authorized to assess.
