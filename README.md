# Awesome FiveM Scripts

A curated list of the best places to find **FiveM scripts**: marketplaces, the Cfx.re release forum, open-source frameworks and libraries, tools, and documentation. Free and paid, ESX, QBCore, Qbox and standalone.

> Maintained by [RPScripts](https://rpscripts.net/), which is listed below. Every other entry was checked to be live and relevant on 2026-11-08. Found a better source? See [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Marketplaces and directories](#marketplaces-and-directories)
- [Community releases](#community-releases)
- [Frameworks](#frameworks)
- [Core libraries](#core-libraries)
- [Popular open-source resources](#popular-open-source-resources)
- [Tools](#tools)
- [Documentation](#documentation)
- [Before you install anything](#before-you-install-anything)

## Marketplaces and directories

- [RPScripts](https://rpscripts.net/) - FiveM scripts, MLOs, vehicles and server packs for ESX, QBCore, Qbox and standalone, with a [free resource directory](https://rpscripts.net/free/), [server templates](https://rpscripts.net/fivem-server-templates/) and [docs](https://rpscripts.net/docs/). Every download is scanned for backdoors and escrow-protected files are not sold.
- [Awesome FiveM](https://awesomefivem.com/) - community directory of FiveM resources (successor of the archived `iLLeniumStudios/awesome-fivem` list).

## Community releases

- [Cfx.re forum: FiveM Releases](https://forum.cfx.re/c/releases/7) - the official release board, with tens of thousands of threads from script authors. Search by framework or feature, and read the replies before you install.

## Frameworks

- [ESX Legacy](https://github.com/esx-framework/esx_core) - the long-running role-play framework ([docs](https://docs.esx-framework.org/en)).
- [QBCore](https://github.com/qbcore-fivem/qb-core) - framework core with a large script ecosystem ([docs](https://qbcore.org/docs/)).
- [Qbox](https://github.com/Qbox-project) - QBCore successor built on the Overextended libraries ([docs](https://docs.qbox.re/)).
- [ox_core](https://github.com/overextended/ox_core) - player and vehicle management and persistence.

## Core libraries

Most modern scripts depend on these.

- [ox_lib](https://github.com/overextended/ox_lib) - script library for Lua and JS.
- [oxmysql](https://github.com/overextended/oxmysql) - MySQL resource for FXServer.
- [ox_inventory](https://github.com/overextended/ox_inventory) - slot-based inventory with metadata.
- [ox_target](https://github.com/overextended/ox_target) - standalone "third-eye" targeting.
- [ox_doorlock](https://github.com/overextended/ox_doorlock) - door locks.
- [pma-voice](https://github.com/AvarianKnight/pma-voice) - drag-and-drop voice resource on FiveM's built-in mumble.
- [PolyZone](https://github.com/mkafrin/PolyZone) - zones of different shapes.

## Popular open-source resources

- [vMenu](https://github.com/TomGrobbe/vMenu) - server-side trainer and menu with a full permission system.
- [EasyAdmin](https://github.com/Blumlaut/EasyAdmin) - admin menu for FiveM and RedM.
- [illenium-appearance](https://github.com/iLLeniumStudios/illenium-appearance) - character appearance for QBCore and ESX.
- [NPWD](https://github.com/project-error/npwd) - phone written in TypeScript and React.
- [ps-mdt](https://github.com/Project-Sloth/ps-mdt) - police MDT for QBCore.
- [bob74_ipl](https://github.com/Bob74/bob74_ipl) - fixes and customizes map IPLs.
- [luxart-vehicle-control](https://github.com/TrevorBarns/luxart-vehicle-control) - siren and emergency light controller.
- [screencapture](https://github.com/itschip/screencapture) - screenshots and video for FiveM.
- [SnailyCAD](https://github.com/SnailyCAD/snaily-cadv4) - web-based computer-aided dispatch.

## Tools

- [txAdmin](https://github.com/citizenfx/txAdmin) - the official server management platform.
- [cfx-server-data](https://github.com/citizenfx/cfx-server-data) - default server resources.
- [FiveM Backdoor Scanner](https://rpscripts.net/tools/fivem-backdoor-scanner/) ([source, MIT](https://github.com/rpScripts/fivem-backdoor-scanner)) - flags hidden loaders, remote `load()`, obfuscated payloads and leaked tokens in a resource. Runs in the browser, as CLI and in CI.
- [fivem-fxmanifest-lint](https://github.com/rpScripts/fivem-fxmanifest-lint) - dependency-free `fxmanifest.lua` linter (MIT).
- [Server IP Finder](https://rpscripts.net/tools/server-ip-finder/) - look up a public FiveM server.
- [RPScripts MCP server](https://rpscripts.net/docs/) - catalogue search, compatibility checks and `fxmanifest.lua` / `server.cfg` validation from your AI assistant (`net.rpscripts/fivem` in the MCP registry).

## Documentation

- [FiveM docs](https://docs.fivem.net/docs/) - official scripting manual and natives.
- [fivemdocs.com](https://fivemdocs.com/) - guides for server owners and script developers.
- [RPScripts docs](https://rpscripts.net/docs/) - install guides and framework notes.

## Before you install anything

- Read the code. Check `fxmanifest.lua`, `server` files and anything that calls `load`, `PerformHttpRequest` or obfuscated blobs.
- Skip cracked and leaked paid scripts. They are the most common source of backdoors.
- Check framework support (ESX, QBCore, Qbox) and the dependency list before you buy or download.
- Test on a staging server first, never on live.

## License

[CC0 1.0](LICENSE). Use this list however you like.
