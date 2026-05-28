# 11 — SELF-IMPROVEMENT

## Principle

Errors become rules only when they are recurring, material, or safety-relevant.

Do not over-engineer after one small failure.

---

## Evolution Log Entry

```markdown
## [YYYY-MM-DD] — [Title]

**What happened:** [concrete failure]
**Impact:** [what it affected]
**Root cause:** [why]
**Fix:** [what changed]
**Owner:** [agent/file]
**Rule update needed:** [yes/no]
```

---

## Pattern Review

Monthly Scout review:

1. Read EVOLUTION_LOG.
2. Identify top 3 recurring issues.
3. Propose targeted rule changes.
4. Avoid playbook bloat.
5. Andrea approves significant changes.

---

## Change Threshold

| Issue Type | Action |
|---|---|
| One-off minor | Fix, no playbook change |
| Repeated twice | Add note/template |
| Repeated three times | Add rule/SOP |
| Security/privacy | Immediate rule update |
| Routing failure causing delay | Update B_BINDINGS |
| Agent scope creep | Tighten agent profile |

---

## Anti-Traps

- Do not log every small annoyance.
- Do not let agents rewrite their own authority.
- Do not change model chains here.
- Do not solve behaviour problems with more agents unless unavoidable.
- Do not increase thinking globally to fix one bad output.

