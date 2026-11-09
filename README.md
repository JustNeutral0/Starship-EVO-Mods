# Starship EVO Mods

JustNeutral0's mods for Starship EVO. Each mod has its own repository with its releases, so
[Starship Uplink](https://github.com/MadTheDog/Starship-Uplink) can install and update it.

| Mod | What it is | Needs | Repository |
|---|---|---|---|
| **EvoCore** | The Lua Computer: a programmable logic block with graph and Lua editors, monitors you can draw on, and animation for ship joints. Also the base the other mods build on. | | [StarshipEVO-EvoCore](https://github.com/JustNeutral0/StarshipEVO-EvoCore) |
| **Cockpit Displays** | Windowless cockpits: screens and painted surfaces showing live outside views, and HUD canvases for the Lua Computer. | EvoCore | [StarshipEVO-CockpitDisplays](https://github.com/JustNeutral0/StarshipEVO-CockpitDisplays) |
| **Mod Settings** | One window (F11 or the Escape menu) for every mod's settings and tabs. | EvoCore | [StarshipEVO-ModSettings](https://github.com/JustNeutral0/StarshipEVO-ModSettings) |

More mods will be added here as they're ready for testing.

Each mod's source code is in its repository (MIT licence), with how to build it in its README. EvoCore's
[MODDING.md](https://github.com/JustNeutral0/StarshipEVO-EvoCore/blob/main/MODDING.md) explains how other mods can
build on it.

## Installing

1. Get [Starship Uplink](https://github.com/MadTheDog/Starship-Uplink) and create a profile for your game.
2. For each mod, use **Add from GitHub** with its repository (e.g. `JustNeutral0/StarshipEVO-EvoCore`), pick its
   zip, and install it. Install EvoCore first.
3. Launch through Uplink.

These are early test releases, built against Starship EVO early-access 26w45a, and single-player only for now.
Report problems in the Issues of the mod's own repository.

## Licence

MIT. Starship EVO itself belongs to its developers.
