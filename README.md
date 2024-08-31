# fnrir's fork of p5rcbt

A plugin for loading loose files instead of repacking a CPK, powered by [Skyline](https://github.com/skyline-dev/skyline).

## Changes from upstream

- Fixed up stuff that `cargo clippy` didn't like
- Ran `cargo fmt`
- Enabled the `is_platform_pc` hook
- Changed the mod directory to `sd:/mods/Persona 5 Royal`
- Improved downcasting for PanicHookInfo
  (i.e. it should give better error messages)

## Features

This comes built-in with the following features:

- File logger (use the [following executable](https://github.com/Coolsonickirby/skyline-logger-files/releases/download/1.0.0/skyline_logger_rust.exe) for logging. Use 127.0.0.1 as the IP if you plan to mod on Ryujinx)
- Loose file loading (Valid paths are ``sd:/mods/Persona 5 Royal`` and ``sd:/atmosphere/contents/01005CA01580E000/romfs/CPK/BIND``)
- 60 FPS patch

## Downloads

Head to the [release](https://github.com/fnr1r/p5rcbt/releases/latest) page to get the latest build!  

Beta builds are sometimes posted there, but please be aware that you are expected to provide constructive feedback when using them.
