# Module Descriptor - Digital Electronics and Logic Design

**Code:** NB-SOCE-L3-CM-TT-04  ·  **Tier:** Institution-Wide Common (Tier 1)  ·  **Status:** Draft for Review v1.2  ·  **Date:** 13 Aug 2026
**Sources:** 01_Shared_Spine.md v2.2; 00_Master_Decisions.md v2.7; pathway registers SE v2.3 / AI&DS v2.1 / ITB v2.1 / NEC v1.1; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; v8.1 Phase 2 Register v1.0

> **Items requiring confirmation at review:** (1) the canonical learning-outcome set, inherited verbatim by the carrying registers once ratified; (2) assessment weightings and component attributes, confirmed at specification sign-off; (3) indicative syllabus hour allocations; (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-CM-TT-04 |
| Module title | Digital Electronics and Logic Design |
| Scope / type | Institution-wide common (Tier 1)  ·  Common / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours) |
| Carried by | All four SOCE pathways - verbatim-identical wherever carried |
| Prerequisites | None beyond the Tier 1 base |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 (V10); laboratory-weighted adjustment permitted at specification within the invariants |

> **Shared module.** This module is delivered to the pathways named above and its specification is held in common. The specification boundary, learning outcomes and assessment specification may not be modified by any single pathway. Changes require the agreement of every carrying pathway and are made through the Master Decisions register. Physical custody of this file in the CS(SE) document set is an administrative arrangement of the current cycle and confers no editorial authority on that pathway.

## 2. Module Purpose and Aims

To give every SOCE student a genuine hardware foundation: designing and verifying digital logic, understanding the electronic components that realise it, and seeing the bridge from gates to processor operation. This module is the v8.1 hardware shift in curricular form - the full answer to the stakeholder issues that v8's software-only strand deferred - and it is deliberately laboratory-based: students build and test what they design.

### Specification Boundary (quoted from 01_Shared_Spine.md v2.2, entry T1.4 - QUOTED, never edited)

> **Covers:** combinational and sequential logic design; digital electronics fundamentals at introductory laboratory level (components, gates, simple circuits); the bridge from logic to computer organisation and processor operation; number systems applied in hardware; laboratory practice throughout.
>
> **Does NOT cover:** embedded systems programming; electronics engineering depth; pathway infrastructure content (the boundary with NEC's Operating Systems and Infrastructure is policed at specification stage - OS&I keeps its systems-administration substrate, DELD owns logic and electronics).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Design and verify combinational and sequential logic circuits. | Apply / introductory Create (defended below) (Bloom); K-SAM 2, 5 |
| LO2 | Explain the operation of common digital electronic components within simple circuits. | Understand (Bloom); K-SAM 1 |
| LO3 | Relate logic-level design to computer organisation and processor operation. | Understand / Apply (Bloom); K-SAM 1 |
| LO4 | Build and test digital circuits using laboratory instruments and simulation tools. | Apply (Bloom); K-SAM 2, 7 |

**LO provenance note (canonical device):** the set is quoted-source aligned to 01_Shared_Spine v2.2 T1.4. LO1's verb was confirmed at the SE Phase 2 close and the formal defence is stated below. The category gloss carried at v1.1 is corrected at this re-issue: category 7 is Information Usage and Management in 07_SLQF_Reference v1.1, not practical and psychomotor skills, and the practical-performance defence properly rests on category 2. K-SAM category names follow 07_SLQF_Reference v1.1: 1 Subject / Theoretical Knowledge, 2 Practical Knowledge and Application, 5 Creativity and Problem Solving, 7 Information Usage and Management. On ratification the four carrying records inherit this set verbatim.

### Integrative Points and Seams

| Pathway | Integrative point / seam |
|---|---|
| CS(SE) | The concrete hardware referent behind software abstractions and the I-027 admissions selling point; memory and execution grounding referenced when Algorithmic Thinking teaches complexity. |
| CS(AI&DS) | Hardware literacy toward edge and accelerator awareness; the physical substrate beneath the computational stack. |
| NEC | Boundary policed against Operating Systems and Infrastructure: DELD owns logic and electronics, OS&I keeps systems administration; jointly they carry the hardware and forensics substrate. |
| ITB | The concrete hardware referent under the Business Information Systems socio-technical view; reinforces the NB6029 bootstrapped pipeline alongside FoC's raised network awareness; combinational-logic reasoning as cohort-wide analytical formation (ITB DELD declaration). |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Number systems in hardware and switching fundamentals | 6 |
| U2 | Logic gates and Boolean algebra | 9 |
| U3 | Combinational logic design (laboratory) | 12 |
| U4 | Sequential logic design: latches, flip-flops, registers, counters (laboratory) | 12 |
| U5 | From logic to computer organisation: ALU, memory and the processor bridge | 6 |
| U6 | Digital electronics fundamentals: components and simple circuits | 3 |
|  | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10), with U3 and U4 run as integrated design-and-build laboratory sessions. The A-3 practicals and demonstration components carry the hands-on build time; a laboratory-weighted shift among timetabled components is expected at specification stage within the V10 invariants.

### K-SAM Verb Defence (per NEC finding N8a, stated not assumed)

> **Defence:** LO1 ("Design and verify") and LO4 ("Build and test") sit above the typical Level 3 cognitive ladder but are defended under K-SAM category 2 (Practical Knowledge and Application), with the laboratory-instrument and simulation-tool strand additionally engaging category 7 (Information Usage and Management): introductory circuit design from a truth-table specification, and laboratory construction and testing against it, are genuine skill performances at this level, standard in first-year digital-logic provision internationally. The cognitive-domain outcomes (LO2, LO3) sit at the conventional Level 3 register. This defence travels into the compliance narrative of the validation submission.

### Lineage and Resourcing

This module answers issues I-001, I-002 and I-003 and I-012, I-016 and I-027 in full, reversing the v8 software-only posture (CR-SE-01, superseded). Its two named institutional costs stand from V2: laboratory kit provision and electronics-capable staffing under D7.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 48 |
| Tutorials | 12 |
| Practicals / Laboratory | 24 |
| In-class assignments | 9 |
| Demonstration | 3 |
| Self-guided study | 54 |
| Total | 150 |

## 5. Assessment

Components per the Assessment Component Taxonomy (04_Conventions.md); weightings confirmed at specification sign-off. No formal examination is carried where none is listed.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-G-Class | Laboratory design-build-verify tasks: specified combinational and sequential circuits designed, built and tested at paired benches, with an individually maintained evidence log per student | Group (n = 2) at the bench; individually logged and graded; in-class | LO1, LO2, LO4 | 50 |
| EX | Written examination: Boolean algebra, circuit analysis and the logic-to-organisation bridge; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO2, LO3 | 50 |

Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Mano, M. M. and Ciletti, M. D., Digital Design (Pearson) - primary text for logic design.
- Floyd, T. L., Digital Fundamentals (Pearson) - electronics-side support and laboratory grounding.
- Harris, D. and Harris, S., Digital Design and Computer Architecture (Morgan Kaufmann) - selected chapters for the U5 bridge.
- School-produced laboratory manuals and simulation-tool guides (kit-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from digital-electronics and logic-design expertise with laboratory instruction capability; generic delivery is non-compliant (D7). Electronics-capable staffing and laboratory kit are named V2 resourcing commitments.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 19 Jul 2026 | Initial v8.1 descriptor | Phase 3 drafting |
| 1.1 | 20 Jul 2026 | Taxonomy-coded assessment with confirmed scheme; integrative table limited to carriers; placeholders removed; dual-format issue (MD source + governance docx) | Phase 3 drafting |
| 1.2 | 13 Aug 2026 | Re-issued under the authoring regime adopted at Curriculum Committee 13 Aug 2026: boundary quoted from 01_Shared_Spine.md v2.2, entry T1.4 rather than self-certified; LO provenance note added; K-SAM mapping applied; shared-module notice added. No specification change. | Curriculum Committee, 13 Aug 2026 |
