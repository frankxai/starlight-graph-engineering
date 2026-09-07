# Graph classes taxonomy (do not collapse)

**Status:** estate law companion to [`CONTRACT.md`](./CONTRACT.md)  
**Source:** frankx.ai `docs/research/graph-engineering-source-ledger.md` + recommendation lock  
**Date:** 2026-09-04

Graph **engineering** is one discipline. Graph **classes** are different kinds of structure. Collapsing them produces fake platforms and broken SSOT claims.

## Classes (keep separated)

| Class | What it is | Typical home in Starlight | Not the same as |
|---|---|---|---|
| **Control / work** | Legal next steps, proof of done, supervisors, brakes, write-back | Layer **A** — SIS work-graph / loop-graph; agentic-ops execution ledger (projection) | Knowledge retrieval graphs; LangGraph-as-product |
| **Knowledge / retrieval** | What is true / findable; evidence-linked concepts, domains, skills | Layer **B** projections; **starlight-knowledge-tree** as knowledge *product*; GraphRAG only as document indexer (forbid as fleet memory) | Work-graph kernel; Queen state |
| **Code** | Callers, callees, impact, disposable repo indexes | Layer **C** — on-demand index of an *active* writer repo | Estate SSOT; private trees |
| **Agent / comms** | Who talks to whom, delegation, lanes, registered roles | Swarm / Hermes / agent-config skill routes; Foundry capability-graph (procedural) | Per-agent private topology as SSOT |
| **State / provenance / recovery** | Durable state, receipts, evidence URIs, resume, compensation | Work-graph events, evals receipts, Hermes Kanban persistence, Temporal-style durability where used | Model chat history as authority |
| **Ontology** | Typed vocabulary / schema for a knowledge product | knowledge-tree `ONTOLOGY.md`, schema packages | Workflow shapes; control plane |

## Hard separation rules

1. **Work ≠ knowledge.** SIS #102 layer A is not SKT. SKT does not become the agent execution kernel.
2. **Procedural ≠ semantic.** Foundry capability-graph and skills attach to routes; they are not layer B memory.
3. **Index ≠ SSOT.** Code indexes and GraphRAG batches are disposable or product-local; they do not own estate truth.
4. **Harness ≠ control plane.** Claude / Codex / Hermes / Grok / Antigravity / Cursor-GrokBot native primitives map *into* Starlight vocabulary; they do not each own a second Queen.
5. **UI ≠ kernel.** command-center `/graph` observes and edits presentations; law lives in contract + compiled loops.

## Mapping hint (layers × classes)

| | Control/work | Knowledge/retrieval | Code | Agent/comms | State/provenance | Ontology |
|---|---|---|---|---|---|---|
| **A** Workflow | ● primary | — | — | routes attach | events emit | — |
| **B** Memory | — | ● primary | — | — | provenance required | may constrain claims |
| **C** Code | — | — | ● primary | — | — | — |
| **D** World | steer only | projections | — | registered stewards | — | world schema local |

● = primary ownership. Empty cells are not invitations to invent a fifth product graph.
