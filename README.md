# Human Function World Model (HFWM)

## A whole-person world model organized through human function

[中文](README.zh-CN.md) · [Framework paper](papers/hfwm-framework/HFWM_EN.md) · [Architecture](architecture/README.md) · [Capacity coordinate](capacity-coordinate/README.md) · [Functional Bridge](functional-bridge/README.md) · [References](references/README.md) · [Public boundary](PUBLIC_RELEASE_BOUNDARY.md) · [Rights](RIGHTS_AND_REUSE.md) · [Collaboration](COLLABORATION.md)

**Official name:** Human Function World Model  
**Official abbreviation:** HFWM  
**Author:** Lei Che  
**Affiliation:** MoveTips Technology (Beijing) Co., Ltd.  
**Correspondence:** dlehche@gmail.com  
**Semantic foundation:** [Unified Ontology of Human Function (UOHF)](https://github.com/dlehche/Unified-Ontology-Of-Human-Function)  
**Public publication/document license:** CC BY-NC 4.0 unless a specific record states otherwise

> **Human function is the body's capacity to be appropriately engaged to meet internal and external demands.**

> **Human function is the organizing coordinate of HFWM, not the boundary of the modeled world.**

---

## What HFWM models

HFWM continuously represents the **same whole person** across:

- internal and external tasks;
- Demand;
- required human-function capacities;
- current capacity;
- Actual Engagement Process;
- bodily structure and physiology;
- disease, injury, surgery, recovery and adaptation;
- manifestation, cost, boundary and reserve;
- evidence, uncertainty, hypotheses and judgment;
- governed action and responsibility routing;
- professional, caregiving and environmental coordination;
- feedback, reassessment and longitudinal change.

The operational reasoning chain is:

```text
INTERNAL_TASK / EXTERNAL_TASK
→ Demand
→ Required Human-Function Capacities
→ Current Capacity
→ Actual Engagement Process
→ Response / Manifestation / Cost / Boundary / Recovery
→ Evidence / Hypotheses / Uncertainty
→ Judgment
→ Governed Action / Responsibility Routing
→ Observed Change
→ Feedback / Reassessment
→ Longitudinal Update
```

The UOHF root definition remains prior to this operational chain. Task representations make Demand explicit; they do not replace Demand in the root definition.

---

## Historical provenance

The term **Human Function World Model (HFWM)** was publicly disclosed by the same author in **UOHF Definition 2.0** on 15 July 2026. That publication distinguished UOHF, the Individual Human Function Model, and HFWM, and described HFWM as adding time, action, transition, prediction, and memory write-back.

UOHF Definition 2.1 subsequently restored the full internal-and-external-demand root scope.

This repository is the dedicated public research home for HFWM as it grows beyond one manuscript.

A targeted public search completed in August 2026 did not identify an earlier independent dedicated framework with the same organizing scope across internal/external tasks, human-function capacity and engagement, medicine-function bidirectional reasoning, responsibility routing, and longitudinal whole-person update. This is a provisional bibliographic statement and should be revised if earlier equivalent work is identified.

---

## The 18 + 104 human-function coordinate

HFWM uses the public UOHF Human Function Capacity System as its governed functional coordinate.

Current public Version 1.0:

- **18 core human functional capacities**
- **104 specific human functional capacities**

HFWM does not create a second copy of the 104 definitions. UOHF remains the semantic authority.

See [`capacity-coordinate/README.md`](capacity-coordinate/README.md).

---

## Functional Bridge

HFWM also requires explanatory scientific knowledge connecting human-function capacities to anatomy, spatial organization, physiology, biological processes, cross-capacity organization, response, state, time, and change.

The **Functional Bridge** is a governed **knowledge-relation layer** for this purpose.

Functional Bridge is:

- not UOHF A14;
- not a second ontology;
- not a replacement for formal UOHF relations;
- not person-specific evidence;
- not a diagnosis, causal conclusion, or action prescription.

Public scientific reference sources can include:

- **Human Reference Atlas (HRA)** for anatomical/spatial reference;
- **NIH Whole Person Reference Physiome (WPP)** for multiorgan and multiscale physiological reference;
- other controlled scientific sources with explicit provenance and scope.

See [`functional-bridge/README.md`](functional-bridge/README.md).

---

## The whole person

“Whole person” does **not** mean that HFWM claims exhaustive simulation of every molecule, cell, biological variable, social variable, or future.

It means that the persistent modeled entity remains the **same person** across biological, physiological, medical, functional, behavioral, environmental, professional, and longitudinal contexts.

Disease, injury, infection, surgery, and endogenous change may **trigger internal tasks** such as defense, regulation, hemostasis, repair, recovery, and adaptation. They are not themselves silently converted into Task or Demand.

---

## Bidirectional medicine–human-function reasoning

HFWM connects medicine and human function bidirectionally without collapsing one into the other.

**Medicine → human function:** medical facts can constrain safety, physiology, capacity, engagement, recovery, task feasibility, and admissible action.

**Human function → medicine:** new or progressive functional change, unexplained deterioration, abnormal recovery, or failure of an existing functional explanation can generate a governed medical question or escalation need.

HFWM does not convert functional evidence into autonomous diagnosis.

See [`architecture/MEDICINE_FUNCTION_BIDIRECTIONAL.md`](architecture/MEDICINE_FUNCTION_BIDIRECTIONAL.md).

---

## Coordination around the same person

HFWM can represent changing responsibility and collaboration across:

- physician;
- nurse;
- physical therapist / physiotherapist;
- occupational therapist;
- speech-language pathologist / speech and language therapist;
- audiologist;
- dietitian;
- psychologist / psychotherapist / other qualified psychological professional;
- exercise and training professional;
- qualified massage/manual practitioner where legally appropriate;
- the person;
- family and caregivers;
- assistive technology;
- home, workplace, school, community, and environmental modification.

The same person remains the shared object. Professional roles retain distinct scope, authority, and evidence requirements.

See [`architecture/COORDINATION_TOPOLOGY.md`](architecture/COORDINATION_TOPOLOGY.md).

---

## Human-readable state projection

A Body Function Report is not the world model itself. It is a governed human-readable projection of the evidence-supported modeled state.

```text
Report_t = Projection(ModelState_t, Evidence_t, Audience, Authority)
```

Historical reports must remain replayable and must not be silently rewritten by later evidence.

See [`architecture/REPORT_PROJECTION.md`](architecture/REPORT_PROJECTION.md).

---

## Start here

| Resource | Purpose |
|---|---|
| [Framework paper](papers/hfwm-framework/HFWM_EN.md) | Complete English HFWM framework manuscript |
| [中文论文](papers/hfwm-framework/HFWM_ZH.md) | 中文完整对照稿 |
| [Architecture](architecture/README.md) | Public HFWM architecture |
| [Capacity coordinate](capacity-coordinate/README.md) | 18 core + 104 specific capacities |
| [Functional Bridge](functional-bridge/README.md) | Knowledge-relation role and boundaries |
| [Scientific references](references/README.md) | Canonical external and UOHF references |
| [Benchmarks](benchmarks/README.md) | Public evaluation direction |
| [Examples](examples/README.md) | Non-normative examples |
| [Governance](governance/README.md) | Authority and publication governance |
| [Public release boundary](PUBLIC_RELEASE_BOUNDARY.md) | What is intentionally public/private |
| [Versions](versions/README.md) | Public HFWM history |
| [Collaboration](COLLABORATION.md) | Research and institutional collaboration |

---

## Current scientific boundary

The current public HFWM framework formally specifies:

- typed whole-person state representation;
- internal/external task and Demand reasoning;
- capacity/engagement type separation;
- evidence, uncertainty, hypothesis, and judgment boundaries;
- governed next action and responsibility routing;
- feedback, reassessment, and history-preserving longitudinal update;
- human-readable state projection;
- integration with governed scientific knowledge sources.

HFWM does **not** currently claim:

- exhaustive whole-body simulation;
- calibrated prediction of every future human state;
- causal counterfactual simulation for arbitrary interventions;
- autonomous medical diagnosis;
- autonomous high-risk treatment selection;
- complete clinical outcome validation;
- release of the complete production reasoning system.

---

## Repository growth

This repository is designed to grow over time. Future public content may include dedicated papers, public typed schemas, benchmark sets, longitudinal state research, internal-task studies, coordination models, public Functional Bridge research, reproducible non-sensitive examples, interoperability mappings, and empirical validation.

Public research growth does not imply release of proprietary production implementation.

---

## Copyright and reuse

**Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.**

Public HFWM publication/document content is intended for **CC BY-NC 4.0** licensing unless a specific record states otherwise. Academic citation and non-commercial reuse are permitted under the applicable license. Commercial use of copyright-protected content requires separate permission where copyright permission is required.

See [`RIGHTS_AND_REUSE.md`](RIGHTS_AND_REUSE.md).
