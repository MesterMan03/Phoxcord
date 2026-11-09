# Phoxcord

**The fox in the machine.**

Phoxcord is an early-stage community project exploring the next generation of Discord desktop client modifications.

## Why Phoxcord?

On November 4, 2026, Discord co-founder and CTO Stanislav Vishnevskiy confirmed that Discord is rebuilding its client in **Rust**. The desktop application will move away from **Electron** and use **GPUI** for its native interface. Discord has also demonstrated an early build known as **Discord Phoenix**.

This is an exciting change for the application's performance and architecture, but it also fundamentally changes how client modifications can work. Existing modification techniques built around Electron and Discord's JavaScript frontend cannot simply be carried over to the new native client.

**Phoxcord aims to explore what comes next.**

Once Discord Phoenix becomes available for examination, we intend to research its architecture and investigate a new, extensible approach to native client modifications. Our longer-term ambition is to provide a framework and plugin API that make it possible for developers to build their own client-side features without having to reverse-engineer the application themselves.

## Our goals

- Research the architecture and behaviour of Discord's new native desktop client.
- Explore viable, maintainable approaches to native client instrumentation and extension.
- Design a modular framework that separates Discord-specific integration from plugins.
- Investigate a developer-friendly plugin API, potentially with TypeScript support.
- Share findings and collaborate openly with the community.

## Current status

**Planning / awaiting access to Discord Phoenix.**

No functional client modification framework exists yet. The technical approach, supported platforms, plugin APIs, and feasibility of native integration are all **to be determined by research**. We do not have a release date or working build to announce.

For now, this repository is a home for the idea and a place to follow its development.

## Sources

- [Stanislav Vishnevskiy's announcement (November 4, 2026)](https://x.com/svishnevskiy/status/2118081920194203799) — confirms Rust, the move away from Electron, and the use of GPUI.
- [The Verge: Discord is ditching Electron (November 5, 2026)](https://www.theverge.com/news/1027379/discord-ditching-electron-web-app) — reporting on the native client rewrite.
- [Inven Global: Discord CTO confirms the rebuild (November 4, 2026)](https://www.invenglobal.com/articles/28182/discord-cto-confirms-the-desktop-and-mobile-apps-are-being-rebuilt-in-rust) — further details and context.

## Disclaimer

Phoxcord is an independent community initiative and is **not affiliated with, endorsed by, or sponsored by Discord Inc.** Discord and related names are trademarks of their respective owners.
