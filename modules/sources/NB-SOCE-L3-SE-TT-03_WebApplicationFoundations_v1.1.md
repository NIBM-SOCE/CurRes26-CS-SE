# Module Descriptor - Web Application Foundations

**Code:** NB-SOCE-L3-SE-TT-03  ·  **Tier:** Pathway (SE)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.1  ·  **Date:** 21 Jul 2026
**Sources:** NIBM_SOCE_SE_ModuleRecords_Y12 v2.3; 00_Master_Decisions.md v2.6 (V13 working-languages register, as amended by V14 pathway instantiation); 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1

> **Items requiring confirmation at review:** (1) the learning-outcome set (canonical device: authored here from the record v2.3 stubs; ratified into the record set on confirmation); (2) assessment attributes and weightings at sign-off, including the no-examination stance stated in Section 5; (3) syllabus hour allocations, and any laboratory-weighted shift within the A-3 adjustment rule (the record flags this module as laboratory-heavy); (4) indicative reading; (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-SE-TT-03 |
| Module title | Web Application Foundations |
| Scope / type | Pathway: CS(SE)  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  3 credits  ·  150 notional hours |
| Feeder targets (named) | Web and Cloud Application Development (Year 2, the tiered continuation) and through it NB6007CEM Web API Development - claim VERIFIED at 3 credits: the demanding content (Node.js, REST, asynchronous programming, API security, cloud delivery) sits entirely in the Year 2 tier, which holds at 4 credits. Also supplies the client-server and HTTP context NB5004CEM Cyber Security assumes - jointly underwritten with Fundamentals of Computing's raised operational networks level (V3.1; the stage 1 co-supply declaration). |
| Prerequisites | Programming Concepts (general programming behind client-side scripting) |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

The module builds the first tier of the CS(SE) two-tier web vertical: how the web works as a client-server system over HTTP, and how a working client-side interface is built with HTML, CSS and introductory JavaScript. Its design intent is a gentler gradient into the demanding Year 2 continuation for a diverse cohort - a sequencing property preserved at 3 credits, since everything demanding (server-side JavaScript, REST, asynchronous programming, API security, cloud delivery) sits by boundary in the Year 2 tier. The scope limit is honest: the stage 1 trim cost 6 taught sessions of practice before that continuation; the recorded mitigation is structural - the Year 2 tier holds at 4 credits laboratory-heavy, and this module's A-3 delivery stays laboratory-weighted.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** HTTP and the client-server model; HTML and CSS; introductory JavaScript; the document object model. This is the first tier of the two-tier web vertical.
>
> **Does NOT cover:** server-side JavaScript, Node.js, REST API design, asynchronous programming, API security and cloud delivery (Web and Cloud Application Development, Year 2).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Explain the client-server model and the role of HTTP in the delivery of web applications | Understand (Bloom); K-SAM 1 |
| LO2 | Build a static web interface using semantic HTML and CSS | Apply (Bloom); K-SAM 2, 7 |
| LO3 | Add interactivity to a web interface using JavaScript and the document object model | Apply (Bloom); K-SAM 2, 7 |

**LO provenance note (canonical device):** the set above is authored from the record v2.3 indicative stubs with minimal wording change ("basic interactivity" rendered as "interactivity ... using JavaScript and the document object model"; "semantic" added to LO2 to name the taught practice). No verb exceeds the Level 3 cognitive ladder; no K-SAM category 7 defence is required. On ratification the carrying register inherits this set verbatim; SLQF-04 for this module closes at that point.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Web and Cloud Application Development (Year 2) | The tier boundary, quoted: "server-side JavaScript, Node.js, REST API design, asynchronous programming, API security and cloud delivery (Web and Cloud Application Development, Year 2)" |
| Fundamentals of Computing | Co-supply declaration: the client-server and HTTP context assumed at Level 5 security is jointly underwritten with FoC's raised operational networks level (V3.1) |
| Programming Concepts | Prerequisite: general programming behind client-side scripting; the working-language change from Java (the SE Year 1 instantiation of Programming Concepts, V14) to JavaScript is a taught transition, not an assumed one |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | The web as a system: the client-server model; HTTP requests and responses; URLs, browsers and servers in outline | 6 |
| U2 | HTML: document structure and semantics; forms; accessibility fundamentals | 9 |
| U3 | CSS: selectors and the cascade; box model; layout with flexbox and grid; responsive basics | 12 |
| U4 | Introductory JavaScript: values, control flow and functions in the browser context; the transition from Programming Concepts (Java under the SE pathway instantiation, V14) | 12 |
| U5 | The document object model: selecting and manipulating elements; events and interactivity; introductory debugging with browser developer tools | 9 |
| | **Total lecture hours** | **48** |

**Language note (V14):** the working language is JavaScript, client-side tier; the CS(SE) web vertical is JavaScript client and server, with the server tier owned by Web and Cloud Application Development. U4 explicitly manages the transition from Java (Programming Concepts under the SE pathway instantiation, V14). C/C++ exposure is not extended here.

Sessions run as 3-hour blocks (16 sessions); the practical and laboratory allocation carries the build thread, and the record's laboratory-heavy flag may shift hours within the A-3 adjustment rule at confirmation.

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
| CW-I-Home | Working web interface: an individually built, standards-conformant interface with styled layout and scripted interactivity | Individual; take-home; graded; oral vehicle: Presentation | LO2, LO3 | 60 |
| CW-I-Class | Supervised practical class test under open-resource conditions: timed build and modification tasks | Individual; in-class; graded; oral vehicle: None | LO1, LO2, LO3 | 40 |

No examination is carried by design: the assessed capability is demonstrated build competence, and the supervised in-class practical test is the integrity anchor for individual capability; per the taxonomy a supervised open-resource applied test is Coursework (in-class), not an Exam. Weights sum to 100. Reassessment is by failed component. Academic-integrity and generative-AI expectations follow School policy; the presentation of the built interface and the supervised test anchor individual authorship.

## 6. Resources, Staff and Governance

### Indicative Reading

- Duckett, J., *HTML and CSS: Design and Build Websites*, Wiley.
- Haverbeke, M., *Eloquent JavaScript*, 3rd edition, No Starch Press. (JavaScript-dependent text; the module's client-side scope uses Parts 1 and 2 only.)
- MDN Web Docs (Mozilla), the module's named online reference for HTML, CSS, JavaScript and DOM; confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from web development expertise; generic delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | SE descriptor thread |
| 1.1 | 21 Jul 2026 | Working-language framing aligned to V14 pathway instantiation (retires "cluster working language"); no boundary or hour change | SE descriptor thread |
