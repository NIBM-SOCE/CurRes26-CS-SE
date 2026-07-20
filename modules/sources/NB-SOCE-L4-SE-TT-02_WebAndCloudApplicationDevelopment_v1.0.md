# Module Descriptor - Web and Cloud Application Development

**Code:** NB-SOCE-L4-SE-TT-02  ·  **Tier:** Pathway (SE)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NIBM_SOCE_SE_ModuleRecords_Y12 v2.3 (carries CR-SE-02, adopted at V12); 00_Master_Decisions.md v2.5 (V5 as amended; V13 working-languages register); 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1

> **Items requiring confirmation at review:** (1) the learning-outcome set (canonical device: authored here from the record v2.3 stubs with the Level 4 register and the analytical-outcome cluster rule applied; ratified into the record set on confirmation); (2) assessment attributes and weightings at sign-off, including the no-examination stance stated in Section 5; (3) syllabus hour allocations - this is the recorded densest module of the year and the density discipline must hold at review (no additions without a matching removal); (4) indicative reading and the cloud platform naming (platform-neutral here; any platform naming lands at teaching-plan stage); (5) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-SE-TT-02 |
| Module title | Web and Cloud Application Development |
| Scope / type | Pathway: CS(SE)  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  4 credits  ·  200 notional hours |
| Feeder targets (named) | NB6007CEM Web API Development (the flagship proximate feeder - Node.js, REST, asynchronous JavaScript, API security; now also deployment, re-attached from the dissolved Cloud and IoT module); NB6034CEM Software Engineering 2 (microservice awareness through the API-design lens; DevOps pipelines - re-attached); NB6033CEM Mobile Application Development 2 (RESTful API consumption); NB5004CEM Cyber Security (web authentication and HTTPS in application context). Both re-attached claims verified at 4 credits: they are context-supply claims sitting beside the API content that contextualises them. |
| Prerequisites | Web Application Foundations (Year 1 tier); Programming Concepts |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile; laboratory-heavy |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

The module is the second tier of the CS(SE) web vertical and the pathway's flagship applied build: server-side JavaScript and Node.js, REST API design, asynchronous programming, API security, single-page application delivery, and - the absorbed scope that names the module - cloud deployment and operation of what is built, through a continuous-integration and delivery pipeline. The working language is JavaScript, client and server (V13). It holds the second DevOps home (the delivery pipeline, paired with Enterprise Application Development's integration home) and one of the two secure-coding homes feeding the Level 6 secure-development destination. The scope limits are honest and load-bearing: cloud enters as a delivery target for applications, not as infrastructure - provisioning and operating infrastructure is NEC territory under the hard boundary quoted below - and cloud-native architecture as standalone conceptual content was trimmed in the merge, the recorded cost of absorbing cloud without credit movement. This is the densest module in the year at 66 lecture hours; the merge is defensible because deployment and DevOps were already inside this boundary, and cloud deepens an existing strand rather than adding a foreign one.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** server-side JavaScript and Node.js; REST API design and implementation; asynchronous programming; API security and authentication; single-page application delivery; cloud deployment and operation of web applications and APIs (cloud as delivery target - the absorbed scope); the DevOps delivery pipeline (continuous integration and delivery - consolidated as the second DevOps home); microservice awareness via API design; a secure-coding thread (web application security, input validation, injection and XSS awareness - one of the two secure-coding homes feeding NB6035CEM).
>
> **Does NOT cover:** web foundations (Web Application Foundations, Year 1); enterprise persistence build (Enterprise Application Development); cloud-native architecture as standalone conceptual content (trimmed in the merge - the honest scope cost); cloud infrastructure provisioning and operations (NEC's Cloud Technologies and infrastructure modules - standing flag 6 hard boundary attaches HERE: SE deploys applications to cloud, NEC provisions and operates infrastructure); device backends (IoT Application Development); deep security engineering (NB5004CEM at Coventry).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Design and implement a RESTful API using Node.js, analysing a problem domain into a resource model | Analyse / Apply (Bloom); K-SAM 1, 2 |
| LO2 | Build an interactive single-page application that consumes the API through asynchronous programming | Apply (Bloom); K-SAM 2, 7 |
| LO3 | Implement API security and authentication, applying secure-coding practice against common web vulnerabilities | Apply (Bloom); K-SAM 2, 10 |
| LO4 | Deploy and operate the application on a cloud platform through a continuous-integration and delivery pipeline | Apply (Bloom); K-SAM 2, 7 |

**LO provenance note (canonical device):** the set above is authored from the record v2.3 indicative stubs. LO1 absorbs the analytical dimension required by the Level 4 cluster rule ("analysing a problem domain into a resource model" per the Level 4 descriptor row 1); LO2 makes the asynchronous element explicit; LO3 names the secure-coding practice from the boundary text; LO4 renders the stub's pipeline abbreviation in full words. No verb exceeds the Level 4 cognitive ladder; no K-SAM category 7 defence is required. On ratification the carrying register inherits this set verbatim; SLQF-04 for this module closes at that point.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Web Application Foundations | The tier boundary: "web foundations (Web Application Foundations, Year 1)" - everything demanding sits here by design |
| NEC pathway (Cloud Technologies and infrastructure modules) | The hard cloud boundary, quoted: "cloud infrastructure provisioning and operations (NEC's Cloud Technologies and infrastructure modules - standing flag 6 hard boundary attaches HERE: SE deploys applications to cloud, NEC provisions and operates infrastructure)" |
| Enterprise Application Development | "enterprise persistence build (Enterprise Application Development)"; the DevOps pairing - delivery pipeline here, integration home there |
| IoT Application Development | "device backends (IoT Application Development)" - API patterns taught here are consumed there |
| Mobile Application Development I | API-consumption mechanics taught here are drawn on in the mobile build |
| Software Quality and Testing | The pipeline here runs delivery; testing method and quality assurance depth are owned there |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Server-side JavaScript and Node.js: the runtime and event loop; modules and package management; the server tier of the web vertical | 9 |
| U2 | Asynchronous programming: callbacks, promises and async/await; error handling in asynchronous code | 9 |
| U3 | REST API design and implementation: resources and routing; HTTP semantics; framework-based API construction; microservice awareness through the API-design lens | 12 |
| U4 | API security and authentication: sessions and token-based authentication; HTTPS in application context; secure coding - input validation, injection and XSS awareness | 12 |
| U5 | Single-page application delivery: consuming the API from an interactive client; state and rendering at applied level | 9 |
| U6 | Cloud deployment and operation: cloud as delivery target; environments, configuration and operation of the deployed application | 9 |
| U7 | The DevOps delivery pipeline: continuous integration and delivery for web applications and APIs | 6 |
| | **Total lecture hours** | **66** |

**Language note (V13):** the working language is JavaScript, client and server - the second tier of the vertical opened by Web Application Foundations. The cloud platform is not named in this descriptor; any platform naming lands at teaching-plan stage. C/C++ exposure is not extended here.

Sessions run as 3-hour blocks (22 sessions); the laboratory-heavy allocation carries one full-stack build that accumulates across U1-U7 and is the assessed artefact. The density note stands: specification and review must hold the discipline of this syllabus - additions require matching removals.

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
| CW-I-Home | Full-stack staged build: a secure, API-served single-page application deployed to a cloud platform through a continuous-integration and delivery pipeline, submitted with pipeline history | Individual; take-home; graded; oral vehicle: Viva-defence | LO1, LO2, LO3, LO4 | 70 |
| CW-I-Class | Supervised applied exercise under open-resource conditions: asynchronous-programming and API-security tasks | Individual; in-class; graded; oral vehicle: None | LO2, LO3 | 30 |

No examination is carried by design: the assessed capability is the end-to-end applied build the module exists to produce; assessment integrity is anchored by the mandatory Viva-defence, the pipeline history as authorship evidence, and the supervised in-class component. Weights sum to 100. Reassessment is by failed component. Academic-integrity and generative-AI expectations follow School policy.

## 6. Resources, Staff and Governance

### Indicative Reading

- Brown, E., *Web Development with Node and Express*, 2nd edition, O'Reilly Media. (JavaScript- and Node.js-dependent text.)
- Cantelon, M., Harter, M., Holowaychuk, T. J. and Rajlich, N., *Node.js in Action*, 2nd edition, Manning.
- OWASP Foundation, *OWASP Top Ten*, the module's named online reference for the secure-coding strand; confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from web, API and cloud application-development expertise, distinct from NEC infrastructure delivery; generic delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | SE descriptor thread |
