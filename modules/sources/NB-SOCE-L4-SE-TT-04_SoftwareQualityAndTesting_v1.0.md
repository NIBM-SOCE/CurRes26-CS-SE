# Module Descriptor - Software Quality and Testing

**Code:** NB-SOCE-L4-SE-TT-04  ·  **Tier:** Pathway (SE)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NIBM_SOCE_SE_ModuleRecords_Y12 v2.3; NIBM_SOCE_ITB_ModuleRecords_Y12 v2.1 (seam counterpart, quoted); 00_Master_Decisions.md v2.5 (V13); 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1

> **Items requiring confirmation at review:** (1) the learning-outcome set (canonical device: authored here from the record v2.3 stubs; ratified into the record set on confirmation); (2) assessment attributes and weightings at sign-off, including the no-examination stance stated in Section 5; (3) syllabus hour allocations, including the security-testing unit sizing (U6, one of the two secure-coding homes); (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-SE-TT-04 |
| Module title | Software Quality and Testing |
| Scope / type | Pathway: CS(SE)  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB6034CEM Software Engineering 2 (quality, testing, TDD, mocks and spies, version control - closes the Row 9 Year 2 SE-process seam); NB5000CEM Agile (automated testing and CI grounding); NB6035CEM Software Security (security testing builds on testing fundamentals). |
| Prerequisites | Software Engineering and Systems Analysis (process context); Programming Concepts |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

The module builds the quality and testing capability of the CS(SE) vertical from the construction side: how a developer designs and writes tests at unit, integration and acceptance level, practises test-driven development with test doubles, works under version-control discipline, and tests code for common security weaknesses. It is the repair for the front-loaded process provision - the Year 2 module that closes the software-engineering process seam into the Level 6 destination - and one of the pathway's two secure-coding homes. Its position on the construction side is a policed cross-pathway seam: this module tests software artefacts as part of building them; quality-assurance processes, test planning and design as a process discipline, and verification-and-validation management belong to ITB's Quality Assurance and Testing (Section 3, seams). The scope limits are honest: deployment and pipeline depth stay in the two DevOps homes, and architectural design stays in its Year 1 owner.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** software quality concepts and standards; testing strategies (unit, integration, acceptance); test-driven development; test doubles (mocks and spies); version control practice; a secure-coding thread (security testing - one of the two secure-coding homes feeding NB6035CEM).
>
> **Does NOT cover:** deployment and DevOps pipeline depth (Enterprise Application Development and Web and Cloud Application Development hold the two DevOps homes); architectural design (Software Architecture Foundations).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Apply testing strategies at unit, integration and acceptance level across the development lifecycle | Apply (Bloom); K-SAM 2, 7 |
| LO2 | Practise test-driven development, using test doubles to isolate the code under test | Apply (Bloom); K-SAM 2 |
| LO3 | Evaluate software quality against defined criteria, including security-testing findings | Evaluate (Bloom); K-SAM 1, 5 |

**LO provenance note (canonical device):** the set above is authored from the record v2.3 indicative stubs with minimal wording change: LO1 names the three levels from the boundary text; LO2 makes the isolation purpose of doubles explicit; LO3 folds the secure-coding strand into the evaluation outcome. LO3 carries the analytical outcome required by the Level 4 cluster rule (evaluate, per the Level 4 descriptor rows 1 and 5). No verb exceeds the Level 4 cognitive ladder; no K-SAM category 7 defence is required. On ratification the carrying register inherits this set verbatim; SLQF-04 for this module closes at that point.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Quality Assurance and Testing (ITB, NB-SOCE-L4-IB-TT-08) | The construction-side seam, quoted from the counterpart record: ITB's module "does NOT cover: software development and construction depth"; its covers are "software-quality concepts, quality-assurance processes, testing levels and techniques, test planning and design, verification and validation, and automated and continuous testing". This module stays on the construction side - the developer's testing of software artefacts within the build; the process and acceptance-management side belongs to ITB. The controls-testing/software-testing distinction is ITB-internal (standing obligation 7) and asserts nothing against this module. |
| Enterprise Application Development and Web and Cloud Application Development | "deployment and DevOps pipeline depth (Enterprise Application Development and Web and Cloud Application Development hold the two DevOps homes)" - tests written here run in pipelines owned there |
| Software Architecture Foundations | "architectural design (Software Architecture Foundations)" - testability observations here do not re-open structural design |
| Software Engineering and Systems Analysis | Prerequisite process context; this module completes at Year 2 the process provision front-loaded there |
| Web and Cloud Application Development (secure coding) | The two secure-coding homes feeding NB6035CEM: web application security there, security testing here |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Software quality: quality concepts and standards; quality attributes from the construction side; the cost of defects | 6 |
| U2 | Unit testing: test design at code level; assertions, coverage awareness and test quality | 9 |
| U3 | Integration and acceptance-level testing from the construction side: integration strategies; acceptance criteria expressed as tests | 9 |
| U4 | Test-driven development: the red-green-refactor cycle; test doubles - mocks and spies; refactoring under a green suite | 12 |
| U5 | Version control practice: branching and merging discipline; reviews; tests in the collaborative workflow | 6 |
| U6 | Security testing: testing for common vulnerability classes; the secure-coding strand from the testing side | 6 |
| | **Total lecture hours** | **48** |

**Language note (V13):** practical work is conducted in Java with its standard testing tooling, continuing the Programming Concepts chain per the pathway's working-languages posture; this is a tooling continuation, not a new language commitment. C/C++ exposure is not extended here.

Sessions run as 3-hour blocks (16 sessions); the laboratory allocation carries a continuously tested build across U2-U6.

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
| CW-I-Home | Tested, quality-assured build: a working codebase with its test suite, test-driven history and a quality evaluation report including security-testing findings | Individual; take-home; graded; oral vehicle: Viva-defence | LO1, LO2, LO3 | 60 |
| CW-I-Class | Supervised test-driven development exercise under open-resource conditions | Individual; in-class; graded; oral vehicle: None | LO1, LO2 | 40 |

No examination is carried by design: the assessed capability is testing practice demonstrated in code, and the test-driven history plus the mandatory Viva-defence and the supervised in-class component anchor integrity and authorship. Weights sum to 100. Reassessment is by failed component. Academic-integrity and generative-AI expectations follow School policy.

## 6. Resources, Staff and Governance

### Indicative Reading

- Beck, K., *Test-Driven Development: By Example*, Addison-Wesley. (Practice transfers to the Java tooling used in the laboratory.)
- Crispin, L. and Gregory, J., *Agile Testing: A Practical Guide for Testers and Agile Teams*, Addison-Wesley.
- Khorikov, V., *Unit Testing Principles, Practices, and Patterns*, Manning.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from software-quality and testing expertise; generic delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | SE descriptor thread |
