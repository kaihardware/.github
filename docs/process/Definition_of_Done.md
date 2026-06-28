# Definition of Done v1.0

“Done” means the stage produced a reviewable decision—not that every uncertainty disappeared.

## Research Done

- [ ] The decision question, scope, exclusions, owner, and evidence-quality target are explicit.
- [ ] Specimens/sources, revisions, methods, tools, units, uncertainty, limitations, and provenance are traceable as applicable.
- [ ] Fact, observation, assumption, decision, and unknown are separated.
- [ ] Results answer the question, narrow it, or are explicitly Inconclusive.
- [ ] Contradictions and negative findings remain visible.
- [ ] Safety, privacy, confidentiality, licensing, and AI assistance are documented.
- [ ] Product impact is extracted: constraints, Requirement candidates, ADR candidates, risks, and follow-up work.
- [ ] A focused Pull Request is reviewed.
- [ ] Status is Accepted, Rework, or Inconclusive—not silently “complete.”

Research is not Done because notes exist or because no more searching feels useful.

## CAD Done — For Prototype Release

- [ ] CAD scope and linked Charter/KDL/Research/ADR/constraints are explicit.
- [ ] Editable source is revisioned; exports do not replace the source of truth.
- [ ] Units, coordinate system, datums, interfaces, keep-outs, dependencies, material/process assumptions, and critical dimensions are documented.
- [ ] Must constraints and trusted-core boundaries are checked.
- [ ] Assembly, fastening, service, reversibility, protection, and daily-carry implications are reviewed.
- [ ] Mass and structural decisions have stated reasons; no unsupported precision or simulation claim is used as proof.
- [ ] Known interferences, open questions, deviations, and risks are visible.
- [ ] Prototype build/export instructions and configuration are reproducible.
- [ ] Peer review is complete and the exact prototype revision is identified.

CAD Done authorizes a prototype. It does not mean Design Freeze or production readiness.

## Prototype Done

- [ ] The prototype's question and acceptance/failure criteria were defined before evaluation.
- [ ] As-built CAD revision, BOM, materials, process, settings, assembly steps, deviations, and specimen ID are recorded.
- [ ] Safety and stop-work checks were completed.
- [ ] Evidence links to the question and applicable constraints/requirements.
- [ ] Failures, anomalies, damage, user observations, and negative results are retained.
- [ ] Prototype evidence is not presented as production or validation evidence.
- [ ] The build can be reproduced or its irreproducibility is explained.
- [ ] Review selects the next outcome: iterate, additional research, validation, hold, or stop.
- [ ] A focused Pull Request records the durable result.

A prototype is Done when it answered a question well enough to decide the next step—not when it looks finished.
