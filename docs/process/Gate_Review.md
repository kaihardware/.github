# Gate Review v1.0

Gate Review is a short decision meeting and a durable record. It exists to answer: **Are we ready for the next kind of work?**

## Standard Record

- Product / revision:
- Current Gate:
- Proposed next Gate:
- Date:
- Accountable owner:
- Reviewers:
- Decision: **Advance / Rework / Hold / Stop**
- Conditions and review trigger:
- Evidence links:
- Risks accepted or rejected:
- Dissent / unresolved questions:

## Review by Gate

| Gate | Review focus | Required evidence | Approval |
| --- | --- | --- | --- |
| Idea → Charter | Problem relevance, KAI fit, owner, learning value | Problem hypothesis and known context | Product Owner |
| Charter → KDL Review | User, problem, vision, scope, non-goals, success, stop conditions | Frozen Charter draft | Product Owner |
| KDL Review → Research | Purpose, preservation, desirability, originality, reversibility, serviceability | KDL alignment and tensions | Brand + Product |
| Research → ADR | Question coverage, evidence quality, limitations, blockers, constraints and decision candidates | Research DoD and review status | Research + Engineering |
| ADR → DoR Review | Architecture boundary, interfaces, consequences, deferred choices | Required ADRs | Engineering + Product |
| DoR Review → CAD | Entire CAD readiness checklist; P0 blockers; prototype questions | Completed DoR and linked evidence | Engineering + Product |
| CAD → Prototype | Constraint compliance, interfaces, risks, reproducible build package | CAD DoD | Engineering |
| Prototype → Validation / Iteration | Question answered, evidence quality, anomalies, next decision | Prototype DoD | Product + Engineering |
| Validation → Design Freeze | User outcome, verification, deviations, risks, claims, manufacturing/service readiness | Requirement-linked validation evidence | Product + Engineering + Quality |
| Design Freeze → Release | Exact configuration, change control, legal/brand claims, production/support/containment | Frozen package and release checklist | Release Owner |

## Review Questions

Every Gate asks:

1. What decision are we making now?
2. What evidence supports it?
3. What remains unknown, and why is it acceptable—or blocking?
4. What changed since the last Gate?
5. Which KDL principles and constraints are affected?
6. What could harm users, the Trusted Core, KAI's credibility, or future serviceability?
7. Who owns the next action and review trigger?

## Outcomes

- **Advance:** Evidence supports the next Gate.
- **Rework:** Specific evidence or artifact must be corrected before review.
- **Hold:** External dependency, risk, or timing blocks a responsible decision.
- **Stop:** Evidence no longer supports the product direction.

No Gate is passed by majority vote, document count, schedule pressure, or AI recommendation. The accountable human owner records the decision and its conditions.
