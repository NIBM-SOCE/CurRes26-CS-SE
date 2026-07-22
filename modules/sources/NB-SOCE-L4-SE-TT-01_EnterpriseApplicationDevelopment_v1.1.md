# Module Descriptor - Enterprise Application Development

**Code:** NB-SOCE-L4-SE-TT-01  ·  **Tier:** Pathway (SE)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.1  ·  **Date:** 21 Jul 2026
**Sources:** NIBM_SOCE_SE_ModuleRecords_Y12 v2.3; 00_Master_Decisions.md v2.6 (V13 working-languages register, as amended by V14 pathway instantiation); 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1

> **Items requiring confirmation at review:** (1) the learning-outcome set (canonical device: authored here from the record v2.3 stubs with the Level 4 register and the analytical-outcome cluster rule applied; ratified into the record set on confirmation); (2) assessment attributes and weightings at sign-off, including the no-examination stance stated in Section 5; (3) syllabus hour allocations; (4) indicative reading, including the framework text (Spring Boot named indicatively; the delivery framework is confirmed at teaching-plan stage); (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-SE-TT-01 |
| Module title | Enterprise Application Development |
| Scope / type | Pathway: CS(SE)  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  4 credits  ·  200 notional hours |
| Feeder targets (named) | NB6007CEM Web API Development (application construction); NB6034CEM Software Engineering 2 (large-scale solution build, applied design patterns, architecture in practice). Both claims STRENGTHEN under the SQL re-draw: students arrive SQL-fluent from Year 1 (V3.4), so the applied persistence work starts higher. |
| Prerequisites | Software Architecture Foundations (structure in principle, which this module implements); Programming Concepts (Java under the SE pathway instantiation, V14); Data Models and Management Systems (SQL fluency and DBMS use ASSUMED, not introduced). Inbound-transit note (V14): entrants transferring from a Python-based pathway arrive without Java and complete the self-paced Java transition pack attached by the SE inbound bridge before or alongside this module |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile; laboratory-heavy |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

The module is where structure moves from principle to practice for the CS(SE) vertical: students who can explain architectural styles and reason about quality attributes now build an enterprise application that implements those judgments through software design patterns, framework-based development and applied persistence. The working language is Java, continuing the Programming Concepts chain into the enterprise context (Java under the SE pathway instantiation, V14). The module holds one of the pathway's two DevOps homes - continuous integration for enterprise builds - paired with the delivery pipeline owned by Web and Cloud Application Development. The scope limit is honest: SQL and DBMS fundamentals are assumed from Year 1, not re-taught; architectural theory stays in its Year 1 owner; web, API and cloud delivery, and testing depth, are each owned elsewhere in the pathway.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** applied enterprise application construction; software design patterns (the folded "Software Architecture and Design Patterns" content lands here); applied persistence - data-access layers, framework and ORM persistence, transactions within an application build; framework-based development; a DevOps thread (continuous integration for enterprise builds - one of the two DevOps homes, paired with Web and Cloud Application Development's delivery pipeline).
>
> **Does NOT cover:** SQL teaching and DBMS fundamentals (Data Models and Management Systems, V3.4 - this module assumes fluency); architectural styles and quality-attribute theory (Software Architecture Foundations); web/API-specific and cloud delivery (Web and Cloud Application Development); testing and quality assurance depth (Software Quality and Testing).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Design and build an enterprise application, analysing the problem structure and justifying the design patterns selected | Analyse / Apply (Bloom); K-SAM 1, 2, 5 |
| LO2 | Implement a data-access and persistence layer over an assumed SQL base, using framework and ORM persistence with transactional integrity | Apply (Bloom); K-SAM 2, 7 |
| LO3 | Apply framework-based development and a continuous-integration workflow to an enterprise build | Apply (Bloom); K-SAM 2, 7 |

**LO provenance note (canonical device):** the set above is authored from the record v2.3 indicative stubs. LO1 absorbs the analytical dimension required by the Level 4 cluster rule ("analysing the problem structure and justifying the design patterns selected" per the Level 4 descriptor rows 1, 2 and 5); LO2 makes the transactional element explicit from the boundary text. No verb exceeds the Level 4 cognitive ladder; no K-SAM category 7 defence is required. On ratification the carrying register inherits this set verbatim; SLQF-04 for this module closes at that point.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Software Architecture Foundations | The principle-to-practice seam: "architectural styles and quality-attribute theory (Software Architecture Foundations)" stays there; this module implements |
| Data Models and Management Systems | "SQL teaching and DBMS fundamentals (Data Models and Management Systems, V3.4 - this module assumes fluency)" - SQL applied here, taught there |
| Web and Cloud Application Development | The DevOps pairing: continuous integration for enterprise builds here, the delivery pipeline there; "web/API-specific and cloud delivery (Web and Cloud Application Development)" |
| Software Quality and Testing | "testing and quality assurance depth (Software Quality and Testing)" - this module's pipeline runs automated checks but teaches no testing method |
| Mobile Application Development I | Design-pattern practice here is the enterprise depth; the mobile context applies patterns introductorily there |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | The enterprise application: layered application structure; from architectural principle to implementation practice; the Java enterprise context | 6 |
| U2 | Software design patterns: creational, structural and behavioural patterns; pattern selection, justification and trade-offs in a working build | 15 |
| U3 | Framework-based development: inversion of control and dependency injection; configuration; building within an enterprise framework | 12 |
| U4 | Applied persistence: data-access layers; object-relational mapping; transactions within the application build (SQL fluency assumed) | 12 |
| U5 | Enterprise build practice: modular construction and integration of components; error handling, logging and configuration management | 12 |
| U6 | Continuous integration for enterprise builds: build automation; automated checks in the integration pipeline | 9 |
| | **Total lecture hours** | **66** |

**Language note (V14):** the working language is Java, continuing the Programming Concepts chain (Java under the SE pathway instantiation); Spring Boot is the indicatively named framework, confirmed at teaching-plan stage. C/C++ exposure is not extended here.

Sessions run as 3-hour blocks (22 sessions); the laboratory-heavy allocation carries a single evolving application build across U2-U6.

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

Components per the Assessment Component Taxonomy; weightings confirmed at specification sign-off.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Enterprise application build: an individually built, pattern-documented application with persistence layer and continuous-integration evidence | Individual; take-home; graded; oral vehicle: Viva-defence | LO1, LO2, LO3 | 60 |
| CW-I-Class | Supervised applied exercise under open-resource conditions: pattern implementation and persistence tasks | Individual; in-class; graded; oral vehicle: None | LO1, LO2 | 40 |

No examination is carried by design: the assessed capability is applied construction, evidenced through the build and its pipeline; assessment integrity is anchored by the mandatory Viva-defence on the build and the supervised in-class component. Weights sum to 100. Reassessment is by failed component. Academic-integrity and generative-AI expectations follow School policy; the Viva-defence and the continuous-integration history are the authorship evidence on the take-home build.

## 6. Resources, Staff and Governance

### Indicative Reading

- Fowler, M., *Patterns of Enterprise Application Architecture*, Addison-Wesley.
- Gamma, E., Helm, R., Johnson, R. and Vlissides, J., *Design Patterns: Elements of Reusable Object-Oriented Software*, Addison-Wesley.
- Walls, C., *Spring in Action*, 6th edition, Manning. (Java- and framework-dependent text; applies if the Spring Boot naming is confirmed at teaching-plan stage.)

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from enterprise software-development expertise; generic delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | SE descriptor thread |
| 1.1 | 21 Jul 2026 | Prerequisite references the SE inbound Java transition pack for Python-based transfer entrants (V14); Java-continuity citation moved to V14 | SE descriptor thread |
