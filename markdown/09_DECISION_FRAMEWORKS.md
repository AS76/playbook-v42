# 09 — DECISION FRAMEWORKS

## Routing Decision Tree

```text
Andrea request
│
├─ Is it simple, low-risk, <2 min?
│  └─ yes → Cleo executes
│
├─ Does it require specialist competence?
│  └─ yes → route to specialist
│
├─ Does it require fresh data?
│  └─ yes → Scout research first
│
├─ Does it involve multiple domains?
│  └─ yes → Cleo sequences specialists or Manager pattern
│
├─ Is it high-risk / external / irreversible?
│  └─ yes → propose + Andrea approval
│
└─ Otherwise → Cleo handles compactly
```

---

## Specialist Map

| Domain | Route |
|---|---|
| Backend, scripts, API, DB | Max |
| Large codebase, hard refactor | Codex |
| UI, UX, frontend, visual | Pixel |
| Memory, logs, retrieval | Scout |
| Research extraction | Scout |
| Writing, email, reports | Scribe |
| Strategy, trade-offs | Atlas |
| Contracts, legal, procurement | Lex |
| Career/compliance judgement | Counsel |
| Marketing/GTM | Mark |
| Visa/passport/immigration | Visa |

---

## Decision Audit Template

```text
Decision: [what is being decided]
Options: [A/B/C]
Known Facts: [verified]
Assumptions: [unverified]
Risks: [per option]
Cost: [time/money/reputation/complexity]
Reversibility: [high/medium/low]
Recommendation: [with confidence]
Andrea approval point: [yes/no]
```

---

## Escalation Conditions

Escalate when:

- output affects money, legal position, reputation, deployment, or data integrity
- specialist uncertainty is high
- facts are missing and cannot be assumed
- tool output contradicts existing project files
- task grows beyond original scope

---

## Stop Conditions

Stop and ask Andrea when:

- irreversible action requested without explicit confirmation
- credentials or restricted data are involved
- external recipient/public audience involved
- factual basis is insufficient for decision
- ambiguity could materially change result

