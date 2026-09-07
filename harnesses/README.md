# Harness matrix — native primitives → Starlight vocabulary

**Status:** v0 matrix (filled from frankx.ai graph-engineering field posts via `gh api`, 2026-09-04)  
**Law:** harnesses are **nodes / workers / projections**. They are **not** a second control plane (agentic-ops #16, CONTRACT forbid #7).  
**Owner:** Loop & Graph Engineer

Starlight vocabulary used below:

| Term | Meaning |
|---|---|
| **Layer A** | Workflow / loop-graph — legal next, proof, supervisor |
| **Layer B** | Memory / truth  promoted claims only |
| **Layer C** | Code index — disposable, writer-repo only |
| **Layer D** | World / steer |
| **Shape** | Chain / Diamond / Router / Converge |
| **Brake** | turns, cost, empty rounds, silence list |
| **Gate** | deterministic or independent supervisor; no self-certified done |

## Matrix

| Harness | frankx.ai post | Native primitives (vendor) | Maps to Starlight | Must not become |
|---|---|---|---|---|
| **Claude** (Claude Code) | [Claude Agent Engineering: Loops, Workflows and Graphs](https://frankx.ai/blog/graph-engineering-claude-code) · `graph-engineering-claude-code.mdx` | Dynamic workflows, subagents, Skills, agent teams, hooks, MCP | Worker brain; dynamic branches  **Router/Diamond**; Skills → route procedures (not graphs); external state + deterministic controls → **Layer A** brakes/gates | Official “Claude graph engineering” doctrine; durable authority inside the model session |
| **Codex** (OpenAI) | [Graph Engineering with OpenAI Codex: Skills and Delivery](https://frankx.ai/blog/graph-engineering-openai-codex) · `graph-engineering-openai-codex.mdx` | Subagents, worktrees, Skills, threads, Codex SDK / App Server, `AGENTS.md` | Coding / delivery **node**; subagents → separable Diamond arms; Skills → node procedures; merge/release → **gated** policy nodes outside Codex | Silent owner of ship policy; estate control plane |
| **Hermes** | [Graph Engineering with Hermes Agent: Durable Worker Graphs](https://frankx.ai/blog/graph-engineering-hermes-agent) · `graph-engineering-hermes-agent.mdx` | Kanban tasks + dependency edges (SQLite), worker lanes/profiles, review/retry, machine-readable evidence | Durable **worker graph** projection of Layer A; dependencies → edges; lifecycle states → progress; evidence → receipts | Temporal-style event replay SSOT; second Queen/cron (Hermes/Queen remains schedule & lease authority per CONTRACT) |
| **Grok** (Grok Build / xAI) | [Graph Engineering with Grok Build: Parallel Coding Graphs](https://frankx.ai/blog/graph-engineering-grok-build) · `graph-engineering-grok-build.mdx` | Terminal coding harness, checkpoints, headless execution, ACP, isolated workspaces | Bounded parallel **coding nodes**; isolation → Diamond fan-out; evidence gates + release → external Layer A | General workflow graph; durable replay engine; core workflow authority |
| **Antigravity** (+ Google ADK 2.0) | [Graph Engineering with Google Antigravity and ADK 2.0](https://frankx.ai/blog/graph-engineering-antigravity-adk) · `graph-engineering-antigravity-adk.mdx` | Antigravity: coding-agent SDK/loop (bundled runtime). ADK 2.0: validated nodes/edges, routing, fan-out, loops, interruption. Temporal: durable history/timers | Antigravity → coding **node** only; ADK graph semantics → comparable to Layer A shapes; Temporal → state/provenance/recovery class | Treating Antigravity ≡ ADK ≡ Temporal; Antigravity as estate control plane |
| **Cursor-GrokBot** | TODO — no dedicated `graph-engineering-cursor*.mdx` in frankx.ai blog set as of this fetch | Cursor agent tools, cloud agents, ACP-adjacent IDE loops, multi-model workers | Treat as **IDE/operator harness**: edits and proposals land as Layer A nodes with independent gates; GrokBot executor stays non-authority | Second control plane; silent merge authority; per-bot private SSOT graph |

## Flagship doctrine (all harnesses)

- [Graph Engineering: AI Architect’s Guide to Reliable Agents](https://frankx.ai/blog/graph-engineering-ai-agents) · `graph-engineering-ai-agents.mdx`  
  Production unit = versioned node/edge contracts that can be tested, observed, resumed, governed. Model may propose; code/policy/human authorizes consequential transitions.

  ## TODO / gaps

  - [ ] Per-harness deep pages under `harnesses/<name>.md` with exact primitive → event-kind tables from SIS work-graph schemas once #102 merges.
  - [ ] Cursor-GrokBot field note (dedicated post or internal ops page) — currently stubbed.
  - [ ] Wire command-center ACP harness control (#19) rows to this matrix after Suite lands.
  - [ ] Confirm Hermes lease/schedule wording against live Queen docs on merge of agentic-ops #16.
  
