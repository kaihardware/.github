# KAI Engineering Process v1.0

- Version: **1.0**
- Scope: **All KAI products**
- Purpose: **Make the next safe step obvious**

This process is not a reporting system. It is a sequence of decisions that prevents KAI from moving forward with hidden uncertainty.

## Flow

**Idea → Project Charter → KDL Review → Research → ADR → Definition of Ready → CAD → Prototype → Validation → Design Freeze → Release**

A product may return to an earlier stage whenever evidence invalidates an assumption. Moving backward is learning, not failure.

## Stages

| Stage | Question | Minimum output | Exit |
| --- | --- | --- | --- |
| Idea | Is there a problem worth understanding? | Short problem hypothesis and owner | Approve Charter work, hold, or stop |
| Project Charter | What are we trying to improve—and not change? | Frozen Charter: user, problem, vision, scope, success, risks, open questions | Product owner approves the research boundary |
| KDL Review | Does this direction express KAI? | KDL alignment and documented tensions | Brand/Product owner approves or requests change |
| Research | What must be true before design? | Reviewed evidence, limitations, unknowns, constraint and decision candidates | Research DoD passes; blockers are owned or resolved |
| ADR | Which consequential choices constrain future work? | Accepted or explicitly deferred ADRs | Required architecture decisions exist |
| Definition of Ready | Is CAD now the right next action? | Completed DoR checklist and Gate Review record | Product and Engineering owners authorize CAD |
| CAD | Does the design satisfy approved intent and constraints? | Revisioned source, interfaces, assumptions, checks, review record | CAD DoD passes for prototype release |
| Prototype | What questions will the physical build answer? | As-built revision, BOM, assembly record, evidence, anomalies | Prototype DoD passes; next experiment/iteration is decided |
| Validation | Does the product work for intended users and conditions? | Requirement-linked verification and user validation | Deviations accepted or resolved; release direction supported |
| Design Freeze | Is this exact design controlled? | Frozen CAD/BOM/specs, approved deviations, manufacturing and support readiness | Change control begins; release candidate authorized |
| Release | Can KAI responsibly support what it ships? | Release record, claims evidence, traceability, support/containment plan | Named Release Owner approves |

## Gate Rules

- A document's existence does not pass a Gate; evidence and accountable review do.
- Fact, observation, assumption, decision, and unknown must remain distinguishable.
- Safety, legal, privacy, security, compatibility, and brand concerns can stop work at any stage.
- AI may organize, draft, compare, and critique. Humans approve product intent, risk, architecture, validation, freeze, and release.
- Every Gate ends with one outcome: **Advance, Rework, Hold, or Stop**.
- The decision, owner, evidence links, conditions, and review date are recorded.

## Ownership

- **Product Owner:** problem, scope, priority, user value, release intent.
- **Engineering Owner:** technical integrity, interfaces, evidence, readiness, configuration control.
- **Brand Owner:** KDL alignment and product claims.
- **Research/Verification Owner:** method, evidence quality, limitations, and result integrity.
- **Release Owner:** final risk acceptance, support, containment, and ship decision.

One person may hold several roles early on, but the responsibilities remain explicit.

## Project Mapping

GitHub Project uses two independent concepts:

- **Status:** Inbox, Ready, In progress, Review, Blocked, Done, Stopped.
- **Engineering Gate:** Idea, Charter, KDL Review, Research, ADR, DoR Review, CAD, Prototype, Validation, Design Freeze, Release.

Status describes work state. Engineering Gate describes product maturity. Neither replaces the reviewed artifacts in the repository.

## Related Standards

- KAI Design Language: https://github.com/kaihardware/brand/blob/main/KAI_Design_Language.md
- Definition of Ready: Definition_of_Ready.md
- Definition of Done: Definition_of_Done.md
- Gate Review: Gate_Review.md
