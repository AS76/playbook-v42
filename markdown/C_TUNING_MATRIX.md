# C — TUNING MATRIX

Model names are excluded by design. This file defines runtime behaviour only.

---

## Thinking Levels

| Level | Use |
|---|---|
| low | routing, retrieval, formatting, simple operations |
| medium | normal coding, writing, UI, marketing, operational analysis |
| medium-high | policy/admin workflows, nuanced UX, quick strategic analysis |
| high | legal, architecture, strategy, complex debugging |
| max | rare: high-stakes ambiguity, critical decisions, major architecture |

Rule: never set all agents to high/max.

---

## Temperature Bands

| Band | Value | Use |
|---|---:|---|
| deterministic | 0.0–0.1 | legal, memory, code, facts |
| controlled | 0.15–0.25 | strategy, UX, synthesis |
| natural | 0.3–0.45 | writing, marketing, human tone |
| creative | 0.5–0.7 | visual concepts, campaign ideas |

Default maximum for operational work: **0.45**.

---

## Agent Defaults

| Agent | Thinking | Temperature | Timeout | Notes |
|---|---:|---:|---:|---|
| Cleo | low | 0.2 | 45–90s | medium only for synthesis |
| Scout | low | 0.0–0.1 | 60–120s | no invention |
| Max | medium | 0.1 | 120–240s | high for hard debug/architecture |
| Codex | high | 0.0–0.1 | 240–300s+ | max only for critical ambiguity |
| Pixel | medium | 0.25–0.35 | 120–240s | 0.5 for visual concepts |
| Scribe | medium | 0.35–0.45 | 90–180s | lower for formal docs |
| Atlas | high | 0.15–0.25 | 180–300s | max for critical decisions |
| Lex | high | 0.0–0.1 | 180–300s | deterministic |
| Counsel | high | 0.15–0.2 | 180–300s | judgement-sensitive |
| Mark | medium | 0.35–0.45 | 120–180s | 0.55 for campaign ideation |
| Visa | medium-high | 0.1 | 180–240s | current-source dependency |

---

## Token/Output Policy

| Agent | Default Output |
|---|---|
| Cleo | short |
| Scout | short/structured |
| Max | medium with files/run steps |
| Codex | medium-long technical plan |
| Pixel | medium with design rationale |
| Scribe | as requested |
| Atlas | structured memo |
| Lex/Counsel | structured risk report |
| Mark | compact GTM/positioning |
| Visa | checklist/timeline |

---

## Escalate Thinking When

- ambiguity affects outcome
- legal/security/reputation risk exists
- multi-step dependency exists
- previous attempt failed
- output will drive external action

## De-escalate Thinking When

- formatting only
- known template
- simple extraction
- routing only
- Andrea wants speed

