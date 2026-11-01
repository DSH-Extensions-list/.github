<div align="center">

# DSH Extensions

**Build, visualize, automate — inside DeepSeek Harness.**

Extensions, English editions, and package snapshots from our working DSH setup.

[Explore the collection](#explore-the-collection) · [Installation](#installation) · [About this collection](#about-this-collection)

</div>

---

A practical collection for [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness): create presentations, render diagrams in chat, connect model providers, manage long-running work, and inspect what your agent is doing.

Maintained by [arzvaak](https://github.com/arzvaak). The collection includes our own extensions and adaptations of community projects, with upstream authorship and licenses retained.

## Start here

| I want to… | Start with |
| --- | --- |
| Create and edit a presentation | [Deckforge](https://github.com/DSH-Extensions-list/dsh-deckforge) — Deck Studio, editable PowerPoint output, and an offline HTML presenter. |
| Show charts and diagrams in an answer | [DSH Visuals](https://github.com/DSH-Extensions-list/dsh-visuals) — inline charts, Mermaid diagrams, editable previews, and SVG export. |
| Connect BharatCode or another model endpoint | [Provider Hub](https://github.com/DSH-Extensions-list/dsh-provider-hub) — provider setup and model discovery, with subscription sign-in through the subscriptions plugin. |
| Schedule and track background work | [Task Board](https://github.com/DSH-Extensions-list/dsh-client-ui-task-board) — Kanban tasks, scheduled runs, and execution history. |
| Understand context usage and costs | [Context](https://github.com/DSH-Extensions-list/dsh-context) for context inspection; [Cost Meter](https://github.com/DSH-Extensions-list/bharatcode-cost-meter) for usage and cost tracking. |

## Explore the collection

### Presentations and visuals

| Extension | What it adds | Distribution |
| --- | --- | --- |
| [Deckforge](https://github.com/DSH-Extensions-list/dsh-deckforge) | Create, edit, import, and check native PowerPoint decks in Deck Studio; export an offline HTML presentation. | Source |
| [DSH Visuals](https://github.com/DSH-Extensions-list/dsh-visuals) | Charts, flowcharts, timelines, and Mermaid diagrams rendered inline, with source editing and SVG export. | Source + release package |

### Providers and usage

| Extension | What it adds | Distribution |
| --- | --- | --- |
| [Provider Hub](https://github.com/DSH-Extensions-list/dsh-provider-hub) | BharatCode and OpenAI-compatible endpoint setup, model discovery, and integrated subscription settings. | Source |
| [Subscriptions](https://github.com/DSH-Extensions-list/dsh-plugin-subscriptions) | Subscription-provider adapters and sign-in, including ChatGPT/Codex and GitHub Copilot. | Upstream npm reference |
| [Cost Meter](https://github.com/DSH-Extensions-list/bharatcode-cost-meter) | Conversation costs, usage history, model pricing, and supported provider balance/quota displays. | Package snapshot |

### Tasks, planning, and skills

| Extension | What it adds | Distribution |
| --- | --- | --- |
| [Task Board](https://github.com/DSH-Extensions-list/dsh-client-ui-task-board) | A Kanban board with scheduled agent runs, execution history, and verification gates. | Package snapshot |
| [Planning with Files](https://github.com/DSH-Extensions-list/dsh-planning-with-files) | Persistent task plans, findings, and progress files, with reminders and compaction recovery. | Package snapshot |
| [Skills Manager](https://github.com/DSH-Extensions-list/dsh-skills-manager) | Browse and manage local/project skills, install from GitHub, review updates, and restore backups. | Package snapshot |

### Memory, context, and reliability

| Extension | What it adds | Distribution |
| --- | --- | --- |
| [Engram — English edition](https://github.com/DSH-Extensions-list/dsh-engram-english) | Cross-session memory with user/project separation and searchable stored knowledge. | Source fork |
| [Context](https://github.com/DSH-Extensions-list/dsh-context) | Context composition, token usage, session insights, and agent-family views. | Package snapshot |
| [Tool Call Guard — English edition](https://github.com/DSH-Extensions-list/dsh-tool-call-guard-english) | Neutralizes malformed tool-call JSON in outgoing history so strict providers can accept subsequent requests. | Source fork |
| [Max Tokens Continue](https://github.com/DSH-Extensions-list/max-tokens-continue) | Bounded continuation when a response hits the provider's output-token limit. | Package snapshot |

### Developer tools

| Extension | What it adds | Distribution |
| --- | --- | --- |
| [LSP Actions](https://github.com/DSH-Extensions-list/dsh-lsp-actions) | Language-server diagnostics, formatting, code actions, symbols, and rename tools. | Package snapshot |
| [MCP Panel](https://github.com/DSH-Extensions-list/dsh-mcp-panel) | MCP server management, connection diagnostics, tool inventory, and trial calls. | Package snapshot |

### Also in our setup

These projects are installed locally but are **not published as organization packages**. The links below go to their upstream projects; upstream downloads do not include our local changes.

| Project | What we use it for |
| --- | --- |
| [PPT Flashmade / PPT Fusion](https://github.com/Bingtang1019/dsh-ppt-fusion) | A presentation workflow combining themes, editable DrawingML export, slide previews, and rendered review. Our installed edition includes English workflow adaptations. |
| [Task Orchestrator](https://github.com/hasan-aghayev/dsh-task-orchestrator) | Plan-driven delegation to isolated workers, dependency scheduling, and review. Our installed edition includes local changes to orchestration and model settings. |

## Installation

**Choose an extension, then follow its repository's installation instructions.** Requirements vary by package and DSH version.

- **Source packages:** use the repository's documented checkout or GitHub installation path. Build first if that project requires it.
- **Package snapshots:** download the `.tgz` archive and checksum from that repository's **Releases** page. These preserve the captured edition; installing the upstream npm package can give you different code or localization.
- **Subscriptions:** install the original npm distribution. Its repository here is an installation reference, not an installable mirror.

For a downloaded package, the usual profile-specific command is:

```sh
dsh plugin --profile desktop add /absolute/path/to/extension.tgz
```

Use `web` or your own profile name as appropriate, and use the CLI belonging to your DSH installation. Follow the extension's restart and activation instructions after installing.

## About this collection

**Source** repositories contain development code. **Source forks** retain the upstream project and our adaptations. **Package snapshots** preserve a particular installed package, which may include built JavaScript without the full development source. Their `DISTRIBUTION.md` and `INSTALLED-PACKAGE.json` describe provenance and captured files.

Each project keeps its own license and attribution. This is an independently maintained collection; inclusion does not imply endorsement by DeepSeek or upstream authors. Compatibility and verification details belong in each extension's README.

The catalog was reconciled with the desktop profile on **1 November 2026**. It lists the public extensions currently in that setup. Historical repositories may remain in the organization without appearing here.

Found a problem? Open an issue in the relevant extension repository. For catalog corrections, [open an issue here](https://github.com/DSH-Extensions-list/.github/issues/new).
