# JARVIS OS

JARVIS OS is the public-safe operating system for coordinating BZ Consulting, Bazinga Lab, Career and the AI workflows around them.

Its purpose is to use AI to **generate revenue, create qualified opportunities, save time, improve decisions and build reusable capability**.

## How to use JARVIS
You do not need to understand the internal architecture.

Just write:

**`JARVIS, <what you want>`**

Examples:
- `JARVIS, oggi voglio migliorare te stesso.`
- `JARVIS, analizza BZ e dimmi cosa manca.`
- `JARVIS, trova la migliore priorità per oggi.`
- `JARVIS, fai ricerca su questo mercato.`
- `JARVIS, aiutami con una candidatura.`
- `JARVIS, spiegami cosa stai facendo mentre lavori.`

The internal router chooses the correct domain, memory, tools, quality level and workflow automatically.

## Global scope
JARVIS is designed to operate globally.

Default expansion ladder:
**Mazarrón / Cartagena / Murcia → Spain → Europe → international markets.**

This is an execution sequence, not a limitation. Local proximity is used as an advantage, while stronger opportunities in other markets can take priority whenever their ROI, access or strategic value is higher.

## Architecture

### Control Layer
The user-interface and orchestration layer. It converts normal language into intent routing, task planning, context selection, tool selection, risk handling, execution and self-improvement.

Canonical source: [`JARVIS/CONTROL_LAYER.md`](JARVIS/CONTROL_LAYER.md)

### BZ Consulting
Agrotech, greenhouses, hydroponics, LED, climate control, IoT, automation, sourcing, consulting, implementation and partnerships.

### Bazinga Lab
CSC/club and lawful cannabis-sector operators: audits, staff/budtender training, menu/communication systems, events/workshops where lawful, quality/process improvement, CRM/technology support and partnerships.

### Career
Job search, CV, LinkedIn, applications, interviews, professional positioning and income/stability improvement.

### Central Money Engine
There is only one scoring system for economic opportunities: `JARVIS/MONEY_ENGINE.md`.

Business engines add sector context but do not maintain duplicate scoring systems.

## Core system
Read these only if you want to understand how JARVIS works internally:

1. [BOOT](JARVIS/BOOT.md) — identity, mission and user interface
2. [CONTROL LAYER](JARVIS/CONTROL_LAYER.md) — routing, planning and orchestration
3. [CORE](JARVIS/CORE.md) — operating principles and governance
4. [OPERATING MAP](JARVIS/OPERATING_MAP.md) — how the pieces fit together
5. [MEMORY SYSTEM](JARVIS/MEMORY_SYSTEM.md) — what JARVIS remembers and where
6. [PERMISSIONS](JARVIS/PERMISSIONS.md) — what JARVIS may do autonomously
7. [QUALITY SYSTEM](JARVIS/QUALITY_SYSTEM.md) — verification and definition-of-done rules
8. [MONEY ENGINE](JARVIS/MONEY_ENGINE.md) — how economic opportunities are prioritized
9. [SALES ENGINE](JARVIS/SALES_ENGINE.md) — how leads become revenue
10. [LEARNING SYSTEM](JARVIS/LEARNING_SYSTEM.md) — how work becomes reusable capability
11. [SCORECARD](JARVIS/SCORECARD.md) — how value and ROI are measured

## Business engines
- [BZ Consulting](BZ/README.md)
- [Bazinga Lab](BAZINGA/README.md)

## Optional shortcuts
You do not need to memorize these. They are only faster ways to route a mission:

- **JARVIS START** — choose the best current priority
- **JARVIS SYSTEM CHECK** — audit JARVIS itself
- **JARVIS MONEY MODE** — prioritize revenue/ROI
- **JARVIS BZ MODE** — focus on BZ Consulting
- **JARVIS BAZINGA MODE** — focus on Bazinga Lab
- **JARVIS RESEARCH MODE** — evidence-heavy research
- **JARVIS BUILD MODE** — build or improve a system
- **JARVIS CEO MODE** — strategy and prioritization
- **JARVIS TEACH ME** — explain the AI method while working

## Clean-system rules
1. **One source of truth.** Do not duplicate rules or scoring systems.
2. **No visible version clutter.** Do not create `v1`, `v1.1`, `final`, `final2`, etc. GitHub history stores previous versions.
3. **Delete obsolete material.** Do not keep stale copies just in case.
4. **Simple interface, strong engine.** Lautaro should not need technical knowledge to operate the system.
5. **Results over complexity.** Add a tool, file or automation only when it creates measurable value.
6. **Human approval for important external actions.** Detailed authority rules live in `JARVIS/PERMISSIONS.md`.
7. **Risk-based quality.** Detailed verification rules live in `JARVIS/QUALITY_SYSTEM.md`.
8. **Memory with discipline.** Durable knowledge follows `JARVIS/MEMORY_SYSTEM.md` rather than being copied everywhere.
9. **Routing before execution.** Substantial tasks pass through `JARVIS/CONTROL_LAYER.md`.

## Philosophy
**Build → Use → Measure → Improve**

Every meaningful JARVIS session should produce at least one of:
- revenue;
- qualified opportunity;
- time saved;
- reusable knowledge;
- reusable asset;
- improved process;
- better decision.

## Public / private boundary
This repository is public-safe.

Do not store here:
- personal data;
- passwords or credentials;
- client/member private data;
- confidential prices or margins;
- supplier terms;
- unpublished proposals;
- negotiation notes;
- sensitive legal or business documents.

Real leads, contacts, prices, negotiations and private business knowledge belong in the private JARVIS layer.

## Primary rule
**Complexity belongs inside JARVIS, not in Lautaro's interface.**
