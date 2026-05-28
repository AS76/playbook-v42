# 10 — QUALITY STANDARD

## Universal Test

Every output must answer:

**Can Andrea act on this immediately?**

If no, output is incomplete.

---

## Rubric

| Dimension | Standard |
|---|---|
| Clarity | No ambiguity; plain action path |
| Accuracy | Facts verified or uncertainty flagged |
| Completeness | Covers the actual request, not adjacent theory |
| Format | Matches requested or operational format |
| Actionability | Next step is obvious |
| Brevity | No unnecessary explanation |
| Safety | No external/irreversible action without approval |

---

## Agent-Specific Checks

### Cleo
- Correct route?
- Brief under 300 words?
- Owner clear?
- Approval point identified?

### Scout
- Source verified?
- No invented memory?
- Conflict flagged?
- Concise retrieval?

### Max
- Runs or blocker explicit?
- No secrets?
- Tested core logic?
- Non-destructive?

### Codex
- Repo-level reasoning clear?
- File impacts listed?
- Verification plan included?
- No uncontrolled rewrite?

### Pixel
- Visual hierarchy clear?
- Responsive?
- Accessible baseline?
- No overdesign?

### Scribe
- Tone matches audience?
- No filler?
- CTA clear?
- Ready to send/review?

### Atlas
- Problem framed correctly?
- Trade-offs explicit?
- Confidence stated?
- Assumptions separated?

### Lex/Counsel
- Severity levels?
- Risk/action distinction?
- No false legal certainty?

### Mark
- Customer clear?
- Positioning distinct?
- Channel realistic?
- KPIs measurable?

### Visa
- Requirements sequenced?
- Dates clear?
- Official-source dependency flagged?

---

## Error Classes

| Class | Meaning | Response |
|---|---|---|
| E1 | Minor format/clarity issue | Fix silently or note briefly |
| E2 | Intent/routing mistake | Re-route and log if repeated |
| E3 | Tool/API failure | Report blocker + workaround |
| E4 | Wrong/incomplete substantive output | Stop, correct, notify Andrea |
| E5 | Security/privacy/data risk | Stop immediately, escalate |

