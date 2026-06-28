# Definition of Ready — CAD

CAD begins only when design work is the best remaining way to reduce uncertainty. This checklist applies to every KAI product.

- Product:
- CAD scope / revision target:
- Review date:
- Product owner:
- Engineering owner:
- Decision: Advance / Rework / Hold / Stop

## Required Checklist

### Intent

- [ ] Project Charter is reviewed and frozen for this design cycle.
- [ ] Target user, problem, intended outcome, scope, and non-goals are explicit.
- [ ] KDL Review is complete; tensions or exceptions are documented.
- [ ] CAD has a defined question or outcome—not merely “start designing.”

### Evidence

- [ ] Required Research meets its Definition of Done or is explicitly Inconclusive with an owned blocker.
- [ ] Facts, assumptions, unknowns, and decisions are separated.
- [ ] Critical sources, specimens, revisions, methods, uncertainty, and limitations are traceable.
- [ ] No P0 research blocker remains hidden or unowned.

### Constraints and Decisions

- [ ] Must / Should / Could / Won't constraints are reviewed.
- [ ] Critical interfaces, datums, envelopes, keep-outs, loads, and safety boundaries are identified at the confidence needed for CAD.
- [ ] Required ADRs are Accepted or explicitly Deferred with conditions.
- [ ] Trusted Core and changeable design scope are defined.
- [ ] Reversibility, serviceability, daily carry, protection, and weight intent are addressed.

### Verification and Risk

- [ ] Each Must constraint has a proposed verification method.
- [ ] Prototype questions and success/failure criteria are defined before CAD.
- [ ] Safety, battery, legal/IP, privacy/security, compatibility, manufacturing, and supply risks have owners and next actions where relevant.
- [ ] Required tools, materials, specimens, reviewers, and prototype resources are realistically available.

### Control

- [ ] CAD owner, source-of-truth tool/version, units, coordinate system, naming, revision, and file structure are defined.
- [ ] Inputs and reference artifacts are licensed, permitted, and provenance-controlled.
- [ ] The Gate Review record links the Charter, KDL Review, Research, ADRs, constraints, risks, and Project item.

## DoR Decision

CAD is **Ready** only when every required item is checked or an explicit, accountable exception is recorded with risk, owner, evidence, and expiry/review trigger.

Unchecked convenience items do not block CAD. Unresolved P0 evidence, safety, trusted-core, or interface-control items do.
