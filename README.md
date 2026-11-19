<div align="center">

# 🌍 PhantomWorlds

**Create, load, copy, back up and teleport between worlds on Bukkit-based Minecraft servers.**

![Spigot / Paper](https://img.shields.io/badge/server-Spigot%20%7C%20Paper-f59e0b)
![Java 8+](https://img.shields.io/badge/Java-8%2B-orange?logo=openjdk&logoColor=white)
![PlaceholderAPI](https://img.shields.io/badge/PlaceholderAPI-optional-0891b2)
[![License: AGPL-3.0-or-later](https://img.shields.io/badge/license-AGPL--3.0--or--later-blue)](LICENSE.md)

> BlockStorm's fork of [TheNewEconomy/PhantomWorlds](https://github.com/TheNewEconomy/PhantomWorlds).

</div>

---

PhantomWorlds is a world manager plugin for server administrators. Everything runs through one command, `/pw`:
create a world with its generator options, load and unload it, copy or delete it, back it up, and send players to
it. Worlds made or imported with PhantomWorlds are loaded again on every start, together with their per-world
settings.

## ✨ At a glance

- 🌱 Create worlds with environment, type, seed, generator, structures, mobs, PvP and difficulty options
- 📂 Load, unload, import, copy and delete worlds; deleted worlds are archived as a zip first by default
- 💾 Manual and scheduled zip backups per world
- 📍 Custom spawn points, a default world for new players, and respawn handling
- 🎮 Per-world game mode, potion effects and access whitelist
- 🌀 Redirect nether and end portals to another world, or transfer players to another server
- 🏷️ PlaceholderAPI placeholders for the player's world name, time and environment

## 🔧 What this fork changes

- `master`: CI builds and a release workflow, plus a dependency fix so the project builds again. No plugin code
  changes.
- A fix for creating worlds on 1.8 servers is on branch `fix/carbon-1.8`
  ([PR #2](https://github.com/BlockStormHU/mc-phantomworlds-fork/pull/2)) and is not in `master` yet.

## 📖 Documentation

Everything else is in the [wiki](https://github.com/BlockStormHU/mc-phantomworlds-fork/wiki):

- [Installation](https://github.com/BlockStormHU/mc-phantomworlds-fork/wiki/Installation): requirements, downloads and
  building from source
- [Commands and Permissions](https://github.com/BlockStormHU/mc-phantomworlds-fork/wiki/Commands-and-Permissions)
- [Configuration](https://github.com/BlockStormHU/mc-phantomworlds-fork/wiki/Configuration): `settings.yml` and the
  per-world settings in `data.yml`
- [Placeholders](https://github.com/BlockStormHU/mc-phantomworlds-fork/wiki/Placeholders)
- [Original README](https://github.com/BlockStormHU/mc-phantomworlds-fork/wiki/Original-README) of the upstream project

---

<div align="center">
<sub>Created by <b>lokka30</b> and <b>creatorfromhell</b> (<a href="https://github.com/TheNewEconomy">TheNewEconomy</a>) and contributors · Maintained in this fork by <b>BlockStorm</b> · Licensed under the <a href="LICENSE.md">GNU AGPL v3.0 or later</a></sub>
</div>
