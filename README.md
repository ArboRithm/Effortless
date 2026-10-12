<div align="center">

<img src="https://arborithm.github.io/Effortless/brand/pancake.svg" alt="Effortless" width="160" />

# Effortless

**Drive your software projects with your AI agents — on your machine.**

Framing, backlog, development standards, quality bar and delivery, from the first idea to the release.

[![Latest release](https://img.shields.io/github/v/release/ArboRithm/Effortless?label=release&color=1F5A44)](https://github.com/ArboRithm/Effortless/releases/latest) [![Platforms](https://img.shields.io/badge/macOS%20%C2%B7%20Windows-1F5A44?label=platforms)](#download) [![Documentation](https://img.shields.io/badge/docs-arborithm.github.io-AD8B4A)](https://arborithm.github.io/Effortless/en/)

[**Download**](https://github.com/ArboRithm/Effortless/releases/latest) · [**Documentation**](https://arborithm.github.io/Effortless/en/) · [**MCP reference**](https://arborithm.github.io/Effortless/en/reference/mcp/) · [Français](README.fr.md)

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://arborithm.github.io/Effortless/captures/en/dark/dashboard.png" />
  <img src="https://arborithm.github.io/Effortless/captures/en/light/dashboard.png" alt="The Effortless dashboard: work in progress, what awaits your decision, statistics and tiles" width="900" />
</picture>

</div>

## Why Effortless

AI agents write code fast. Keeping a project framed, tracked and shippable is another story. Effortless gives you and your agents one shared, structured view of the project — what is decided, what is in progress, what comes next — and a method to move it forward, step by step.

You decide. Your agent executes. Effortless keeps everything in order.

## Highlights

- **Resume dashboard** — open a project and see at once what is in progress, what awaits your decision and what comes next. Compose your own tiles.
- **The OPALE cycle** — every story goes through the same phases (Observe, Position, Articulate, Launch, Execute), guarded by the engine rather than by memory.
- **Backlog and change register** — epics, stories and tasks, anomalies and feature requests, and the history of your work sessions.
- **Knowledge** — decisions, open questions and framing documents, scoped to the project, an epic or a story.
- **Quality, measured** — drift between code and documentation, repository state, shared development standards.
- **Delivery** — version, tag and build, project-wide or module by module, after a summary you confirm; internal and public channels.
- **Your agents, connected** — Effortless deploys its MCP server into your AI tools and gives them an up-to-date guide of every verb they can call.

## Works with your agents

Effortless exposes its engine through the [Model Context Protocol](https://modelcontextprotocol.io). Agents built on frontier models use it best — **Claude Code**, **Codex** or **Antigravity**, for example; **opencode** support is in progress.

Deploy it from the app (**Preferences › MCP & Skills**) or ask your agent to call `effortless_deploy`. Then just talk to it:

> *"Start an epic for the invoicing module, with a first story for the quote form."*

Every verb is documented in the [MCP reference](https://arborithm.github.io/Effortless/en/reference/mcp/), and the [agent guide](https://arborithm.github.io/Effortless/en/agent/) walks through real use cases.

### Recommended setup

Effortless works best with a **command-line agent — Claude Code, Codex or Antigravity — started from the root of your project**, the folder that contains `effortless.json`:

```sh
cd ~/Projects/my-project
claude        # or codex, or your agent's command
```

The Effortless MCP server recognizes your project from that folder, and your agent reads its instructions there. Keep the Effortless app open alongside to watch, live, what the agent does. The VS Code integrated terminal, opened on the project folder, is just as comfortable. [More in the agent guide](https://arborithm.github.io/Effortless/en/agent/#working-at-your-best-the-agent-opened-at-the-project-root).

Your code can live in the project, in other repositories you develop, or in **shared sources** that Effortless leaves untouched — no git hook, no commits. Pick your work mode and code layout before you start: [Choosing your setup](https://arborithm.github.io/Effortless/en/guide/setup.html).

## Download

| Platform | Requirements | File |
|---|---|---|
| **macOS** | Apple Silicon, macOS 10.15 or later | `Effortless_<version>_standard_aarch64.dmg` |
| **Windows** | x64 | `Effortless_<version>_standard_x64-setup.exe` |
| **Windows** | ARM64 | `Effortless_<version>_standard_arm64-setup.exe` |

Get them from the [latest release](https://github.com/ArboRithm/Effortless/releases/latest). Effortless then offers its own updates — nothing installs without your consent.

The macOS build is signed and notarized by Apple. The Windows installer is not signed yet: if SmartScreen warns you, choose **More info**, then **Run anyway**.

## Getting started

1. **Install** Effortless and create your profile on first launch.
2. **Open a project** — create a new one with the creation assistant, or adopt an existing repository.
3. **Connect your agent** from **Preferences › MCP & Skills**.
4. **Open a terminal at the project root**, start your agent there, and talk to it.

The [getting started guide](https://arborithm.github.io/Effortless/en/guide/) covers each screen in detail.

## Privacy

Effortless runs on your machine. Your projects stay in your folders and belong to you. There is no telemetry and no data collection.

## Support

- **Documentation** — [arborithm.github.io/Effortless](https://arborithm.github.io/Effortless/en/)
- **Bugs and suggestions** — [open an issue](https://github.com/ArboRithm/Effortless/issues)
- **Contact** — app@arborithm.fr

---

<sub>Effortless is published by ArboRithm and free to use under its [license agreement](LICENSE.md).</sub>
