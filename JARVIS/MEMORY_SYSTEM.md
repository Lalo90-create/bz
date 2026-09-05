# JARVIS MEMORY SYSTEM

## Purpose
Give JARVIS a professional memory model without turning every conversation into one giant prompt.

## Memory layers

### 1. Working Memory
Temporary context for the task currently being executed.

Examples:
- current lead research;
- draft proposal;
- today’s priorities;
- temporary calculations;
- open questions.

Do not promote everything from Working Memory into long-term knowledge.

### 2. Project Memory
Durable knowledge related to one project or business engine.

Examples:
- BZ offers and positioning;
- Bazinga service models;
- successful outreach patterns;
- supplier categories;
- market learnings;
- recurring objections;
- validated processes.

Project Memory must remain separated by project unless information is genuinely shared.

### 3. Core Memory
Small, stable information that affects how JARVIS operates across projects.

Examples:
- business priorities;
- global operating scope;
- approval rules;
- communication preferences;
- strategic principles;
- long-term goals.

Core Memory should stay compact. Do not turn it into a database.

### 4. Private Business Memory
Confidential operational data.

Examples:
- real customer and club names;
- personal contact details;
- prices and margins;
- supplier terms;
- negotiations;
- unpublished proposals;
- contracts and sensitive documents.

This information must not be stored in the public repository.

## Promotion rule
Before saving something as durable knowledge, ask:
1. Will this be useful again?
2. Is it verified enough to reuse?
3. Which project owns it?
4. Is it sensitive?
5. Does an existing source already contain it?

If the answer to #1 is no, leave it temporary.

## Source-of-truth rule
Do not copy the same fact into multiple permanent locations.
Prefer a primary source and reference it from elsewhere.

## Confidence and freshness
Durable knowledge should be treated as one of:
- **Stable** — unlikely to change often;
- **Operational** — current process or decision;
- **Time-sensitive** — market, price, law, contact role, product availability or similar information that may require verification before reuse.

JARVIS must re-check time-sensitive information when it matters to a decision.

## Correction rule
When better information replaces old information:
- update the current source of truth;
- do not create a second competing version;
- rely on history for the old state.

## Learning rule
A completed task should enter durable memory only when it produces reusable value such as:
- a validated decision rule;
- a successful workflow;
- a useful market insight;
- a repeatable sales pattern;
- a proven prompt/template;
- a lesson from failure.

## User experience
Lautaro should not need to manage these layers manually during normal work.
JARVIS should identify what belongs where and keep the interface simple.
