# Module Descriptor - Mathematical Thinking

**Code:** NB-SOCE-L3-CM-TT-02  ·  **Tier:** Institution-Wide Common (Tier 1)  ·  **Status:** Draft for Review v1.1  ·  **Date:** 20 Jul 2026
**Sources:** pathway registers SE v2.3 / AI&DS v2.1 / ITB v2.1 / NEC v1.1; 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md (Assessment Component Taxonomy); 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; v8.1 Phase 2 Register v1.0

> **Items requiring confirmation at review:** (1) the canonical learning-outcome set, inherited verbatim by the carrying registers once ratified; (2) assessment weightings and component attributes, confirmed at specification sign-off; (3) indicative syllabus hour allocations; (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-CM-TT-02 |
| Module title | Mathematical Thinking |
| Scope / type | Institution-wide common (Tier 1)  ·  Common / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  4 credits  ·  200 notional hours (1 credit = 50 hours) |
| Carried by | All four SOCE pathways - verbatim-identical wherever carried |
| Prerequisites | None beyond the Tier 1 base |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 (V10) |

## 2. Module Purpose and Aims

To build the shared quantitative foundation the four pathways' feeder chains genuinely require, delivered as mathematics for computing rather than generic service mathematics. The V3.2 fourth credit answers a named pressure: insufficient time at the cohort's pace. The rebuild therefore changes the pedagogy, not just the hours: every strand enters through a concrete computing artefact before formalism, every session runs a concept-practice-consolidate cycle, and the expanded conceptual treatment of sets, relations and functions becomes the grounding on which linear algebra and probability are built.

### Specification Boundary (canonical, v8.1 Phase 2)

> **Covers:** discrete structures with expanded conceptual treatment of sets, relations and functions; linear algebra foundations (vectors, matrix arithmetic) grounded in the discrete foundations; baseline probability (sample spaces, conditional probability, Bayes, random variables, distributions) grounded likewise; elementary modular arithmetic supporting Level 5 applied cryptography (NB5004CEM); a hands-on, pragmatic mathematics treatment throughout, paced for the cohort.
>
> **Does NOT cover:** statistical inference machinery; eigen-decomposition and calculus (owner named in each pathway's records where carried); applied statistical modelling (pathway and Coventry owners named in each pathway's records).
>
> *The boundary text is the audited canonical text, identical in every carrying register. Any change is a change request against the Master Decisions register, not a descriptor-level edit.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Use the language of logic, sets, relations and functions to describe computing structures. | Apply |
| LO2 | Perform vector and matrix operations on computing-derived data. | Apply |
| LO3 | Reason about uncertainty using foundational probability grounded in discrete models. | Apply / Analyse |
| LO4 | Apply modular arithmetic to elementary applied-cryptography problems. | Apply |

*Canonical set authored at this descriptor (v8.1 Phase 3), harmonising the four Phase 1 register variants; presented for ratification, after which the pathway registers inherit it verbatim. Every LO is phrased as doing mathematics on computing objects, matching the pragmatic treatment.*

### Integrative Points and Seams

| Pathway | Integrative point / seam |
|---|---|
| CS(AI&DS) | Direct feeder to Mathematics for Intelligent Systems (extends U3 to eigen-decomposition and inference-ready depth) and Statistical Methods and Analysis (builds inference on the U4 base); downstream the NB5018CEM chain. |
| CS(SE) | Modular arithmetic supporting applied cryptography in NB5004CEM; the U4 probability base assumed by NB5005CEM Data Science. |
| ITB | Foundation for Quantitative Methods for Business, the sole quantitative feeder for NB5015, NB5016 and NB5017; the ITB stress verdict stands with added margin under the fourth credit. |
| NEC | General quantitative literacy. The module carries no NEC Cryptography obligation: the NEC on-ramp is self-contained in its pathway modules (O14 two-touchpoint), and the former anchor clause is retired. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Mathematical language and structured reasoning: statements, conditions and quantifiers through code logic | 9 |
| U2 | Sets, relations and functions grounded in data and code: collections, links, mappings | 15 |
| U3 | Linear algebra foundations through computing artefacts: vectors as data, matrices as images, graphs and transformations | 15 |
| U4 | Probability foundations grounded in discrete structures: counting to distributions through logs, spam and games | 15 |
| U5 | Modular arithmetic for applied cryptography: clock arithmetic to key exchange intuition | 6 |
| U6 | Integrative pragmatic workshops: cross-strand problem clinics on realistic computing scenarios | 6 |
|  | Total lecture hours | 66 |

66 lecture hours are delivered as 22 three-hour sessions (V10), each structured as a concept-practice-consolidate cycle: roughly one hour of new concept through a computing artefact, and two hours of scaffolded worked practice. This is the cohort-pacing device of V3.2, delivered through session design rather than any banding, streaming or naming of student groups.

### Pedagogical Design (the V3.2 crafted element)

| Commitment | Meaning in delivery |
|---|---|
| Artefact-first entry | No strand opens with formalism. Sets enter through data collections, relations through database links, functions through code functions, matrices through images and adjacency structures, probability through logs and filtering, modular arithmetic through clock and checksum behaviour. |
| Concept-practice-consolidate cycle | Every session: one hour of concept through the artefact, two hours of scaffolded practice ending in a consolidation exercise that feeds the portfolio. Practice is the majority of contact time by design. |
| Grounded progression | U3 and U4 explicitly reuse U1 and U2 objects (vectors as functions on index sets; sample spaces as sets; events as subsets), so the cohort meets new mathematics as extensions of mastered structures, never as fresh starts. |

*The pacing device is structural, not nominal: nothing in naming, banding or grouping identifies any student segment (cohort-sensitivity rule, 04_Conventions.md).*

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 66 |
| Tutorials | 15 |
| Practicals / Laboratory | 30 |
| In-class assignments | 9 |
| Demonstration | 6 |
| Self-guided study | 74 |
| Total | 200 |

## 5. Assessment

Components per the Assessment Component Taxonomy (04_Conventions.md); weightings confirmed at specification sign-off. No formal examination is carried where none is listed.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Practice portfolio: cumulative computing-anchored problem sets across all strands, assembled session by session under the concept-practice-consolidate cycle | Individual; take-home; graded; oral vehicle: None | LO1, LO2, LO3, LO4 | 40 |
| CW-I-Class | Supervised mid-point techniques test: discrete structures and linear algebra; 1 hour | Individual; in-class (supervised); graded; oral vehicle: None | LO1, LO2 | 20 |
| EX | Written examination: techniques and applied reasoning across discrete structures, linear algebra, probability and modular arithmetic; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO2, LO3, LO4 | 40 |

Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Epp, S. S., Discrete Mathematics with Applications (Cengage) - primary text; the gentlest rigorous on-ramp for U1 and U2.
- Rosen, K. H., Discrete Mathematics and Its Applications (McGraw-Hill) - problem bank and the modular arithmetic strand.
- Lay, D. C., Lay, S. R. and McDonald, J. J., Linear Algebra and Its Applications (Pearson) - foundational chapters only, within the module boundary.
- School-produced computing-anchored practice sets (the portfolio spine), authored by the module leaders and confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from mathematics-for-computing expertise with demonstrated cohort-paced teaching practice; generic service-mathematics delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 19 Jul 2026 | Initial v8.1 descriptor | Phase 3 drafting |
| 1.1 | 20 Jul 2026 | Taxonomy-coded assessment with confirmed scheme; integrative table limited to carriers; placeholders removed; dual-format issue (MD source + governance docx) | Phase 3 drafting |
