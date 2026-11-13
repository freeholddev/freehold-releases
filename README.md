# Freehold

> **Freehold — Rule, don't manage**
> A self-organising settlement economy for Minecraft.

Freehold is a settlement and economy game inside Minecraft. You found a settlement with a
charter, decide what is built where and which policy holds, and watch it organise itself.

**Policy instead of micromanagement.** You set the rules — where free residents go to work,
who gets a scarce good, what is built next. Your settlement does the rest: it gives its people
work, makes and carries its goods, walks the roads you draw and pushes its boundary out. You
never decide who carries which log.

## What is in the game

- **Full production chains.** Fell trees and plant new ones, saw planks, make and wear out
  tools, quarry stone, grow wheat, catch fish, pick apples, grind and bake, burn charcoal,
  sink a mine, smelt and forge iron, brew beer and pour it in a tavern.
- **Goods are carried, not teleported.** Every load goes from door to door, so where you
  build decides how fast things flow.
- **Roads you draw.** Lay roads and junctions by hand; with their traffic they grow from dirt
  to wood to stone, outwards from buildings of the second level.
- **Buildings that grow.** A building kept busy in a busy neighbourhood rises to a second
  level on its own.
- **Beyond your boundary.** Connect a neighbouring village through a gate, trade with it for
  emeralds, and keep soldiers in watchtowers and barracks against the raiders that come for
  your settlement.
- **Play together.** Offer friends a role in your settlement — member or visitor — and they
  accept it in chat. Settlements can attack each other and take each other's watchtowers.

**[The Freehold Wiki](https://freeholddev.github.io/freehold-releases/wiki/)** is the
reference for players and server admins: every building, good, tool, gesture and message,
the rules behind them, and every setting a server can change.

## Status: beta

Freehold is in **public beta** (`0.x`). It is playable, but it is not finished: new features
are still on the way, numbers are still being tuned, and **a save may not carry over from one
version to the next**. Keep a backup of any world you care about, and start a fresh one when
you update.

What changed between versions is in the [changelog](docs/CHANGELOG.md).

## Download and install

Freehold is a NeoForge mod and has to be installed **on the server and on every client**.

- Minecraft Java **26.1.2**
- NeoForge **26.1.2.122** or newer

The mod file is on the
[releases page](https://github.com/freeholddev/freehold-releases/releases). Put it into the
`mods` folder of your game or server. To begin, craft a charter — an emerald framed in eight
planks — and follow
[First steps](https://freeholddev.github.io/freehold-releases/wiki/start/first-steps.html).

## Feedback and bugs

Please report only problems you can clearly reproduce, as an
[issue](https://github.com/freeholddev/freehold-releases/issues). A report helps when it says
which Freehold version you play, the steps that lead to the problem, what you expected and what
happened instead, with `logs/debug.log` attached, and the file from `crash-reports/` if the game
crashed. A problem that cannot be reproduced usually cannot be fixed.

## Modpack permission

**You may use Freehold in any modpack, public or private, without asking.** This
includes redistributing the unmodified mod file as part of the pack, on any platform.
Two things come with it:

- **Configuration and datapacks.** Tune the starting values, and write and ship your
  own goods, building and blueprint definitions.
- **Derived assets, if you say where they came from.** Textures, models and blueprints
  that start from ours may go in your pack as long as the pack names Freehold as their
  origin.

**If you build a theme**, everything above the footprint is yours — height, roof, facade.
The footprint, the foundation and the places people work stay fixed, so a themed building
fits wherever the original does. Keep each building's one distinguishing feature, and keep
walls, roof and frame visibly apart, or every building starts to look like every other. See
[Making a theme](https://freeholddev.github.io/freehold-releases/wiki/admin/making-a-theme.html).

## License

**All rights reserved, for code and assets alike.** [LICENSE](LICENSE) has the terms and
the modpack permission in full; [ASSETS-LICENSE.md](ASSETS-LICENSE.md) says which files
count as assets, since the permission turns on that.
