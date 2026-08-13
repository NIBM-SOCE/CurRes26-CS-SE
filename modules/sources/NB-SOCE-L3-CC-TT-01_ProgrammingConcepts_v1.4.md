# Module Descriptor - Programming Concepts

**Code:** NB-SOCE-L3-CC-TT-01  ·  **Scope:** Common (Tier 2 cluster)  ·  **Type:** Common / Taught  ·  **Status:** Draft for Review v1.4  ·  **Date:** 13 Aug 2026
**Sources:** 01_Shared_Spine.md v2.3 (T2.1, adopted common text); 00_Master_Decisions.md v2.7; NIBM_SOCE_SE_ModuleRecords_Y12 v2.3; NIBM_SOCE_AIDS_ModuleRecords_Y12 v2.1; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1

> **Items requiring confirmation at review:** (1) assessment weightings and component attributes at specification sign-off; (2) indicative syllabus hour allocations within the units below; (3) indicative reading; (4) staffing names. The specification boundary and the learning-outcome set are adopted and are not open at review.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-CC-TT-01 |
| Module title | Programming Concepts |
| Scope / type | Common: CS(SE), CS(AI&DS)  ·  Common / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  4 credits  ·  200 notional hours (1 credit = 50 hours) |
| Working language | Pathway-instantiated (V14): Java for CS(SE); Python for CS(AI&DS). Single-parameter fence: the working language is the only variable. Boundary, outcomes and assessment specification are invariant. |
| Feeder targets (named) | NB5002CEM Algorithms and Data Structures (programming fluency and construction capability). Feeds Programming, Data Structures and Algorithms I as the bound-pair continuation, and the pathway construction verticals named in each carrying record. |
| Prerequisites | None as an entry condition. Co-runs with Algorithmic Thinking, whose designs are rendered in code here. |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals, in-class assignments and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

> **Shared module.** This module is delivered to the pathways named above and its specification is held in common. The specification boundary, learning outcomes and assessment specification may not be modified by any single pathway. Changes require the agreement of every carrying pathway and are made through the Master Decisions register. Physical custody of this file in the CS(SE) document set is an administrative arrangement of the current cycle and confers no editorial authority on that pathway.

## 2. Module Purpose and Aims

The module turns a student who can design a solution into a student who can build one. It takes the algorithmic reasoning developed alongside it and renders it in a production language, moving from first program to a program that is organised, tested and understood.

Its central commitment is that programs are built from parts, and that the parts have to be designed. Functions and modules give the first answer to that problem. Objects give the second, and the more consequential one: data and the operations on it held together, with the boundaries between parts made explicit. The module teaches object-oriented programming as a way of organising a program, not as syntax to be memorised, because everything the carrying pathways build in Year 2 assumes a student who thinks in these terms. Six modules on the Software Engineering pathway alone open on that assumption.

The treatment is deliberately paced for a foundationally varied cohort. Concepts are introduced with a worked reason for existing before the mechanism is shown, and the laboratory allocation carries the practice load. The module does not chase breadth. It teaches a small number of ideas until they are usable.

### Specification Boundary (quoted from 01_Shared_Spine.md v2.3, entry T2.1 - QUOTED, never edited)

> **Covers:** programming fundamentals in a production language; the pathway working language and its development tooling; control structures, functions and modular organisation; core data structures in code, including collections; object-oriented programming - classes and objects, encapsulation, inheritance, polymorphism and interface-style abstraction, expressed in the pathway working language; program design, testing and debugging practice.
>
> **Does NOT cover:** data-structure and algorithm implementation depth (Programming, Data Structures and Algorithms I); object-oriented design method, architectural styles and design patterns (owners named in each pathway's records); secure-coding depth (owners named in each pathway's records); pathway-owned applied stacks.
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Write, test and debug structured programs in the working language, using control structures, functions and modular organisation | Apply (Bloom); K-SAM 1, 2 |
| LO2 | Apply object-oriented programming to organise a program, selecting and defining appropriate types for a given problem | Apply (Bloom); K-SAM 1, 2 |
| LO3 | Use core data structures, including collections, to hold and manipulate data in code | Apply (Bloom); K-SAM 2 |
| LO4 | Render an algorithmic design as working code, explaining the choices made in translation | Apply / Analyse (Bloom); K-SAM 2, 5 |
| LO5 | Demonstrate disciplined development practice: testing habits, error handling and systematic debugging | Apply (Bloom); K-SAM 2, 6 |

**LO provenance note (canonical device):** the set is authored from the adopted common text at 01_Shared_Spine v2.3 T2.1 and from the SE record v2.3 indicative stubs. LO2 restores the record's stub "Apply object-oriented concepts in program design", rendered with the Committee-directed term "object-oriented programming" and extended to name type definition, which is the concrete Level 3 behaviour. LO1 and LO5 separate construction from development discipline, which the record stubs carried together. LO3 carries the collections strand named in the adopted text. LO4 is the explicit bridge from Algorithmic Thinking and is the module's only analytical outcome; SLQF-04 does not require an analytical cluster at Level 3, and LO4 is carried on merit rather than to satisfy a rule. No verb exceeds the Level 3 cognitive ladder. No K-SAM category 7 defence is required. On ratification the carrying records inherit this set verbatim.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Algorithmic Thinking (Tier 1 common) | Co-runs. Designs and pseudocode are produced there and rendered in code here. Complexity intuition is theirs; implementation is ours. |
| Programming, Data Structures and Algorithms I (Year 2) | The bound pair (V14). This module supplies the object model, collections literacy and construction fluency that PDSA I assumes whole; PDSA I implements structures at depth and re-implements nothing taught here. The dependency is load-bearing in both languages. |
| Software Architecture Foundations, Enterprise Application Development, Software Engineering and Systems Analysis, Mobile Application Development I, Software Quality and Testing (CS(SE)) | All open on the object model established here. Design method, architectural styles and design patterns are theirs; the objects those patterns arrange are ours. The does-NOT-cover line polices the seam from this side. |
| Applied Data Exploration, Web and API Technologies, Machine Learning Engineering (CS(AI&DS)) | Consume Python fluency, control and data structures, functions and modularity. The object strand is carried as general programming literacy; no AI&DS module assumes it as a prerequisite. |
| Programming for Data and Analytics (ITB) | The ITB override. Core alignment is claimed against the control, functions and data-structures core only, and not against the object strand, which ITB excludes by design. Outbound transfer counselling reflects this. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | The working environment: tooling, editing, running and compiling; how a program becomes a running process; a first look at memory and at C as the reference point for what the working language manages | 6 |
| U2 | Variables, types and expressions; control structures: selection, iteration, and the shape of a well-formed block | 12 |
| U3 | Functions and modular organisation: parameters, return values, scope; organising a program into parts | 9 |
| U4 | Object-oriented programming I: why objects exist; classes and objects; state and behaviour held together; encapsulation and the boundary of a type; defining types for a stated problem | 6 |
| U5 | Object-oriented programming II: inheritance and the reuse of behaviour; polymorphism; interface-style abstraction and programming to a contract; when not to reach for inheritance | 3 |
| U6 | Core data structures in code: sequences, mappings and strings; collections in the working language and the operations they support | 6 |
| U7 | File handling and simple input and output | 6 |
| U8 | Error handling, testing habits and systematic debugging | 9 |
| U9 | Integrative build: small structured programs written from algorithmic designs, using the object model where it earns its place | 9 |
|  | Total lecture hours | 66 |

66 lecture hours are delivered as 22 three-hour sessions (V10). U4 and U5 carry the object strand at 9 hours combined, funded by the reductions to U3 and U6 agreed at Committee item 1. U5 is short by design: inheritance and polymorphism are introduced conceptually and exercised in the laboratory rather than lectured at length, and the 30 practical hours carry that load. The session plan is produced at teaching-plan stage.

**Adoption record for this syllabus.** Against the prior v1.3 structure, modular organisation reduces from 12 to 9 hours and core data structures from 12 to 6, releasing 9 hours for U4 and U5. The cost is named: collections breadth narrows to the structures that Programming, Data Structures and Algorithms I extends in Year 2, and that recovery is structural rather than assumed, since the two modules are a bound pair.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 66 |
| Tutorials | 15 |
| Practicals / Laboratory | 30 |
| In-class assignments | 9 |
| Demonstration | 6 |
| Self-guided study | 74 |
| **Total** | **200** |

## 5. Assessment

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The module is assessed from a single specification across both instantiations, with language-equivalent task sets moderated jointly each cycle. Task sets must exercise the object strand in both languages.

| Ref | Component | Attributes | Outcomes | Weight |
|---|---|---|---|---|
| CW-Port | Programming portfolio: a sequence of building tasks culminating in a small program organised around defined types, with a short written account of the design choices | Individual; out-of-class; graded; oral vehicle: None | LO1, LO2, LO3, LO4, LO5 | 60 |
| CW-I-Class | Supervised machine-based practical programming test; 2 hours, stated open resources, no communication tools | Individual; in-class (supervised); graded; oral vehicle: None | LO1, LO2, LO3 | 40 |
| | **Total** | | | **100** |

**Assessment note.** No written examination is carried. The module's outcomes are constructional and are evidenced by construction. The supervised practical test secures individual attribution for the portfolio strand.

## 6. Indicative Reading

- Liang, Y. D., *Introduction to Java Programming and Data Structures* - CS(SE) instantiation; foundational chapters and the object-oriented chapters within the boundary.
- Matthes, E., *Python Crash Course* - CS(AI&DS) instantiation; foundational chapters and the classes chapter within the boundary.
- Downey, A. B., *Think Python* / *Think Java* - supporting text for the cohort-paced treatment.
- Kernighan, B. W. and Ritchie, D. M., *The C Programming Language* - U1 reference use only, for the memory strand.

## 7. Version History

| Version | Date | Change |
|---|---|---|
| 1.0 | 19 Jul 2026 | Initial issue. |
| 1.1 | 19 Jul 2026 | Assessment attributes aligned to the component taxonomy. |
| 1.2 | 20 Jul 2026 | Hours profile reconciled. |
| 1.3 | 20 Jul 2026 | Re-issued under V14: working language stated as pathway-instantiated; common assessment specification recorded. |
| 1.4 | 13 Aug 2026 | Re-issued under the adopted common text (01_Shared_Spine v2.3 T2.1, Committee item 1). Object-oriented programming restored to boundary, outcomes and syllabus as U4 and U5, funded by reductions to modular organisation and core data structures. Boundary now quoted rather than self-certified. LO provenance note and K-SAM mapping added. Shared-module notice added. Header status, version table and filename reconciled. |
