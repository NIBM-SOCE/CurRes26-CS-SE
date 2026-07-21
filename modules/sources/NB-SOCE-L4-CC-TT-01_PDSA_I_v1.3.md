# Module Descriptor - Programming, Data Structures and Algorithms I

**Code:** NB-SOCE-L4-CC-TT-01  ·  **Tier:** Cluster Common (Tier 2)  ·  **Status:** Draft for Review v1.1  ·  **Date:** 20 Jul 2026
**Sources:** pathway registers SE v2.3 / AI&DS v2.1 / ITB v2.1 / NEC v1.1; 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md (Assessment Component Taxonomy); 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; v8.1 Phase 2 Register v1.0

> **Items requiring confirmation at review:** (1) the canonical learning-outcome set, inherited verbatim by the carrying registers once ratified; (2) assessment weightings and component attributes, confirmed at specification sign-off; (3) indicative syllabus hour allocations; (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-CC-TT-01 |
| Module title | Programming, Data Structures and Algorithms I |
| Scope / type | Cluster common (Tier 2)  ·  Common / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours) |
| Carried by | CS(SE), CS(AI&DS) - the named feeder anchor for NB5002CEM Programming, Data Structures and Algorithms 2. ITB overrides (no NB5002CEM in its destination); NEC does not carry it. |
| Prerequisites | Programming Concepts; Algorithmic Thinking |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3) |

## 2. Module Purpose and Aims

To implement, in code, the structures and algorithm families that Algorithmic Thinking established conceptually and Programming Concepts made expressible: linked structures, stacks, queues, trees, heaps and hash tables; searching, sorting and recursion; and the shift from complexity intuition to working Big-O analysis. The module is the direct on-ramp to NB5002CEM and deliberately stops short of advanced and distributed algorithms.

### Specification Boundary (canonical, v8.1 Phase 2)

> **Covers:** data structures (linked lists, trees, heaps, hash tables); core algorithm families; complexity (Big-O); introduction to concurrency and data-consistency concepts.
>
> **Does NOT cover:** advanced and distributed algorithms (NB5002CEM); pathway application stacks (owners named in each pathway's records).
>
> *The boundary text is the audited canonical text, identical in every carrying register. Any change is a change request against the Master Decisions register, not a descriptor-level edit.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Implement core data structures and justify the choice of structure for a given problem. | Apply / Analyse |
| LO2 | Implement and compare searching, sorting and recursive algorithms in code. | Apply / Analyse |
| LO3 | Analyse algorithm and data-structure performance using Big-O reasoning. | Analyse |
| LO4 | Explain concurrency and data-consistency concepts as they affect shared data structures. | Understand |

*Canonical set authored at this descriptor (v8.1 Phase 3); presented for ratification, after which the two carrying registers inherit it verbatim. As a Level 4 taught module it carries the cluster analytical-outcome rule with margin: LO1, LO2 and LO3 all sit at the analytical register (v8.1 Phase 2, Section 5).*

### Integrative Points and Seams

| Pathway | Integrative point / seam |
|---|---|
| CS(SE) and CS(AI&DS) | Named feeder for NB5002CEM; the withheld advanced content protects that vertical. AI&DS additionally leans on U3 to U6 in Machine Learning Engineering's performance-aware implementation work. |
| ITB | Overridden by design: ITB carries no formal algorithm analysis; Algorithmic Thinking's conceptual treatment is its full provision. A transiting ITB student meets this module inside the receiving pathway's bridge context. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | From conceptual structures to implementations: lists and linked lists | 9 |
| U2 | Stacks, queues and their applications | 6 |
| U3 | Trees and heaps | 9 |
| U4 | Hash tables | 6 |
| U5 | Core algorithm families in code: searching, sorting, recursion | 9 |
| U6 | Complexity analysis: Big-O in practice | 6 |
| U7 | Concurrency and data-consistency concepts: an introduction | 3 |
|  | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10). THE WORKING LANGUAGE IS PATHWAY-SPECIFIC (V14): Java for CS(SE), Python for CS(AI&DS), bound to the Programming Concepts instantiation the student's pathway carries; assessment runs from a common specification with language-equivalent task banks moderated across pathways. The module assumes Programming Concepts throughout and re-implements nothing from it; Algorithmic Thinking's conceptual treatment is the assumed substrate, formalised here into working analysis.

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
| CW-I-Home | Implementation portfolio: data structures and algorithms built to specification, each accompanied by a written complexity argument | Individual; take-home; graded; oral vehicle: None | LO1, LO2, LO3 | 50 |
| EX | Written examination: implementation reasoning, comparative analysis and Big-O; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO2, LO3, LO4 | 50 |

Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Goodrich, M. T. and Tamassia, R., Data Structures and Algorithms in Java (Wiley) - primary text for the CS(SE) instantiation.
- Goodrich, M. T., Tamassia, R. and Goldwasser, M. H., Data Structures and Algorithms in Python (Wiley) - primary text for the CS(AI&DS) instantiation.
- Sedgewick, R. and Wayne, K., Algorithms (Addison-Wesley) - selected chapters for U5 and U6.
- School-produced implementation specifications and the complexity-argument template, confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from algorithms and software-implementation expertise; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 19 Jul 2026 | Initial v8.1 descriptor | Phase 3 drafting |
| 1.1 | 20 Jul 2026 | Taxonomy-coded assessment with confirmed scheme; integrative table limited to carriers; placeholders removed; dual-format issue (MD source + governance docx) | Phase 3 drafting |
| 1.2 | 20 Jul 2026 | Working language resolved to Java (V13); reading completed; PC memory strand and ITB conceptual-alignment wording | Phase 3 drafting |
| 1.3 | 20 Jul 2026 | Pathway-instantiated working language (V14): Java CS(SE) / Python CS(AI&DS) as a bound pair; single-parameter rule; common assessment specification with cross-pathway moderation; dual primary texts | Phase 3 drafting |
