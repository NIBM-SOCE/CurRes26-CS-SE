# Module Descriptor - Data Models and Management Systems

**Code:** NB-SOCE-L3-CC-TT-02  ·  **Tier:** Cluster Common (Tier 2)  ·  **Status:** Draft for Review v1.1  ·  **Date:** 20 Jul 2026
**Sources:** pathway registers SE v2.3 / AI&DS v2.1 / ITB v2.1 / NEC v1.1; 01_Shared_Spine.md v2.2; 03_Module_Record_Template.md v1.1; 04_Conventions.md (Assessment Component Taxonomy); 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; v8.1 Phase 2 Register v1.0

> **Items requiring confirmation at review:** (1) the canonical learning-outcome set, inherited verbatim by the carrying registers once ratified; (2) assessment weightings and component attributes, confirmed at specification sign-off; (3) indicative syllabus hour allocations; (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-CC-TT-02 |
| Module title | Data Models and Management Systems |
| Scope / type | Cluster common (Tier 2)  ·  Common / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  4 credits  ·  200 notional hours (1 credit = 50 hours) |
| Carried by | CS(SE), CS(AI&DS), ITB - the School's single SQL teach-source (v8.1 Phase 2 close SE-P2-06). NEC does not carry it (its Data Management and Security module owns data protection and secure operations, not modelling instruction). |
| Prerequisites | None beyond the Tier 1 base |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4) |

## 2. Module Purpose and Aims

To establish how data is modelled, stored, queried and managed: entity-relationship and relational thinking, substantial SQL practice as the emphasis of the fourth credit (V3.4), DBMS fundamentals at use level, and a systems view of storage and retrieval across structured and semi-structured data. The module is the cluster's single SQL teach-source; every carrier consumes rather than re-teaches.

### Specification Boundary (canonical, v8.1 Phase 2)

> **Covers:** data-modelling concepts; relational-model foundations; structured and semi-structured data; a systems view of how data is stored and retrieved; DBMS fundamentals with SQL practice as the emphasis of the fourth credit.
>
> **Does NOT cover:** data-engineering and pipeline depth; production database administration (use and querying are in; administration remains out); relational schema design and normalisation at engineering level (owner: the pathway data-engineering provision where carried) [CR-AD-01, adopted 19 Jul 2026].
>
> *The boundary text is the audited canonical text, identical in every carrying register. Any change is a change request against the Master Decisions register, not a descriptor-level edit.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Model data using entity-relationship and relational concepts. | Apply |
| LO2 | Write SQL queries over relational data, including joins, aggregation and subqueries. | Apply |
| LO3 | Explain the role and core functions of a database management system, including transactions and access control at awareness level. | Understand |
| LO4 | Interpret how structured and semi-structured data are stored and retrieved within systems. | Understand / Apply |

*Canonical set authored at this descriptor (v8.1 Phase 3); presented for ratification, after which the three carrying registers inherit it verbatim. LO1 stops deliberately short of normalisation and engineering-level schema design per the adopted CR-AD-01 boundary.*

### Integrative Points and Seams

| Pathway | Integrative point / seam |
|---|---|
| CS(SE) | SQL and modelling applied in Enterprise Application Development; no re-teaching. |
| CS(AI&DS) | The first half of the policed two-module relational chain: Data Engineering and Pipelines carries schema design and normalisation at engineering level (CR-AD-01) and consumes this module's SQL base. |
| ITB | Programming for Data and Analytics consumes SQL programmatically in applied data work; instruction lives here (ITB boundary obligation 3). |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Data and the modelling view: entities, attributes, relationships | 9 |
| U2 | The relational model: relations, keys and integrity | 12 |
| U3 | SQL practice I: single-table querying, filtering, ordering, functions | 12 |
| U4 | SQL practice II: joins, aggregation, grouping and subqueries | 12 |
| U5 | DBMS fundamentals: services of a DBMS, transactions and access control at use level | 9 |
| U6 | Structured and semi-structured data; the systems view of storage and retrieval | 6 |
| U7 | Integrative practice: from model to query on realistic cases | 6 |
|  | Total lecture hours | 66 |

66 lecture hours are delivered as 22 three-hour sessions (V10). U3, U4 and U7 total 30 lecture hours of direct SQL practice, with the practicals allocation adding hands-on laboratory time - the visible form of the fourth-credit emphasis (V3.4).

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
| CW-I-Home | Modelling-to-query practical: an entity-relationship model built and queried in SQL over a realistic case | Individual; take-home; graded; oral vehicle: None | LO1, LO2, LO4 | 50 |
| EX | Written examination including an SQL-writing section and DBMS concepts; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO2, LO3 | 50 |

Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Elmasri, R. and Navathe, S. B., Fundamentals of Database Systems (Pearson) - selected foundational chapters within the boundary.
- Connolly, T. and Begg, C., Database Systems (Pearson) - alternative text, selected chapters.
- School-produced SQL practice sets and the realistic-case pack for U7, confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from database-systems expertise with current SQL practice; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 19 Jul 2026 | Initial v8.1 descriptor | Phase 3 drafting |
| 1.1 | 20 Jul 2026 | Taxonomy-coded assessment with confirmed scheme; integrative table limited to carriers; placeholders removed; dual-format issue (MD source + governance docx) | Phase 3 drafting |
