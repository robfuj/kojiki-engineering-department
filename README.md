# 08 — Engineering / Technology

> Part of the **Hermes Organizational Decision System**. This repo is the
> **Engineering / Technology** line. It references the shared ontology in
> [`00-kojiki-ontology`](https://github.com/hermes-ios/00-kojiki-ontology) for the
> canonical schemas, taxonomy, decision-rights, and handoff standards.

## Primary question
> How do we build and operate the product?

## Purpose
Design, build, verify, scale, and operate reliable technical systems.

## Sub-functions
Software Engineering, Architecture, Platform, Infrastructure, DevOps, SRE, QA, Technical Program Management, Developer Experience

## Typical roles
CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE

## Inputs
Requirements, system state, constraints, architecture, security, reliability, cost.

## Outputs
Software, architecture, infrastructure, releases, tests, technical decisions.

## Learning focus
Architecture patterns; failure modes; reliability signals; technical debt; estimates; incident causes; verification effectiveness.

## Operating tree
```text
PROBLEM →
    CURRENT SYSTEM →
    CONSTRAINTS →
    ROOT CAUSE →
    OPTIONS →
    TRADEOFFS →
    ARCHITECTURE DECISION →
    IMPLEMENTATION →
    VERIFICATION →
    DEPLOYMENT →
    OBSERVATION →
    TECHNICAL LEARNING
```

## Decision states
```text
REPORTED → TRIAGED → ROOT-CAUSED → DESIGNED → IMPLEMENTING → VERIFYING → DEPLOYED → OBSERVING → CLOSED
```

## Decision outputs
`Implement · Refactor · Defer · Reject · Escalate · Monitor`

## Critical prompts (what this function thinks about)
> What problem are we actually solving?
> Is this really a technical problem?
> What is the current system state?
> What constraints exist?
> What are the root causes?
> What options exist?
> What are the tradeoffs?
> What are we optimizing?
> What are we sacrificing?
> What is the simplest viable solution?
> What could fail?
> How will we verify it?
> What evidence proves it works?
> What technical debt are we creating?
> What should be documented?
> What should be automated?
> What should the next engineer or agent know?

## Canonical record schema (docx Learning Ledger + Decision Object Fields)
Every decision in this line is recorded as:
- a **Decision Object** (docx S9) — see `schema/decision-object.json`
- a **Learning Ledger** entry (docx S7) — see `schema/learning-ledger.json`

and the agent must run the **Orientation Protocol** first (see `AGENT.md`).

## How to use
1. Read `AGENT.md` — the first-run Orientation Protocol.
2. Read `SCHEMA.md` — how this line maps to the universal schema.
3. Read `data/08-engineering.json` — the machine-readable spec.
4. See `data/example.json` — one fully worked decision (Decision Object + Ledger).
5. Use `decision-graph.mmd` — agent-decodable operating tree + state model.
6. Validate new records: `python3 tools/validate.py data/<name>.json`
