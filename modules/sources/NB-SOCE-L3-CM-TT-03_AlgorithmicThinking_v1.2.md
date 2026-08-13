# Module Descriptor - Algorithmic Thinking

**Code:** NB-SOCE-L3-CM-TT-03  ·  **Tier:** Institution-Wide Common (Tier 1)  ·  **Status:** Draft for Review v1.2  ·  **Date:** 13 Aug 2026
**Sources:** 01_Shared_Spine.md v2.2; 00_Master_Decisions.md v2.7; pathway registers SE v2.3 / AI&DS v2.1 / ITB v2.1 / NEC v1.1; 03_Module_Record_Template.md v1.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; v8.1 Phase 2 Register v1.0

> **Items requiring confirmation at review:** (1) the canonical learning-outcome set, inherited verbatim by the carrying registers once ratified; (2) assessment weightings and component attributes, confirmed at specification sign-off; (3) indicative syllabus hour allocations; (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-CM-TT-03 |
| Module title | Algorithmic Thinking |
| Scope / type | Institution-wide common (Tier 1)  ·  Common / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours) |
| Carried by | All four SOCE pathways - verbatim-identical wherever carried |
| Prerequisites | None beyond the Tier 1 base |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 (V10) |

> **Shared module.** This module is delivered to the pathways named above and its specification is held in common. The specification boundary, learning outcomes and assessment specification may not be modified by any single pathway. Changes require the agreement of every carrying pathway and are made through the Master Decisions register. Physical custody of this file in the CS(SE) document set is an administrative arrangement of the current cycle and confers no editorial authority on that pathway.

## 2. Module Purpose and Aims

To develop language-independent algorithmic reasoning: decomposing problems into structured, solvable components; expressing solutions in pseudocode and flow representations; understanding searching, sorting and elementary data structures conceptually; and building an intuition for algorithmic efficiency, deliberately short of formal asymptotic analysis, which is owned downstream. The V3.3 re-banding trims hours, not boundary: the conceptual scope is unchanged from v8.

### Specification Boundary (quoted from 01_Shared_Spine.md v2.2, entry T1.3 - QUOTED, never edited)

> **Covers:** problem decomposition; pseudocode and flow representation; searching and sorting concepts; elementary data structures conceptually; complexity intuition (not formal asymptotic analysis).
>
> **Does NOT cover:** implementation in a production language; formal algorithm analysis (owners named in each pathway's records).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Decompose problems into structured, solvable components. | Analyse (Bloom); K-SAM 5 |
| LO2 | Represent solutions using pseudocode and flow representations. | Apply (Bloom); K-SAM 2, 3 |
| LO3 | Compare searching and sorting strategies conceptually. | Analyse (Bloom); K-SAM 1, 5 |
| LO4 | Reason informally about algorithmic efficiency. | Analyse / Evaluate (informal) (Bloom); K-SAM 1, 5 |

**LO provenance note (canonical device):** the set is quoted-source aligned to 01_Shared_Spine v2.2 T1.3 and is unchanged in substance from the v8 set. LO4's informal register is deliberate: complexity intuition is taught here and formal asymptotic analysis is owned by Programming, Data Structures and Algorithms I. K-SAM category names follow 07_SLQF_Reference v1.1: 1 Subject / Theoretical Knowledge, 2 Practical Knowledge and Application, 3 Communication, 5 Creativity and Problem Solving. On ratification the four carrying records inherit this set verbatim.

### Integrative Points and Seams

| Pathway | Integrative point / seam |
|---|---|
| CS(SE) and CS(AI&DS) | Supplies the language-independent reasoning that Programming, Data Structures and Algorithms I implements and NB5002CEM extends; withholding formal asymptotic analysis protects that vertical. |
| ITB | Conceptual base for Programming for Data and Analytics; ITB carries no formal algorithm analysis by design (PDSA I overridden), so this treatment is the pathway's full provision. |
| NEC | Dovetails with Applied Programming for Networks and Security with no gap or overlap (O13); the two specifications stay aligned at specification stage. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Problem decomposition and abstraction | 9 |
| U2 | Pseudocode and flow representation | 9 |
| U3 | Searching strategies conceptually | 6 |
| U4 | Sorting strategies conceptually | 9 |
| U5 | Elementary data structures conceptually: lists, stacks, queues, trees | 9 |
| U6 | Complexity intuition and efficiency reasoning | 6 |
|  | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); the V3.3 trim removes 18 v8-plan lecture hours through tightened practice density, not scope loss. Outcome coverage note: U5 (elementary data structures) is the conceptual substrate for LO3 and LO4 - the searching, sorting and efficiency reasoning in U3, U4 and U6 is taught over these structures - and is assessed through the design portfolio rather than as a standalone outcome, consistent with the four canonical LOs.

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
| CW-I-Home | Algorithm design portfolio: five to six graded problems, each with decomposition, pseudocode over elementary data structures and an informal efficiency argument | Individual; take-home; graded; oral vehicle: None | LO1, LO2, LO3, LO4 | 60 |
| CW-I-Class | Supervised design-and-reasoning test: decomposition, representation and conceptual comparison of strategies; 90 minutes | Individual; in-class (supervised); graded; oral vehicle: None | LO1, LO2, LO3 | 40 |

Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Cormen, T. H., Algorithms Unlocked (MIT Press) - conceptual treatment matched to the pre-formal register.
- Denning, P. J. and Tedre, M., Computational Thinking (MIT Press) - decomposition and abstraction framing.
- Polya, G., How to Solve It (Princeton) - problem-decomposition heritage text, selected use.
- School-produced pseudocode convention guide and graded problem sets, confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from algorithms and computational-thinking expertise; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 19 Jul 2026 | Initial v8.1 descriptor | Phase 3 drafting |
| 1.1 | 20 Jul 2026 | Taxonomy-coded assessment with confirmed scheme; integrative table limited to carriers; placeholders removed; dual-format issue (MD source + governance docx) | Phase 3 drafting |
| 1.2 | 13 Aug 2026 | Re-issued under the authoring regime adopted at Curriculum Committee 13 Aug 2026: boundary quoted from 01_Shared_Spine.md v2.2, entry T1.3 rather than self-certified; LO provenance note added; K-SAM mapping applied; shared-module notice added. No specification change. | Curriculum Committee, 13 Aug 2026 |
