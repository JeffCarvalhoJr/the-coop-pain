# CO-OP Pain

**CO-OP Pain** is a community-driven fork of [Dynamite](https://github.com/unknown321/dynamite), a 2-player co-op mod for **Metal Gear Solid V: The Phantom Pain**.

The goal of CO-OP Pain is to **improve, maintain, and expand upon the original Dynamite codebase**, building on its reverse-engineering work while improving stability, maintainability, synchronization, and extensibility.

This project exists because the original work demonstrated that MGSV's existing multiplayer infrastructure could be adapted to support cooperative gameplay in regular single-player missions. CO-OP Pain aims to continue developing that idea.

> [!WARNING]
> You MUST roll back your game to the required version before installing.
>
> See the original project's [related issue](https://github.com/unknown321/dynamite/issues/136) for details.

[Download](https://github.com/unknown321/dynamite/releases/latest)

Things won't always work as you expect them to.

This project is still experimental. Please read the user documentation before playing, and expect bugs, crashes, synchronization issues, and mission-specific problems.

---

## Requirements

1. An unmodified Steam version of **MGSV: The Phantom Pain** (regular version; JP is not supported)
2. An online connection
3. Some free disk space
4. A friend to play with

---

## Documentation

[Making of](./docs/MAKING_OF.md)

The original [Making Of](https://github.com/unknown321/dynamite/blob/master/docs/MAKING_OF.md) is highly recommended for anyone interested in how cooperative gameplay was achieved through reverse engineering of the FOX Engine.

[User documentation](./webui/docs/docs.md)

[Build from source](./docs/BUILD.md)

---

## What is CO-OP Pain?

CO-OP Pain is focused on evolving the original Dynamite project rather than replacing its foundation.

Our current priorities include:

* improving runtime stability
* fixing crashes and synchronization issues
* improving session and connection handling
* making the codebase easier to maintain
* improving the separation between FOX Engine hooks and gameplay logic
* improving synchronization and networking reliability
* expanding mission compatibility
* adding new cooperative features

The underlying approach remains the same: **reuse and extend the multiplayer capabilities already present in MGSV instead of implementing an entirely new multiplayer system from scratch.**

---

## Origins & Credits

CO-OP Pain is a fork of **Dynamite**, created by **[unknown321](https://github.com/unknown321)**.

The original Dynamite project and its reverse-engineering work are the foundation of this project.

### Original project

https://github.com/unknown321/dynamite

### Original author

[unknown321](https://github.com/unknown321)

### Original repository

[github.com/unknown321/dynamite](https://github.com/unknown321/dynamite)

We strongly recommend reading the original project's [Making Of](https://github.com/unknown321/dynamite/blob/master/docs/MAKING_OF.md) to understand the discoveries and engineering behind the original implementation.

This project does **not** claim the original reverse-engineering work as its own.

---

## Gameplay

The following videos demonstrate gameplay from the original Dynamite project and are preserved here as references to the work this fork is based on.

<a href="https://www.youtube.com/watch?v=dja6IPYZ_p4">Mission 5 — OVER THE FENCE (41:06)</a>

<a href="https://www.youtube.com/watch?v=4xIB7_qEVwI">Mission 15 — FOOTPRINTS OF PHANTOMS (07:25)</a>

<a href="https://www.youtube.com/watch?v=JJQbVnNBghE">General gameplay, funny cuts (13:59)</a>

<a href="https://www.youtube.com/watch?v=JMAAO8YrxB0">Gameplay, v0.6.0 (Oct 31, 2025), Portuguese (22:55)</a>

---

## Press

[PC Gamer — After 10 years, there's a functioning Metal Gear Solid 5 co-op mod](https://www.pcgamer.com/games/action/after-10-years-theres-a-functioning-metal-gear-solid-5-co-op-mod-so-you-and-a-friend-can-be-played-like-a-damn-fiddle-together/)

---

## Support the Original Project

The original Dynamite project was created and maintained by **unknown321**.

If you want to support the original author's work, you can do so here:

[Boosty](https://boosty.to/unknown321/donate)

---

## Development

This project deals with reverse-engineered game internals, runtime hooks, binary patches, synchronization, Lua scripting, and FOX Engine structures.

Some parts of the codebase are necessarily low-level and game-version-specific.

When contributing, prefer:

* fixes that are reproducible
* clear documentation of reverse-engineered behavior
* isolation of game-specific hacks
* safer session and synchronization handling
* changes that improve maintainability without obscuring the original behavior

When reporting a crash or synchronization problem, please include as much information as possible:

* mission
* host/client role
* steps to reproduce
* logs
* crash information, when available
* video, when useful

---

## Disclaimer

**CO-OP Pain is an unofficial community project.**

It is not affiliated with, endorsed by, sponsored by, or otherwise connected to:

* Konami
* Kojima Productions
* the original developers of the FOX Engine

**Metal Gear Solid V: The Phantom Pain** and related trademarks are the property of their respective owners.

Use this project at your own risk.

Back up your save data before using experimental builds.

---

## License

CO-OP Pain is derived from the original **Dynamite** project.

Please see the repository's [`LICENSE`](./LICENSE) file for the applicable license terms.

When redistributing modified versions of this project, preserve the required license notices, attribution, and the relationship to the original Dynamite project.

---

## Why "CO-OP Pain"?

Because one Phantom Pain wasn't enough.
---

> **A fork built on the shoulders of Dynamite.**
