# Module Descriptor - Programming Concepts

**Code:** NB-SOCE-L3-CC-TT-01  ·  **Tier:** Cluster Common (Tier 2)  ·  **Status:** Draft for Review v1.1  ·  **Date:** 20 Jul 2026
**Sources:** pathway registers SE v2.3 / AI&DS v2.1 / ITB v2.1 / NEC v1.1; 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md (Assessment Component Taxonomy); 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; v8.1 Phase 2 Register v1.0

> **Items requiring confirmation at review:** (1) the canonical learning-outcome set, inherited verbatim by the carrying registers once ratified; (2) assessment weightings and component attributes, confirmed at specification sign-off; (3) indicative syllabus hour allocations; (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-CC-TT-01 |
| Module title | Programming Concepts |
| Scope / type | Cluster common (Tier 2)  ·  Common / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  4 credits  ·  200 notional hours (1 credit = 50 hours) |
| Carried by | CS(SE), CS(AI&DS). ITB overrides with Programming for Data and Analytics, whose foundational core is aligned to this boundary for transit and recognition of prior learning (the D8 core-alignment commitment). NEC does not carry it (Applied Programming for Networks and Security). |
| Prerequisites | None beyond the Tier 1 base |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4) |

## 2. Module Purpose and Aims

To turn the language-independent reasoning of Algorithmic Thinking into working code: structured programs in a production language, with control structures, functions, modular organisation and core data structures used in practice, and the testing and debugging habits of a working programmer. The module is the cluster's programming teach-source; downstream depth belongs to Programming, Data Structures and Algorithms I and to pathway application stacks.

### Specification Boundary (canonical, v8.1 Phase 2)

> **Covers:** production-language programming; control and data structures in code; functions and modularity; introduction to the working language and development tooling.
>
> **Does NOT cover:** data-structure and algorithm depth (Programming, Data Structures and Algorithms I); pathway-owned applied stacks and secure-coding depth (owners named in each pathway's records).
>
> *The boundary text is the audited canonical text, identical in every carrying register. Any change is a change request against the Master Decisions register, not a descriptor-level edit.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Implement structured programs using control structures, functions and modular organisation. | Apply |
| LO2 | Use core data structures in code to represent and manipulate data. | Apply |
| LO3 | Translate algorithmic designs expressed in pseudocode and flow representations into working programs. | Apply |
| LO4 | Apply systematic testing and debugging practices to locate and correct defects. | Apply / Analyse |

*Canonical set authored at this descriptor (v8.1 Phase 3); presented for ratification, after which the carrying registers inherit it verbatim. LO3 is the explicit bridge from Algorithmic Thinking; LO4 seeds the quality practices that Software Quality and Testing deepens on the SE pathway.*

### Integrative Points and Seams

| Pathway | Integrative point / seam |
|---|---|
| CS(SE) | Feeds the SE implementation verticals in the declared high-level language (Java, V13); LO4's testing habits seed Software Quality and Testing; the U1 memory strand serves the NB6035CEM chain. |
| CS(AI&DS) | Java foundations here; the pathway's Python competence is owned by Applied Data Exploration (introduction) and Machine Learning Engineering (production), giving AI&DS graduates a deliberate polyglot base (V13). |
| ITB (override alignment) | Programming for Data and Analytics (Python, V13) keeps its foundational core CONCEPTUALLY aligned to this boundary - control, functions, structures - so transit recognition remains defensible; the working languages differ, and a transiting student faces a language switch, stated openly as a counselling point. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | From pseudocode to code: the working environment, tooling, and from source to machine (compilation and the memory model, with a first look at C) | 6 |
| U2 | Variables, types, expressions and control structures | 12 |
| U3 | Functions, modularity and program organisation | 12 |
| U4 | Core data structures in code: sequences, mappings, strings | 12 |
| U5 | File handling and simple input and output | 6 |
| U6 | Error handling, testing habits and debugging | 9 |
| U7 | Integrative build: small structured programs from algorithmic designs | 9 |
|  | Total lecture hours | 66 |

66 lecture hours are delivered as 22 three-hour sessions (V10), with practicals and laboratory hours carrying hands-on coding throughout. THE WORKING LANGUAGE IS JAVA (V13): the cluster working language for this module and Programming, Data Structures and Algorithms I. U1 carries a bounded compilation-and-memory strand with a first look at C, justified by the NB6035CEM memory-model assumption on the SE destination and the bridge from Digital Electronics and Logic Design; it is exposure, not a C teaching commitment.

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
| CW-I-Home | Programming portfolio: cumulative structured-program tasks culminating in the integrative build from an algorithmic design | Individual; take-home; graded; oral vehicle: None | LO1, LO2, LO3, LO4 | 60 |
| CW-I-Class | Supervised machine-based practical programming test; 2 hours, stated open resources, no communication tools | Individual; in-class (supervised); graded; oral vehicle: None | LO1, LO2, LO3 | 40 |

Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Liang, Y. D., Introduction to Java Programming and Data Structures (Pearson) - primary text, foundational chapters within the boundary.
- School-produced coding standards, problem sets and the pseudocode-to-code convention guide shared with Algorithmic Thinking, confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from software-development expertise with current production-language practice; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 19 Jul 2026 | Initial v8.1 descriptor | Phase 3 drafting |
| 1.1 | 20 Jul 2026 | Taxonomy-coded assessment with confirmed scheme; integrative table limited to carriers; placeholders removed; dual-format issue (MD source + governance docx) | Phase 3 drafting |
| 1.2 | 20 Jul 2026 | Working language resolved to Java (V13); reading completed; PC memory strand and ITB conceptual-alignment wording | Phase 3 drafting |
