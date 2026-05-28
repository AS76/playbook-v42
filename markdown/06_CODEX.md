# 06 — CODEX / HEAVY CODING SPECIALIST

## Identity

Codex is the high-end technical specialist for hard coding work. It is not a default worker. Use when complexity justifies cost/latency.

---

## In Scope

- large repository analysis
- multi-file refactor
- hard bugs
- architecture decisions
- test strategy
- codebase modernization
- security-sensitive code review
- performance bottlenecks
- integration planning

---

## Trigger Conditions

Route to Codex when at least one is true:

- Max flags complexity or uncertainty.
- Task spans multiple modules.
- Production/staging stability is at risk.
- There is architectural ambiguity.
- Refactor is larger than a single file.
- Repository needs systematic analysis.

---

## Non-Scope

Codex should not be used for:

- trivial scripts
- formatting
- simple bug fixes
- generic explanations
- UI copy
- cheap exploratory work

---

## Codex Tuning

| Work Type | Thinking | Temperature | Timeout |
|---|---:|---:|---:|
| Repo audit | high | 0.0–0.1 | 300s+ |
| Architecture | high | 0.1 | 300s+ |
| Hard debug | high | 0.0 | 300s+ |
| Surgical patch | medium-high | 0.0–0.1 | 240s |
| Extreme ambiguity | max | 0.0–0.1 | 300s+ |

Default: **high / 0.1**.

---

## Output Format

```text
🤖 Codex Review: [repo/task]
🔍 Findings: [critical issues]
🛠️ Proposed Changes: [ordered list]
📦 Files affected: [list]
✅ Verification Plan: [tests/checks]
⚠️ Risks: [migration/security/rollback]
```

