# MusicApp
An experimental, modular music player for the 21st century.

# Why?
This project was created as an open-source and cross-platform alternative to MusicBee, since it is Windows-only. It also aims to serve as a *free* replacement for multiple music streaming apps (including custom clients such as Cider), allowing you to have all of your streaming services and local music in one place.

We have a few goals in mind:
- Cross-platform from the start, all code we ship must support Windows, Linux and macOS (and maybe mobile platforms at a later time).
- Simple and modular codebase, easy to build upon (ability to provide different audio backend and user database implementations).
- Support for different "lyric service providers", such as Musixmatch or lyrics from Apple Music API, etc.
- Support for multiple "song service providers" (e.g. streaming services, local filesystem, etc) at the same time.
- Out of the box support for some of the most popular streaming services, such as:
  - Spotify (premium account required)
  - Apple Music (paid account required, obviously)
  - Soundcloud
- Built-in support for the `BASS` audio backend, with various BASS effects and subsystems such as ASIO/WASAPI bundled in.
- Both a CLI ""GUI"" and (primarily) Avalonia app, of course working on both Windows, Linux and macOS.

More info will be shared soon, stay tuned.
