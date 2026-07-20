# Module Descriptor - Software Architecture Foundations

**Code:** NB-SOCE-L3-SE-TT-02  ·  **Tier:** Pathway (SE)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NIBM_SOCE_SE_ModuleRecords_Y12 v2.3; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1

> **Items requiring confirmation at review:** (1) the learning-outcome set (canonical device: authored here from the record v2.3 stubs; ratified into the record set on confirmation); (2) assessment attributes and weightings at sign-off, including the no-examination stance stated in Section 5; (3) syllabus hour allocations, which carry the stage 1 trim (the styles catalogue and extended case-study depth are the recorded cut, recovered in Enterprise Application Development); (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-SE-TT-02 |
| Module title | Software Architecture Foundations |
| Scope / type | Pathway: CS(SE)  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB6034CEM Software Engineering 2 (architectural styles and quality-attribute reasoning) - claim VERIFIED at 3 credits: the NB6034 architecture supply is joint between this module (principle) and Enterprise Application Development (patterns in practice, unchanged at 4 credits); core styles and quality attributes retained. Feeds Enterprise Application Development, where architecture moves from principle to practice (standing obligation 4). |
| Prerequisites | Programming Concepts; co-runs with Software Engineering and Systems Analysis |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

The module builds architectural reasoning for the CS(SE) vertical: the vocabulary of software architecture, the recognised styles and their trade-offs, and the quality attributes against which structural decisions are judged. It is structure in principle - "what architectures, and why" - and it exists so that Enterprise Application Development in Year 2 can move directly to structure in practice, and so that the joint supply of architectural reasoning into the Level 6 software-engineering destination is secured from the principle side. The scope limit is honest and recorded: the stage 1 trim from 4 to 3 credits cost breadth of the styles catalogue and extended case-study depth, both recovered in the Year 2 applied treatment; quality-attribute reasoning and the core styles are untouched.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** architectural styles and patterns at the structural level; quality attributes (maintainability, scalability, performance); high-level structural design; the vocabulary of architecture. This is structure in principle - "what architectures, and why".
>
> **Does NOT cover:** applied enterprise construction and the implementation of design patterns (Enterprise Application Development - structure in practice); process and lifecycle (Software Engineering and Systems Analysis).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Explain common software architectural styles and the trade-offs between them | Understand (Bloom); K-SAM 1 |
| LO2 | Make initial judgments about quality attributes in structural design, developing arguments from basic architectural principles | Understand (Bloom); K-SAM 5 |
| LO3 | Produce and communicate a high-level architecture for a given problem | Apply (Bloom); K-SAM 2, 3 |

**LO provenance note (canonical device):** the set above is authored from the record v2.3 indicative stubs. The record's LO2 "reason about" is rendered in the Level 3 register as "make initial judgments ... developing arguments from basic principles" (Level 3 descriptor rows 2 and 5); "communicate" is added to LO3 to carry K-SAM 3 explicitly. No verb exceeds the Level 3 cognitive ladder; no K-SAM category 7 defence is required. On ratification the carrying register inherits this set verbatim; SLQF-04 for this module closes at that point.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Enterprise Application Development (Year 2) | "applied enterprise construction and the implementation of design patterns (Enterprise Application Development - structure in practice)"; the joint supply declaration on the Level 6 destination is principle here, patterns in practice there |
| Software Engineering and Systems Analysis | Co-runs; "process and lifecycle (Software Engineering and Systems Analysis)" - introductory design there stops where structural styles begin here |
| Programming Concepts | Prerequisite: program-level construction experience assumed before structure is abstracted |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | The role of architecture: what architecture is and is not; architectural vocabulary; components, connectors and views | 6 |
| U2 | Architectural styles I: layered, client-server, model-view-controller; strengths, costs and typical uses | 9 |
| U3 | Architectural styles II: event-driven, pipe-and-filter, service-oriented and microservice styles at survey level | 9 |
| U4 | Quality attributes: maintainability, scalability, performance; trade-off reasoning between attributes; how attributes drive structural choice | 12 |
| U5 | High-level structural design practice: documenting an architecture through views; from problem statement to candidate structure | 9 |
| U6 | Case study and evaluation basics: reading an existing architecture; presenting and defending a structural choice | 3 |
| | **Total lecture hours** | **48** |

Sessions run as 3-hour blocks (16 sessions). The stage 1 trim lands on U2-U3 catalogue breadth and U6 case depth by design; the recorded recovery route is the Year 2 applied treatment.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 48 |
| Tutorials | 12 |
| Practicals / Laboratory | 24 |
| In-class assignments | 9 |
| Demonstration | 3 |
| Self-guided study | 54 |
| **Total** | **150** |

## 5. Assessment

Components per the Assessment Component Taxonomy; weightings confirmed at specification sign-off.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Architecture design report: a high-level architecture for a supplied problem with documented styles reasoning and quality-attribute trade-offs | Individual; take-home; graded; oral vehicle: Viva-defence | LO2, LO3 | 70 |
| CW-I-Class | Supervised architecture-reasoning exercise under open-resource conditions | Individual; in-class; graded; oral vehicle: None | LO1, LO2 | 30 |

No examination is carried by design: the assessed capability is design-artefact reasoning, for which a written examination adds no coverage; assessment integrity is anchored by the mandatory Viva-defence on the design report and the supervised in-class component. Weights sum to 100. Reassessment is by failed component. Academic-integrity and generative-AI expectations follow School policy; the Viva-defence is the authorship check on the take-home report.

## 6. Resources, Staff and Governance

### Indicative Reading

- Bass, L., Clements, P. and Kazman, R., *Software Architecture in Practice*, 4th edition, Addison-Wesley.
- Richards, M. and Ford, N., *Fundamentals of Software Architecture: An Engineering Approach*, O'Reilly Media.
- Rozanski, N. and Woods, E., *Software Systems Architecture: Working with Stakeholders Using Viewpoints and Perspectives*, 2nd edition, Addison-Wesley.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from software-architecture expertise; generic delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | SE descriptor thread |
