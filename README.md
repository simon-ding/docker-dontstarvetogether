# Don't Starve Together
> Dockerfile for building a [Don't Starve Together][website] dedicated-server image.

[![Build Status](https://img.shields.io/travis/dst-academy/docker-dontstarvetogether/develop.svg)](https://travis-ci.org/dst-academy/docker-dontstarvetogether)
[![GitHub Release](https://img.shields.io/github/release/dst-academy/docker-dontstarvetogether.svg)](https://github.com/dst-academy/docker-dontstarvetogether/releases/latest)
[![Docker Pulls](https://img.shields.io/docker/pulls/dstacademy/dontstarvetogether.svg)](https://hub.docker.com/r/dstacademy/dontstarvetogether/)
[![License](https://img.shields.io/github/license/dst-academy/docker-dontstarvetogether.svg)](https://github.com/dst-academy/docker-dontstarvetogether/blob/develop/LICENSE.md)
[![Steam](https://img.shields.io/badge/steam-join-1b2838.svg)](https://d3a7.link/steam)
[![Discord](https://discordapp.com/api/guilds/215170368959283200/embed.png)](https://d3a7.link/discord)

---

This repository provides a `Dockerfile` for building the DST:A Dedicated Server
for the online multi-player survival game [*Don't Starve Together*][website].

## Features
- [x] Configuration via **ENV** variables.
- [x] Customized **world generation** via `leveldataoverride.lua`.
- [x] Mods and custom **mod-configuration**.
- [x] Connected worlds via **sharding**.
- [x] Control the server directly on the **CLI**.
- [x] **World-persistence** on container destruction.
- [ ] Automatic update of game files.
- [ ] Automatic update of mod files.
- [x] **Sharing** game and mod-files between instances.

## Documentation
- [Setup][docs-setup]
- [Configuration][docs-configuration]
- [Commands][docs-commands]
- [Usage][docs-usage]
- [Examples][docs-examples]

## Contribution
Do you want to contribute to the project?
Check out our [contribution guide][contribution-guide].

## Frequently Asked Questions

- **Why does Steam take so long to update the game?**  
  It can happen that Steam takes a really long time to update the game. This is a known problem with
  SteamCMD - sort of a bug. One solution is to install a DNS cache on your system, which was reported
  to help regarding download speed.

## References and Links
- [Dedicated Server Discussion (Klei Forums)][reference-dedicated]
- [Shards and Migration Portals (Klei Forums)][reference-shards]
- [Dedicated Server Guide (Wikia)][reference-guide]
- [Server Console Commands (Wikia)][reference-commands]
- [DST Server Deploy Script][reference-script]
---

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

[docs-setup]: /docs/setup.md
[docs-configuration]: /docs/configuration.md
[docs-commands]: /docs/commands.md
[docs-usage]: /docs/usage.md
[docs-examples]: /docs/examples/
[website]: https://www.dontstarvetogether.com/
[contribution-guide]: /CONTRIBUTING.md
[docker-kitematic]: https://kitematic.com/
[docker-toolbox]: https://www.docker.com/docker-toolbox
[reference-dedicated]: https://forums.kleientertainment.com/forum/83-dont-starve-together-beta-dedicated-server-discussion/
[reference-shards]: https://forums.kleientertainment.com/topic/59174-understanding-shards-and-migration-portals/
[reference-guide]: https://dont-starve-game.wikia.com/wiki/Guides/Don%E2%80%99t_Starve_Together_Dedicated_Servers
[reference-commands]: https://dont-starve-game.wikia.com/wiki/Console/Don't_Starve_Together_Commands
[reference-script]: https://gitlab.com/lego_engineer/dst-server-deploy
