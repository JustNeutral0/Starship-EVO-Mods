# Starship EVO Mods

JustNeutral0's mods for Starship EVO. Each mod has its own repository with its releases, so
[Starship Uplink](https://github.com/MadTheDog/Starship-Uplink) can install and update it.

| Mod | What it is | Needs | Repository |
|---|---|---|---|
| **EvoCore** | The Lua Computer: a programmable logic block with graph and Lua editors, monitors you can draw on, and animation for ship joints. Also the base the other mods build on. | | [StarshipEVO-EvoCore](https://github.com/JustNeutral0/StarshipEVO-EvoCore) |
| **Cockpit Displays** | Windowless cockpits: screens and painted surfaces showing live outside views, and HUD canvases for the Lua Computer. | EvoCore | [StarshipEVO-CockpitDisplays](https://github.com/JustNeutral0/StarshipEVO-CockpitDisplays) |
| **Mod Settings** | One window (F11 or the Escape menu) for every mod's settings and tabs. | EvoCore | [StarshipEVO-ModSettings](https://github.com/JustNeutral0/StarshipEVO-ModSettings) |
| **EvoFixes** | Game fixes and quality-of-life changes, each switchable: multiplayer fixes (power on joined players' ships, passengers following a warp), Pipe Thin, life support, NPC ships, glass panes, galaxy sky, a Repair Dock. | EvoCore 0.9.81+ | [StarshipEVO-EvoFixes](https://github.com/JustNeutral0/StarshipEVO-EvoFixes) |

More mods will be added here as they're ready for testing.

Each mod's source code is in its repository (MIT licence), with how to build it in its README. EvoCore's
[MODDING.md](https://github.com/JustNeutral0/StarshipEVO-EvoCore/blob/main/MODDING.md) explains how other mods can
build on it.

## Installing

**First, the game build:** these mods are built for the **Unity 6 beta** of Starship EVO, not the default build. In Steam, right-click Starship EVO, open **Properties > Betas**, pick **unity6**, and let it update. The mods don't work on the default build (character creation breaks, for one).

1. Get [Starship Uplink](https://github.com/MadTheDog/Starship-Uplink) and create a profile for your game.
2. For each mod, use **Add from GitHub** with its repository (e.g. `JustNeutral0/StarshipEVO-EvoCore`), pick its
   zip, and install it. Install EvoCore first.
3. Launch through Uplink.

These are early test releases, built against Starship EVO early-access 26w45a (Unity 6 beta branch).
Report problems in the Issues of the mod's own repository.

## Multiplayer

**Modded multiplayer works.** It was widely believed that modding, Keel and Uplink in particular, broke multiplayer.
It doesn't. In a real two-PC Steam game with Uplink, EvoCore and EvoFixes, both players flew each other around, rode
as passengers, built, and used blocks together. The bugs players hit are the game's own; mods only passed them
through. [EvoFixes](https://github.com/JustNeutral0/StarshipEVO-EvoFixes#multiplayer-works-with-mods) fixes the two
big ones (power on ships a joined player spawns, and passengers stranded by a warp) and lists what is still broken.
Install EvoFixes on every player's game.

The Lua Computer (EvoCore) runs separately on each player's machine and isn't multiplayer-safe yet.

## Licence

MIT. Starship EVO itself belongs to its developers.
