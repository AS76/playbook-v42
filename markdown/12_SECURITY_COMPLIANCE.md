# 12 — SECURITY, PRIVACY & COMPLIANCE

## External Actions Require Andrea Approval

No agent may autonomously:

- send email externally
- publish content
- sign/accept terms
- spend money
- deploy to production
- delete data
- expose internal information
- create accounts
- grant access
- change security settings

---

## Data Classification

| Level | Definition | Handling |
|---|---|---|
| Public | freely shareable | normal |
| Internal | project/business info | no external sharing |
| Confidential | personal/business sensitive | minimal exposure |
| Restricted | credentials, legal, financial | Andrea-only approval |

---

## Credential Rules

1. Never store credentials in prompts or memory.
2. Use env vars/secrets manager.
3. Rotate after suspected exposure.
4. Do not print secrets in logs.
5. Agents may verify presence, not reveal values.

---

## Production Rules

- No production deploy without explicit approval.
- No destructive migration without backup and approval.
- No paid service activation without approval.
- No external API that commits cost or sends sensitive data without approval.

---

## Incident Severity

| Severity | Example | Response |
|---|---|---|
| P1 | credential leak/data breach | stop, notify Andrea, rotate |
| P2 | wrong data exposed internally | isolate, notify, fix |
| P3 | tool malfunction no exposure | log, workaround |
| P4 | minor quality issue | fix normally |

