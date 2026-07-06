<p align="center">
  <img src="./images/mainline.jpg" alt="Sanctuary Mainline" width="100%">
</p>


# Sanctuary Mainline

**Sanctuary Mainline** is a community-driven **Free Realms server restoration project** focused on rebuilding, testing, and documenting server-side systems for preservation and development purposes.

This project is not just a launcher or a client tool.
It is mainly focused on the server files, service logic, packet behavior, minigame systems, world entry systems, and backend structures required to bring Free Realms features back to life.

Some systems are partially working, some are unstable, and some are currently sleeping inside ancient data files guarded by mysterious GFX rituals.

> Sanctuary is not just a path into the realm.
> It is the machine trying to wake the realm back up.

---

## About Sanctuary Mainline

Sanctuary Mainline focuses on restoring and testing Free Realms server-side functionality.

The project includes research and development around:

* Server files
* Service responses
* Packet handling
* Minigame logic
* TCG service restoration
* Combat system behavior
* World/minigame entry systems
* GFX transitions and summary screens
* Data cache and content loading
* Missing data reconstruction
* Experimental logic for incomplete systems

The goal is to make these systems easier to understand, test, improve, and eventually preserve in a cleaner and more maintainable way.

## Status Legend

| Icon | Meaning                                |
| ---- | -------------------------------------- |
| ✅    | Working / mostly working               |
| ☑️   | Partially working / needs more data    |
| 💤   | Not finished / sleeping / needs work   |
| 🔍   | Active research / investigation        |
| 🔬   | Experimental                           |
| ‼️   | Very unstable / dangerous magical zone |
| ⁉️   | Unknown / mysterious                   |

---

## Development Progress

| Core Systems                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | World / Extra Systems                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Minigames** <br><br> ✅ Checkers <br> ✅ Chess <br> 💤 Mining <br><sub>I think I found a small bug, checking it.</sub> <br> 💤 Forging <br> 💤 Cooking <br><sub>A bit unstable, still needs recipe systems.</sub> <br> 💤 Harvesting <br> 💤 Smelting <br> 💤 Tower Defense <br> ☑️ Micro-games <br> 💤 Wheels <br> 💤 Treasure War <br> 💤 Pirates Plunderer <br> ☑️ Spot the Difference <br><sub>Still unstable, needs more data.</sub> <br><br> <sub>It looks like each minigame uses its own separate data file or something similar.</sub> <br><br> <sub>I’m preparing a bit of **arcane machine learning magic** to generate estimated data for the missing parts.</sub> | **Minigame Worlds** <br><br> 🔍 Fishing <br><sub>Worlds are active, but not finished yet.</sub> <br> 🔍 Karts <br><sub>Worlds are active, but not finished yet.</sub> <br> 🔍 Derby <br><sub>Worlds are active, but not finished yet.</sub> <br> 💤 Soccer <br> ⁉️ Battles <br><br> <sub>There’s also good news from the racing world.</sub> <br><br> <sub>But because approximately seventeen billion extra GFX files are scattered across reality, the race car key may currently exist in another dimension.</sub> <br><br> <sub>It is believed that organizing files properly would anger the ancient tech gods.</sub> |
| **Integrated TCG Game** <br><br> 🔬 Trading Card Game <br><br> <sub>After a very long silence… the TCG service has finally been reactivated.</sub> <br><br> <sub>The launch gate is open. The native login gate is open.</sub> <br><br> <sub>Now we stand before the mysterious **TCG data cache / content loading** gate.</sub>                                                                                                                                                                                                                                                                                                                                               | **Boombox Thing** <br><br> 🧪 Boombox Packet <br><br> <sub>I wrote a special packet for the Boombox.</sub> <br><br> <sub>Haven’t tested it yet, but eventually I’ll perform that chaotic ritual too.</sub>                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Combat System** <br><br> ‼️ Combat <br><br> <sub>This place is basically a magical disaster zone.</sub> <br><br> <sub>Archer, Brawler, Medic, Ninja, Warrior… and of course, Wizard.</sub> <br><br> <sub>Right now the combat system is being held together by temporary logic, unstable math, and one suspicious wizard making mysterious noises in the background.</sub>                                                                                                                                                                                                                                                                                                   | **Future Systems** <br><br> 💤 Housing <br> 💤 Pets <br> 💤 Guilds <br> 💤 Marketplace <br> 💤 Social systems <br><br> <sub>These systems are not the current main focus, but they may be researched later.</sub>                                                                                                                                                                                                                                                                                                                                                                                                          |

---
## Technical Notes

Some Free Realms systems appear to depend on separate data files, GFX files, cache files, service responses, or special transition logic.

Because of this, a feature may open, connect, or launch successfully, but still fail when the client expects another server response, content cache entry, summary file, or missing data structure.

This project is focused on understanding and rebuilding those missing server-side parts.

---

## Current Focus

The current focus of Sanctuary Mainline includes:

* Testing minigame server behavior
* Restoring missing service responses
* Investigating TCG content loading
* Researching combat system logic
* Testing world-based minigame entries
* Checking GFX transition requirements
* Improving server-side stability
* Reconstructing missing or incomplete data
* Documenting how restored systems work

---

## Disclaimer

Sanctuary Mainline is an independent community project created for Free Realms preservation, research, and development purposes.

This project is not affiliated with, endorsed by, or officially connected to Sony Online Entertainment, Daybreak Game Company, or any original Free Realms rights holders.

All Free Realms-related names, assets, and references belong to their respective owners.

---
