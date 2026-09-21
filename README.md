<b>Tangelo</b> is a 3DS emulator built upon the Citra and Azahar emulator projects.

Features:
- Compatibility with all game files. If a file works with any Citra fork, it works with Tangelo.
- Ability to download system files from official servers. No need for an actual 3DS.
- Compatibility with older CPUs (no SSE4.2 required)
- Compatibility with Android 9
- ZipPass: A new way to exchange StreetPass data through zip files
- Built in cheats
- Amiibo generation
- Better multiplayer compatibility with other Citra forks

Copyright © 2026 Tangelo Emulator Project.

---

![Tangelo](dist/tangelo.svg)

![GitHub Release](https://img.shields.io/github/v/release/MicroWorldwide/Tangelo?label=Current%20Release)
![GitHub Downloads](https://img.shields.io/github/downloads/MicroWorldwide/Tangelo/total?logo=github&label=GitHub%20Downloads)

# Installation

Download the latest release from [Releases](https://github.com/MicroWorldwide/Tangelo/releases).

### Android

Tangelo has its own application ID (`io.github.microworldwide.tangelo`), so it installs and
runs independently alongside any existing Azahar (or other Citra-fork) installation - no
conflicts, no need to uninstall anything else first.

### Cocoon

Cocoon currently targets Azahar by name/application ID; since Tangelo now has its own distinct
ID, it will not be recognized as Azahar by Cocoon. Check with that project for Tangelo-specific
support.

### Batocera

Third-party frontends like Batocera's unofficial add-ons currently target Azahar by name; check
with that project for Tangelo-specific support:

 https://github.com/batocera-unofficial-addons/batocera-unofficial-addons

# ZipPass

ZipPass allows you to share StreetPass data in the form of zip files.<br>
On desktop it is in File > ZipPass. On android it is in the main menu.

- It can only be used when no game is running.
- It requires system files and LLE modules enabled.
- You need to enable StreetPass in your games.
- The export feature will save the StreetPass data of all your games in a xxx.pass.zip file.
- The import feature lets you pick one or several xxx.pass.zip files and will simulate StreetPass tags.
- You can pick as many files as you want for the import but every game has a limit for its queue and anything - beyond that will be ignored.
- This is all pretty experimental so in case of issues, there's a menu to disable StreetPass on every game. You won't lose anything, you will simply need to enable StreetPass again.

# Build instructions

Please refer this repository's [wiki](https://github.com/MicroWorldwide/Tangelo/wiki/Building-From-Source) for build instructions

# Minimum requirements
Below are the minimum requirements to run Tangelo:

### Desktop
```
Operating System: Windows 10 (64-bit), or modern 64-bit Linux
CPU: x86-64/ARM64 CPU (Windows for ARM not supported). Single core performance higher than 1,800 on Passmark
GPU: OpenGL 4.3 or Vulkan 1.1 support
Memory: 2GB of RAM. 4GB is recommended
```
### Android
```
Operating System: Android 9.0+ (64-bit)
CPU: Snapdragon 835 SoC or better
GPU: OpenGL ES 3.2 or Vulkan 1.1 support
Memory: 2GB of RAM. 4GB is recommended
```

# Where to find this project
- Github: https://github.com/MicroWorldwide/Tangelo
