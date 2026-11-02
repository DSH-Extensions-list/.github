<div align="center">

# DSH Extensions

**The extensions I use with DeepSeek Harness.**

My extensions, English adaptations, and the packages I keep in my DSH setup.

[Explore the collection](#explore-the-collection) · [Installation](#installation) · [About this collection](#about-this-collection)

</div>

---

I use [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) for coding, presentations, research, and longer tasks. This is where I share the extensions I build, the English editions I adapt, and the community packages I use alongside them.

I'm [arzvaak](https://github.com/arzvaak). Each entry explains what I use it for and where to get it. Community projects keep their original credits and licenses.

## Start here

| I want to… | Start with |
| --- | --- |
| Keep the coordinator available while coding workers run | [DSH Conductor](https://github.com/DSH-Extensions-list/dsh-conductor) — per-task model selection, queued native and official Muse CLI workers, worker controls, and independent review. |
| Create and edit a presentation | [Claude Slides — my English edition](https://github.com/DSH-Extensions-list/baoyu-design-english#claude-slides) — a local slide editor with direct editing, comments, and PDF, HTML, or PowerPoint export. |
| Design a website or app screen | [Claude Design — my English edition](https://github.com/DSH-Extensions-list/baoyu-design-english#claude-design) — editable artboards for responsive layouts and interactive prototypes. |
| Build a data-backed dashboard | [Claude Dashboard — my English edition](https://github.com/DSH-Extensions-list/baoyu-design-english#claude-dashboard) — charts, numbers, and tables over data files, with source attribution. |
| Show charts and diagrams in an answer | [DSH Visuals](https://github.com/DSH-Extensions-list/dsh-visuals) — inline charts, Mermaid diagrams, editable previews, and SVG export. |
| Connect BharatCode or another model endpoint | [Provider Hub](https://github.com/DSH-Extensions-list/dsh-provider-hub) — provider setup and model discovery, with subscription sign-in through the subscriptions plugin. |
| Schedule and track background work | [Task Board](https://github.com/DSH-Extensions-list/dsh-client-ui-task-board) — Kanban tasks, scheduled runs, and execution history. |
| Understand context usage and costs | [Context](https://github.com/DSH-Extensions-list/dsh-context) for context inspection; [Cost Meter](https://github.com/DSH-Extensions-list/bharatcode-cost-meter) for usage and cost tracking. |

## Explore the collection

### Presentations, design, and visuals

| Extension | What it adds | Distribution |
| --- | --- | --- |
| [Claude Slides — English edition](https://github.com/DSH-Extensions-list/baoyu-design-english#claude-slides) | My default presentation workflow: editable slide decks, a local editor, comments, history, and PDF/HTML/PowerPoint export. | Adapted source + release package |
| [Claude Design — English edition](https://github.com/DSH-Extensions-list/baoyu-design-english#claude-design) | Website and app-screen designs on editable canvases with multiple artboards, responsive layouts, and interactive controls. | Adapted source + release package |
| [Claude Design System — English edition](https://github.com/DSH-Extensions-list/baoyu-design-english#claude-design-system) | Shared colors, typography, tokens, components, assets, and a browsable brand book. | Adapted source + release package |
| [Claude Dashboard — English edition](https://github.com/DSH-Extensions-list/baoyu-design-english#claude-dashboard) | Data-backed charts, numbers, and tables over CSV/TSV/JSON files, with a Sources panel. | Adapted source + release package |
| [DSH Visuals](https://github.com/DSH-Extensions-list/dsh-visuals) | Charts, flowcharts, timelines, and Mermaid diagrams rendered inline, with source editing and SVG export. | Source + release package |

The four baoyu-design editions share an **Artifacts** sidebar and local editor/comment workflows. I keep their interfaces, instructions, validator messages, and generated-content defaults in English, including under Chinese browser settings. Download my English packages from the [suite’s Releases page](https://github.com/DSH-Extensions-list/baoyu-design-english/releases/latest); upstream npm downloads do not include these changes. The suite retains upstream authorship and mixed licensing, described in its repository.

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
| [Conductor](https://github.com/DSH-Extensions-list/dsh-conductor) | Discover models, choose one per task, queue native and official Muse CLI workers, and retain reviewed results with status and cancellation. | Adapted source + release package |
| [LSP Actions](https://github.com/DSH-Extensions-list/dsh-lsp-actions) | Language-server diagnostics, formatting, code actions, symbols, and rename tools. | Package snapshot |
| [MCP Panel](https://github.com/DSH-Extensions-list/dsh-mcp-panel) | MCP server management, connection diagnostics, tool inventory, and trial calls. | Package snapshot |

### Also in my setup

Conductor is derived from the project below. The maintained fork and its verification notes are linked above; upstream keeps its original credit and license.

| Project | What I use it for |
| --- | --- |
| [Task Orchestrator](https://github.com/hasan-aghayev/dsh-task-orchestrator) | Plan-driven delegation, dependency scheduling and review; the upstream foundation for Conductor. |

## Installation

**Choose an extension, then follow its repository's installation instructions.** Requirements vary by package and DSH version.

- **Source packages:** use the repository's documented checkout or GitHub installation path. Build first if that project requires it.
- **Package snapshots:** download the `.tgz` archive and checksum from that repository's **Releases** page. These preserve the captured edition; installing the upstream npm package can give you different code or localization.
- **Subscriptions:** install the original npm distribution. Its repository here is an installation reference, not an installable mirror.

**Desktop:** open **Plugins → Add plugin**, enter the full path to the downloaded `.tgz` file, install it, and enable it. My desktop build reserves its profile for the app’s Plugins page.

For a CLI profile such as `web`:

```sh
dsh plugin --profile web add /absolute/path/to/extension.tgz
```

Use your own CLI profile name as appropriate and the CLI belonging to your DSH installation. Follow the extension’s reload/restart instructions, then start a new session to receive newly installed skills.

## About this collection

**Source** repositories contain development code. **Source forks** and **adapted source** retain the upstream project and my changes. **Package snapshots** preserve a particular installed package, which may include built JavaScript without the full development source. Their `DISTRIBUTION.md` and `INSTALLED-PACKAGE.json` describe provenance and captured files.

Each project keeps its own license and attribution. This is an independently maintained collection; inclusion does not imply endorsement by DeepSeek or upstream authors. Compatibility and verification details belong in each extension's README.

I updated the presentation and design entries against my desktop profile on **2 November 2026**; the rest of the collection was last reconciled on **1 November 2026**. The baoyu-design suite replaces PPT Flashmade and Deckforge in my setup. Their repositories remain available as history. Installation state varies by machine.

Found a problem? Open an issue in the relevant extension repository. If I missed something in this list, [open an issue here](https://github.com/DSH-Extensions-list/.github/issues/new).
