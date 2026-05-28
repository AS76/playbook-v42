# B — FORMAL ROUTING BINDINGS

## Cleo Direct Execution

Allowed only when:

- simple
- under 2 minutes
- reversible
- no specialist judgement
- no external action

Otherwise route.

---

## Mandatory Routing Table

| Trigger | Route | Thinking |
|---|---|---:|
| code, script, automation, API, DB | Max | medium |
| repo-wide, hard refactor, architecture | Codex | high |
| UI, frontend, UX, dashboard, visual | Pixel | medium |
| memory, remember, log, retrieve | Scout | low |
| research, find current info, compare sources | Scout | low-medium |
| write, draft, email, report, doc | Scribe | medium |
| strategy, scenario, decision, trade-off | Atlas | high |
| contract, legal, procurement, GDPR | Lex | high |
| career, mobility, sensitive risk | Counsel | high |
| marketing, GTM, positioning, offer | Mark | medium |
| visa, passport, immigration, permit | Visa | medium-high |

---

## Multi-Agent Bindings

| Task Type | Sequence |
|---|---|
| Webapp from data | Scout → Atlas → Pixel → Max/Codex |
| Backend + UI | Pixel defines UX → Max implements backend → Pixel integrates |
| Contract + business decision | Lex → Atlas/Counsel → Cleo synthesis |
| Market launch | Scout → Mark → Scribe → Pixel |
| Immigration + career impact | Visa → Counsel → Cleo synthesis |
| Repo rebuild | Codex → Max → Pixel if UI involved |

---

## Anti-Routing Rules

- Do not route writing to Atlas unless strategic memo.
- Do not route UI to Max unless pure implementation of approved design.
- Do not route legal to Atlas.
- Do not route memory to Cleo.
- Do not route trivial scripts to Codex.
- Do not route marketing copy directly to Mark when final text is needed; Mark frames, Scribe writes.

---

## Escalation Levels

| Level | Meaning |
|---|---|
| E0 | Cleo handles |
| E1 | Single specialist |
| E2 | Specialist + reviewer |
| E3 | Multi-agent sequence |
| E4 | Andrea approval required before action |

