# Blockcraft

An original voxel sandbox game: build, explore and survive. Made by Elite Eagle Development.

## Download (Windows)

**[Download BlockcraftSetup.exe](https://github.com/EliteEagle2/BlockCraft/releases/latest/download/BlockcraftSetup.exe)**
(about 3 MB). It installs Blockcraft Launcher, which downloads the game and keeps it up to date.
Java is included; you do not need to install anything else.

No internet on the computer you want to play on? Use the full installer, which includes the game:

- [BlockcraftSetup-Offline.exe](https://github.com/EliteEagle2/BlockCraft/releases/latest/download/BlockcraftSetup-Offline.exe)
- [BlockcraftLauncher.msi](https://github.com/EliteEagle2/BlockCraft/releases/latest/download/BlockcraftLauncher.msi) (for silent installs: `msiexec /i BlockcraftLauncher.msi /quiet`)

The installers are not code-signed yet, so Windows may show "Windows protected your PC". Choose
**More info**, then **Run anyway**.

Your worlds, screenshots and settings are kept when you update or uninstall, unless you tick
"Also delete my game data" while uninstalling.

## What is in this repository

The release files the launcher installs (one GitHub release per game version, and one per
launcher version), and the lists it reads to find them: `version_manifest.json` (game versions),
`launcher_manifest.json` (launcher updates) and `news.json` (the launcher's news). The source code
is not public.

## Third-party software

Blockcraft and its launcher include: an OpenJDK Java runtime and OpenJFX (GPLv2 with the
Classpath Exception), LWJGL (BSD 3-Clause), JOML (MIT), Gson and Error Prone annotations
(Apache 2.0), and the Pixelify Sans and Silkscreen fonts (SIL Open Font License 1.1). Their licenses are in the
installed `runtime/legal` folder and inside the respective jars. All game art is original.
