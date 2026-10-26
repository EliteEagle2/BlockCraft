# Blockcraft

An original voxel sandbox game: build, explore and survive in a blocky world, then uncover the story of
the sky that fell. Made by Elite Eagle Development.

Blockcraft plays like the classic block-building survival games you already know (mine, craft, build,
survive the night) with its own art, its own world and its own story. Every texture, sound and line of
code is original.

## The game

**Survive and build.** Mine with tools of wood, stone, iron, gold and diamond, smelt ores in a furnace,
craft armor, manage hunger and health, swim, dig, and build anything you can imagine. Water and lava
flow, caves wind underground, and every block can be broken and placed.

**The Shattered Sky.** Long ago the sky was joined to the land, until something broke it apart into
the floating islands of the Aether. Pieces of it still fall as meteors. Six ancient Anchors lie in
the deserts, jungles, snowfields, mountains, oceans and deep caves, each with its own puzzle, its own
guardian and its own reward. Restore them in any order, rise to the Aether, Blockcraft's original sky
dimension, and decide the fate of the world.

**Play your way.** Every world chooses **Story** (follow the legend, meet the people who remember it)
or **Freeroam** (no story, every place still reachable). A Freeroam world can switch to Story any
time.

**Blockcraft extras.** Settlements to grow and trade with, roguelike dungeons, new weapons such as
spears, war hammers and daggers, a stamina and dodge system, seasons and temperature, meteor showers
and blood moons, a minimap with waypoints, a recipe browser, inventory sorting and a journal that
records your discoveries. Anything that changes core gameplay can be turned off for a classic-style
world.

**Resource packs.** Blocks, items and the Classic menu style work with resource packs made for the
popular block game, so you can bring your favourite textures.

## Where it is now

Blockcraft is in **Alpha**. It's being built in public updates; each one adds a piece of the plan:

| Version | Update | What it adds |
|---|---|---|
| 0.1.0 | First Light | The world, building, crafting, menus and resource packs |
| 0.2.0 | Survival Update | Tool tiers, mining, hunger, damage, XP, armor, water and lava, swimming, buckets, the furnace |
| 0.2.1 | UI Refresh | A new look for every menu, inventory and the HUD |
| 0.3.0 | Home Update | Chests, beds, stairs, doors and more building blocks, recipe browser |
| 0.4.0 | World Update | New biomes, mountains, rebuilt caves, weather, the first Anchors |
| 0.5.0 | Creatures Update | Animals, monsters, combat, bows and shields, new weapons, the first boss |
| 0.6.0 | Harvest Update | Farming, breeding, fishing, seasons and temperature |
| 0.7.0 | Sound Update | Music and sound, advancements, world events, the journal, Story and Freeroam |
| 0.8.0 | Magic Update | Enchanting, anvils and brewing |
| 0.9.0 | Redstone Update | Redstone and the Anchors' puzzle mechanisms |
| 0.10.0 | Adventure Update | Settlements, dungeons and all six Anchor trials |
| **1.0.0** | **Full release** | The Aether, the final boss and the ending of The Shattered Sky |
| 1.1.0 | Together Update | Multiplayer, dedicated servers and join codes |

Plans can change as the game grows. Snapshots (test versions of the next update) can be turned on in
the launcher under **Settings > Show snapshots**; they may be unstable, so back up your worlds first.

## Download (Windows)

**[Download BlockcraftSetup.exe](https://github.com/EliteEagle2/BlockCraft/releases/latest/download/BlockcraftSetup.exe)**
(about 3 MB). It installs Blockcraft Launcher, which downloads the game and keeps it up to date.
Java is included; you do not need to install anything else.

No internet on the computer you want to play on? Use the full installer, which includes the game:

- [BlockcraftSetup-Offline.exe](https://github.com/EliteEagle2/BlockCraft/releases/latest/download/BlockcraftSetup-Offline.exe)
- [BlockcraftLauncher.msi](https://github.com/EliteEagle2/BlockCraft/releases/latest/download/BlockcraftLauncher.msi) (for silent installs: `msiexec /i BlockcraftLauncher.msi /quiet`)

The installers are not code-signed yet, so Windows may show "Windows protected your PC". Choose
**More info**, then **Run anyway**. Every release includes a `SHA256SUMS.txt` so you can check your
download.

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

Blockcraft is an independent game. It is not affiliated with, endorsed by or connected to Mojang
Studios, Microsoft or Minecraft.
