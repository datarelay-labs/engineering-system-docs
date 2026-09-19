# Data Relay Labs Engineering System Docs

Human-readable handbook for the Data Relay Labs Engineering System.

- Canonical engineering standard: https://github.com/datarelay-labs/engineering-system
- Handbook source: https://github.com/datarelay-labs/engineering-system-docs
- Intended site: https://engineering.datarelay.run

The canonical repository defines the rules consumed by AI agents, repositories, CI, and release workflows. This repository explains the system for humans: architecture, tools, automation, session continuity, knowledge management, remote development-server audit, adoption, and real-world lessons.

## Documentation map

- `index.mdx` — overview and system map
- `architecture.mdx` — responsibilities and authority model
- `workflow.mdx` — ChatGPT → Work Packet → Cursor → verification loop
- `tools.mdx` — ChatGPT, Cursor, GitHub, Desktop Commander, Athena
- `knowledge.mdx` — source-of-truth and decision-history model
- `session-continuity.mdx` — AI Work Packet and `/resume`
- `remote-audit.mdx` — direct development Linux host audit
- `mobile-remote-workflow.mdx` — Cursor CLI, tmux, phone SSH, and Telegram completion notifications
- `adoption.mdx` — minimal setup for new/existing repositories
- `evolution.mdx` — problems, trade-offs, and lessons learned

The site is configured for Mintlify through `docs.json` and provides English/Korean navigation with matching system diagrams.

This repository is intentionally derived documentation. If this handbook conflicts with the canonical Engineering System repository, the canonical repository wins.
