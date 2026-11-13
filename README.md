# Dataset License Check — Claude plugin

Before you train on a dataset or ship a model, know whether you are allowed to — and what you owe. Dataset License Check reads the licence, the card and the provenance, and gives a clear verdict for your intended use.

_Supports compliance work; not legal advice._

## Install

**Claude app (web, desktop):** Plugins → add a marketplace from a GitHub repository → `xelA31B/dataset-license-check` → install **Dataset License Check**. Once approved in the Claude directory, search for **Dataset License Check** in Plugins.

**Claude Code (VS Code or terminal):**

```
/plugin marketplace add xelA31B/dataset-license-check
/plugin install dataset-license-check@dataset-license-check
```

## Commands

Type `/` in Claude and pick a command:

| Command | What it does |
|---|---|
| `/license-check [dataset or model] [intended use]` | Verdict ✅ / ⚠️ / ⛔ for commercial use, training and redistribution, with obligations and provenance risks |
| `/data-register [list, project or files]` | Register of datasets and models with licences, obligations, risks and review dates |

## Sources (free, public)

| Source | What it adds |
|---|---|
| Hugging Face Hub | Declared licence, card, base model, gated status, terms of use |
| SPDX License List, OSI, Creative Commons | Standard identifiers and official licence terms |
| Data Provenance Initiative | Published provenance and licence audits of popular datasets |
| EU AI Act Service Desk | Copyright-policy and training-content summary duties for general-purpose AI model providers |

## Where it works best

Works in all Claude apps. If a page cannot be opened directly, the plugin uses web search or asks you to open a link, and marks unchecked items. Claude Code gives the most complete checks.

## Reports

Concise, evidence-based reports in the language of your request, presented in the branded house style where supported. Schedule regular re-checks on your own frequency, day and time.

## License

MIT
