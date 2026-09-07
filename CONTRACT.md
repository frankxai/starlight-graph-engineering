# Starlight Graph Engineering Contract

**Schema:** `starlight.graph-engineering.v1`  
**Status:** published canon (this repo)  
**Date:** 2026-09-04  
**Owner:** Loop & Graph Engineer  
**Seed:** [SIS #102](https://github.com/frankxai/Starlight-Intelligence-System/pull/102) `docs/graph-engineering/CONTRACT.md` (`starlight.graph-engineering.v1` on that branch)  
**Not:** a new product, a per-agent brain, Q-Town, Agent Canvas, GraphRAG-as-memory, or a second Queen / control-plane scheduler

This contract names the four graphs the estate may keep. Everything else is a skill, a pack, a projection, or waste.

## Canonical homes

| Layer / concern | Canonical home |
|---|---|
| **A** Workflow / loop-graph | **SIS work-graph** + **this canon** ([SIS #102](https://github.com/frankxai/Starlight-Intelligence-System/pull/102)) |
| **B** Memory / truth | **SIS vaults** (private notes stay in `second-brain-vault`) |
| **C** Code | **On-demand product-repo indexes** (active writer repos only) |
| **D** World / drive | **starlight-world** (`docs/starlight-world/`) |
| **Knowledge product** | **[starlight-knowledge-tree](https://github.com/frankxai/starlight-knowledge-tree)** — **not a fifth control layer** |

**Explicit: no second control plane** ([agentic-ops #16](https://github.com/frankxai/agentic-ops/pull/16)). Supporting surfaces (adapters/UI/projections only): agentic-ops, command-center (#16/#8/#19), starlight-agent-config (#17), starlight-memory (#10 derived Graphiti only).

Foundry `capability-graph` is **procedural memory** (skills and registered agents). It is not layer B and not a fifth product graph.

## Layers

| ID | Name | Job | How many |
|---|---|---|---|
| **A** | Workflow / loop-graph | What is legal next, what proves done, who may not self-grade | A small library of reusable shapes. One compiled ledger per *campaign*, never per agent |
| **B** | Memory / truth | What is true, with provenance | **One** estate memory. No per-brand second brain |
| **C** | Code | Callers, callees, impact | Only repos with a live writer. Never the whole estate |
| **D** | World / drive | Where Frank steers | **One** |

Do **not** collapse these with the graph **classes** in [`TAXONOMY.md`](./TAXONOMY.md) (control/work vs knowledge/retrieval vs code vs agent/comms vs state/provenance vs ontology). Layers are the estate’s allowed *homes*; classes are the *kinds* of graph work.

## Hard forbids

1. **No graph per agent.** Hundreds of agents share A+B+D. Headcount is not topology.
2. **No graph per skill.** Skills are encoded expertise. They attach to a route. They are not graphs.
3. **No graph per domain by default.** A domain earns a typed subgraph only when the *product* is knowledge (canon index, research hub, knowledge-tree). It still projects into SIS. It never becomes a second SSOT.
4. **No GraphRAG as fleet memory.** Expensive batch document indexes are not Queen / estate state.
5. **No Graphiti as a second memory product.** Temporal facts may be a *derived* index only after the promotion rule. Auto-invalidation must not erase wisdom-vault entries.
6. **No Codegraph/Graphify as SSOT.** Code indexes are disposable. `private/` stays off-graph.
7. **No third orchestrator / second control plane.** Hermes/Queen remains schedule and lease authority. `longgraph-skill`, `agent-graph`, LangGraph adapters, and agentic-ops ledgers are pattern sources or execution projections — not a second cron.
8. **No private notes, secrets, transcripts, or `.env` values** in any public graph, loop ledger, or work-graph event body.
9. **No self-certified done.** Completion requires an independent supervisor or a deterministic gate. A model summary is not a fact.
10. **No live spawn from World.** District stewards stay `registered` until a Queen lane admits a writer.

## Promotion into layer B

A work-graph event, transcript, or index hit becomes semantic memory only when all of these hold:

1. the claim is stable (not task progress);
2. provenance points at an evidence URI;
3. privacy/retention is classified;
4. contradiction and staleness were evaluated;
5. a human or named policy authorized promotion;
6. the projection is reversible.

Otherwise it stays layer A (operational) or dies with the session.

## Workflow shapes (layer A)

Reuse these. Do not invent a new shape per brand.

| Shape | When |
|---|---|
| **Chain** | True data dependency (admit before execute) |
| **Diamond** | Independent fan-out, then merge (research, review, scans) |
| **Router** | Inspect facts, pick one legal path |
| **Converge** | Repeat until a stop rule outside the model (tests dry, K empty rounds) |

Every compiled loop must name: nodes, edges as data contracts, executor, **different** supervisor, proof gates, stop rule, human gates, and the work-graph event kinds it emits.

## Scale

- Skills scale by **activation**, not by cloning graphs.
- Brands scale by **packs** on the creator substrate, not by brand-to-brand graphs.
- Content scale is a **pipeline loop** (brief → draft → verifier → human publish). Corpus stays files + hashes.
- Software scale is **one writer per repo** plus a code index on that repo only.
- Fleet scale is **shared routes and facts**. Registered agents without a live process and a receipt are registry theater.

## Related

- Living index: [`INDEX.md`](./INDEX.md)
- Graph classes: [`TAXONOMY.md`](./TAXONOMY.md)
- Operational event kernel (SIS): `docs/architecture/operational-work-graph.md` on SIS
- Estate routing: `starlight-agent-config/core/estate/repo-estate.control.json`

Built on SIP — operational + doctrine tier. Seeded from SIS PR #102; adapted for estate-wide canon ownership without inventing conflicting law.
