# Module Descriptor - Mobile Application Development I

**Code:** NB-SOCE-L4-SE-TT-03  ·  **Tier:** Pathway (SE)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.2  ·  **Date:** 21 Jul 2026
**Sources:** NIBM_SOCE_SE_ModuleRecords_Y12 v2.3; 00_Master_Decisions.md v2.6 (V13 working-languages register as amended by V14 - this descriptor records the SE-thread platform-language decision delegated under V13); 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; Descriptor Edit Note - Mobile Application Development I (CS SE pathway composition analysis finding, 21 Jul 2026)

> **Items requiring confirmation at review:** (1) the learning-outcome set (canonical device: authored here from the record v2.3 stubs with the Level 4 register and the analytical-outcome cluster rule applied; ratified into the record set on confirmation); (2) **the platform-language decision - Kotlin on Android - recorded in Section 4 with its reasoning and named costs; ratification here also reports the decision for adoption into the working-languages register (V13 as amended by V14) at reconciliation**; (3) assessment attributes and weightings at sign-off, including the no-examination stance stated in Section 5; (4) syllabus hour allocations; (5) indicative reading (Kotlin-dependent entries); (6) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-SE-TT-03 |
| Module title | Mobile Application Development I |
| Scope / type | Pathway: CS(SE)  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | NB6033CEM Mobile Application Development 2 - the direct numbered predecessor (clean anchor). Supplies the mobile build, design-pattern and API-consumption base that MAD 2 extends into MVVM, continuous integration and analytics. |
| Prerequisites | Programming Concepts (OOP); design-pattern awareness from Software Architecture Foundations; API consumption from Web and Cloud Application Development; Data Models and Management Systems (data integration - an explicit prerequisite under the SQL re-draw) |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile; laboratory-heavy |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

The module builds native mobile development for the CS(SE) vertical and is the direct numbered predecessor of its Coventry continuation: the mobile build, design-pattern and API-consumption base that Mobile Application Development 2 extends into MVVM, continuous integration and crash analytics. Its 3-credit scope is defensible because the supporting spine now carries more of its load than before - design-pattern awareness arrives from Software Architecture Foundations, API-consumption mechanics from Web and Cloud Application Development, and SQL practice from Data Models and Management Systems (V3.4) - so the module narrows to its mobile-specific core. The costs are recorded honestly: the trimmed 18 lecture hours land on platform breadth and polish, not on the base the Coventry continuation extends; and the named risk stands in the record - the cleanest numbered anchor in the year was trimmed to fund a non-feeder module, a defence that appears in the validation narrative. Platform breadth is also where the language decision lands: one native platform, taught properly (Section 4).

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** mobile application development; introductory software design patterns in the mobile context; UI construction for mobile; database integration and RESTful API consumption in a mobile app (consumption level).
>
> **Does NOT cover:** the MVVM architectural pattern, continuous integration and crash-analytics depth (NB6033CEM at Coventry); SQL teaching (Data Models and Management Systems).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Build a functional mobile application for the target platform | Apply (Bloom); K-SAM 2, 7 |
| LO2 | Apply introductory design patterns in the mobile context, analysing their fit to a given application structure | Analyse / Apply (Bloom); K-SAM 1, 2, 5 |
| LO3 | Construct an event-driven mobile user interface following platform conventions | Apply (Bloom); K-SAM 2 |
| LO4 | Integrate a local database and consume a RESTful API within a mobile application | Apply (Bloom); K-SAM 2, 7 |

**LO provenance note (canonical device):** the set above is authored from the record v2.3 indicative stubs, with the record's compound LO2 split into pattern work (LO2) and UI construction (LO3) for assessability. At v1.1, user-interaction event handling is named in U2 and LO3 is worded "event-driven" - a pre-ratification naming refinement at the LO/syllabus layer (sourced from the composition-analysis finding, 21 Jul 2026); lifecycle events remain in U1, the MVVM carve is untouched, and no boundary text changes. LO2 absorbs the analytical dimension required by the Level 4 cluster rule ("analysing their fit to a given application structure" per the Level 4 descriptor row 1). No verb exceeds the Level 4 cognitive ladder; no K-SAM category 7 defence is required. On ratification the carrying register inherits this set verbatim; SLQF-04 for this module closes at that point.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| NB6033CEM (Coventry) | The numbered-chain boundary, quoted: "the MVVM architectural pattern, continuous integration and crash-analytics depth (NB6033CEM at Coventry)" |
| Software Architecture Foundations | Design-pattern awareness arrives from there; this module applies patterns introductorily in the mobile context |
| Web and Cloud Application Development | API-consumption mechanics taught there; consumed here at consumption level |
| Data Models and Management Systems | "SQL teaching (Data Models and Management Systems)" - data integration here assumes the taught SQL practice |

## 4. Curriculum and Delivery

### Platform-Language Decision (V13 delegation, recorded)

**The platform language is Kotlin, on the Android platform.** This is the SE thread's one delegated language decision under V13, recorded here and reported for adoption into the working-languages register at Phase 2 reconciliation. Reasoning: (1) the Coventry continuation extends this module into MVVM, continuous integration and crash analytics, an extension chain native to the Android/Kotlin toolchain; (2) Programming Concepts runs Java under the SE pathway instantiation (V14) - Kotlin is JVM-based and Java-interoperable, making the language transition the cheapest available and teachable as a managed transition in U1; (3) one native platform taught properly beats cross-platform breadth at the trimmed 3-credit scope - Flutter would add a third pathway language and React Native would bind mobile to the web stack. **Named costs:** iOS and Swift are not taught - consistent with the recorded trim landing on platform breadth, but students meet no Apple toolchain before Coventry; and single-platform depth is a bet on the anchor's own platform posture. Resourcing note: Android Studio runs on existing laboratory machines; no macOS fleet is required.

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | The mobile platform: Android application structure; activities and the lifecycle; Kotlin for Java programmers (the managed transition) | 9 |
| U2 | UI construction for mobile: layouts and components; event handling; navigation; platform UI conventions and responsive behaviour on device | 12 |
| U3 | Introductory design patterns in the mobile context: separation of concerns; adapter and observer patterns in interface work | 9 |
| U4 | Database integration: local persistence within the mobile application (SQL fluency assumed) | 9 |
| U5 | RESTful API consumption: networking on device; parsing and presenting remote data (consumption level) | 9 |
| | **Total lecture hours** | **48** |

Sessions run as 3-hour blocks (16 sessions); the laboratory-heavy allocation carries one application build accumulating across U1-U5.

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
| CW-I-Home | Mobile application build: an individually built, working application with database integration and API consumption, demonstrated on device or emulator | Individual; take-home; graded; oral vehicle: Presentation | LO1, LO2, LO3, LO4 | 65 |
| CW-I-Class | Supervised practical class test under open-resource conditions: timed build and modification tasks in the platform environment | Individual; in-class; graded; oral vehicle: None | LO1, LO3 | 35 |

No examination is carried by design: the assessed capability is demonstrated build competence on the platform, and the supervised in-class practical test is the integrity anchor for individual capability. Weights sum to 100. Reassessment is by failed component. Academic-integrity and generative-AI expectations follow School policy; the demonstration of the built application and the supervised test anchor individual authorship.

## 6. Resources, Staff and Governance

### Indicative Reading

- Stewart, K., Marsicano, K., Gardner, B. and Phillips, B., *Android Programming: The Big Nerd Ranch Guide*, 5th edition, Big Nerd Ranch / Pearson. (Kotlin-dependent text.)
- Griffiths, D. and Griffiths, D., *Head First Android Development*, 3rd edition, O'Reilly Media. (Kotlin-dependent text.)
- Android Developers documentation (Google), the module's named online reference for platform and Kotlin guidance; confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from mobile application development expertise; generic delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | SE descriptor thread |
| 1.1 | 21 Jul 2026 | U2 event-handling naming; LO3 "event-driven" wording (pre-ratification edit, composition-analysis finding) | SE descriptor thread |
| 1.2 | 21 Jul 2026 | Working-language basis aligned to V14 pathway instantiation; no boundary, LO, hour or weight change | SE descriptor thread |
