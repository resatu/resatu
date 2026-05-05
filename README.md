# Resat Ugur Ulu

I build local-first AI software: desktop runtimes, agent memory, reusable skills,
and workflows that leave receipts a human can audit.

Right now I am building [Graphyn](https://graphyn.xyz), a desktop app for turning
AI conversations into durable agents, project memory, and workflows you own.

[Website](https://graphyn.xyz) | [X](https://twitter.com/graphyn_) |
[LinkedIn](https://www.linkedin.com/in/resatugurulu) |
[Email](mailto:richard@graphyn.xyz)

## Current Focus

- Desktop AI runtime: panes, sessions, permissions, local state, and recovery.
- Agent memory: durable context, conversation isolation, and reusable knowledge.
- Skill systems: small `SKILL.md` packages with scripts, references, and assets.
- Operator workflows: planning, research, review, deployment, docs, and support.
- Product surfaces that make AI work inspectable instead of disposable.

## Public Work

| Repo | What it is |
| --- | --- |
| [letta-code](https://github.com/resatu/letta-code) | Memory-first coding agent experiments. |
| [gpui-mono](https://github.com/resatu/gpui-mono) | Graphyn design-system work for GPUI/Rust UI surfaces. |
| [chunkbench](https://github.com/resatu/chunkbench) | Benchmarks for finding the right chunking strategy for a codebase. |
| [kv-storage](https://github.com/resatu/kv-storage) | TypeScript LSM-tree key-value store with realtime visualization. |
| [awesome-cursor-prompts](https://github.com/resatu/awesome-cursor-prompts) | Prompt and workflow collection for AI-assisted development. |

## How I Work

I keep a living `.skills/` library for repeatable agent work. The useful pattern
is not a giant prompt; it is a small instruction file plus the scripts, examples,
and references needed to run the workflow again.

The same idea shows up in Graphyn: agents should remember what matters, expose
what they changed, keep work tied to a thread, and make handoff between humans
and models less fragile.

## Stack

`TypeScript` | `Rust` | `Go` | `Swift` | `Node.js` | `PostgreSQL` | `SQLite` |
`Tauri` | `Cloudflare` | `GitHub Actions`

Based in Istanbul. Building for people who want AI tools that compound instead
of forgetting everything after the tab closes.
