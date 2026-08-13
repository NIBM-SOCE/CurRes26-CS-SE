# CurRes26 - Pathway: Computer Science with Software Engineering

Governance repository for the Years 1 and 2 module descriptors of the Computer Science with Software Engineering pathway, produced under NIBM's School of Computing and Engineering (SOCE) curriculum restructuring initiative, CurRes26.

This repository holds the governance-ready module descriptors for the Software Engineering (SE) pathway, together with the institution-wide common modules shared across the programme. SE is one of four pathways in the restructured BSc programme; the others (Computer Science with Artificial Intelligence and Data Science, Information Technology for Business, and Network Engineering and Cybersecurity) are governed and versioned separately.

---

## 1. Programme Context

The programme is delivered in two stages:

- **Years 1 and 2** are governed by NIBM under the Sri Lanka Qualifications Framework (SLQF). This is the scope of this repository.
- **Years 3 and 4** are delivered in partnership with Coventry University under the UK Framework for Higher Education Qualifications (FHEQ), leading to a BSc (Hons) award. Years 3 and 4 are outside this repository; they are referenced here only for continuity.

## 2. Qualification Structure

| Programme stage | SLQF award | FHEQ (comparability, reference only) | NVQ target | Award title |
|---|---|---|---|---|
| Year 1 (exit) | Diploma level | Level 4 | NVQ Level 5 (target) | Diploma in Computer Science with Software Engineering |
| Year 2 (exit) | Higher Diploma level | Level 5 | NVQ Level 6 (target) | Higher National Diploma in Computer Science with Software Engineering |
| Years 3-4 (Coventry) | Bachelors Honours level | Levels 5-6 | n/a | BSc (Hons) Computer Science with Software Engineering |

The FHEQ column is carried for comparability and reference only. FHEQ is a holistic framework operating at programme and award level; it is not applied module by module to the NIBM-delivered years, where SLQF is the binding framework. "Higher National Diploma" is the award-certificate term and reflects TVEC-side vocabulary; SLQF itself uses "Higher Diploma" for the same level. UK usage of "HND" denotes a qualification of a defined size and character under FHEQ, and no equivalence to it is asserted here: the column states a comparison, not a claim. Final exit-certificate wording is being settled as part of exit-award finalisation; the titles above are the working form.

**TVEC accreditation:** TVEC accreditation is being actively pursued and has not yet been granted. The NVQ-level targets above, and any other TVEC/NVQ-facing mappings referenced from this programme, are targets that may be adjusted once TVEC confirms its specific requirements. SLQF conventions are binding now, independently of that outcome. Any exit-award or accreditation language should carry this caveat until TVEC's requirements are final.

## 3. Credit and Hours Convention

- **1 credit = 50 notional learning hours.** Industrial Training is the one exception, at 1 credit = 100 hours.
- **Delivery follows the institute's 3-hour session pattern.** Lecture hours are fixed by credit weight: 48 hours (16 sessions) for a 3-credit taught module, 66 hours (22 sessions) for a 4-credit module, and 30 hours (10 sessions) for a 2-credit module. All other timetabled components (tutorials, practicals, laboratory work, in-class assignments, demonstrations) are set in multiples of three hours.
- **Self-guided study always carries the largest share** of a taught module's notional hours; this holds across every credit weight.
- CREST, the Year 2 entrepreneurship component, is delivered on the skills-module hours pattern but does not count toward award credit totals; it is a mandatory pass/fail component, not a credit-bearing one.

## 4. Programme Architecture - CS(SE)

### Year 1 - Diploma Stage

<sub>37 credits · 1,850 notional hours</sub>

| Module group | Modules | Credits |
|---|---|---|
| Institution-wide common | Fundamentals of Computing, Mathematical Thinking, Algorithmic Thinking, Digital Electronics and Logic Design | 14 |
| Cluster common | Programming Concepts, Data Models and Management Systems | 8 |
| Pathway (SE) | Software Engineering and Systems Analysis, Software Architecture Foundations, Web Application Foundations | 10 |
| Integrative Skills | Effective Communication Skills I, Creative Project | 5 |
| Exit Block (Diploma exit only) | Industry Horizons, Professional Practice Foundations | 4 |

The exit block applies only to students exiting the programme at Diploma level. Including it, the Diploma exit stands at **13 modules, 41 credits**.

### Year 2 - Higher Diploma Stage

<sub>39 credits · 2,200 notional hours</sub>

| Module group | Modules | Credits |
|---|---|---|
| Cluster common | Programming, Data Structures and Algorithms I | 3 |
| Pathway (SE) | Enterprise Application Development, Web and Cloud Application Development, Mobile Application Development I, Software Quality and Testing, User Experience and Interaction Design, IoT Application Development, AI-Enabled Application Development, Business and Project Management Practice, Capstone Project, Industrial Training | 34 |
| Integrative Skills | Entrepreneurship, Creativity and Innovation (CREST, non-credit), Effective Communication Skills II | 2 |
| Exit Block (HND exit only) | Professional Standing and Career Strategy, Ethics and Responsibility in Computing Practice | 4 |

<sub>Industrial Training is credited at 100 notional hours per credit rather than the standard 50, which is why 2,200 notional hours runs above the simple 39 × 50.</sub>

The exit block applies only to students exiting the programme at Higher National Diploma level. Including it, the HND exit stands at **15 modules, 43 credits**.

### Why Year 2 Is Shaped This Way

Year 2's taught set was built to a clear brief, worth explaining rather than just listing:

- **Cloud is taught as a delivery skill inside Web and Cloud Application Development.** Students learn to build, deploy and operate a web application end to end, so cloud arrives as the natural completion of work they already own rather than as a separate topic studied in isolation. The discipline held here is "cloud as delivery target, not topic."
- **AI-Enabled Application Development builds a genuinely valuable, in-demand skill: integrating AI capabilities into real software.** Students learn to bring models, APIs and AI services into working applications, complementing rather than duplicating the AI&DS pathway, which owns model-building and theory depth.
- **IoT Application Development gives students the applied skill of building connected-device backends, APIs and data integrations.** It works as a focused, software-scoped module precisely because hardware literacy is already established in Digital Electronics and Logic Design, so the module concentrates fully on the software side of connected devices.
- **Business and Project Management Practice restores dedicated, credit-bearing project-management and business content** to the Higher National Diploma profile, giving students the delivery, planning and commercial skills that employers expect alongside technical capability.
- **Software Quality and Testing and User Experience and Interaction Design round out the professional profile.** Between them students gain the testing discipline and the user-centred design judgement that separate a working build from a product fit to ship.

### Working Languages

Language choices across the pathway are deliberate and sequenced rather than left to individual modules:

| Strand | Working language | Modules |
|---|---|---|
| Core programming spine | Java | Programming Concepts; Programming, Data Structures and Algorithms I; Enterprise Application Development |
| Web and connected devices | JavaScript (client and server, with Node) | Web Application Foundations; Web and Cloud Application Development; IoT Application Development |
| Native mobile | Kotlin on Android | Mobile Application Development I |
| Applied AI integration | Java or JavaScript, per application context | AI-Enabled Application Development |

Two points of governance interest. First, Programming Concepts and Programming, Data Structures and Algorithms I are shared cluster modules whose working language is the single parameter that varies by pathway: SE runs them in Java, and the AI&DS pathway runs them in Python. Title, code, credits, boundary, learning outcomes, syllabus structure, hour allocations and assessment structure are identical across both instantiations, and assessment runs from a common specification with language-equivalent task banks moderated across pathways. Second, Kotlin was chosen for mobile because it is JVM-based and Java-interoperable, making the transition from the Java spine the cheapest available and teachable within the module; the alternative of a cross-platform framework would either have introduced a third language or bound mobile work to the web stack.

### Years 3 and 4

Progression continues at Coventry University under FHEQ Levels 5 and 6, leading to a BSc (Hons) in Computer Science with Software Engineering, at 240 credits across the full four-year programme. Years 3 and 4 module descriptors are Coventry's and are not held in this repository.

## 5. Module Descriptors

**Shared modules.** The institution-wide common modules, the cluster commons, the Integrative Skills modules and the exit-block modules are delivered to more than one pathway and their specifications are held in common. No single pathway may vary a shared module's boundary, learning outcomes or assessment; changes require the agreement of every pathway that delivers it. These descriptors are maintained centrally and published on the common-modules page, which always carries the current version.

Each row links to the governance descriptor: the polished, review-ready module descriptor document. These are the authoritative version of each module's identity, learning outcomes, curriculum, assessment and staffing arrangement.

The four Tier 1 commons, the cluster commons, the Integrative Skills modules and the exit-block modules are shared across pathways and maintained here as the central set; the other pathway repositories link to this page for them.

### Year 1 - Diploma Stage

<sub>37 credits · 1,850 notional hours</sub>

| Code | Module | Type | Credits | Descriptor |
|---|---|---|---|---|
| NB-SOCE-L3-CM-TT-01 | Fundamentals of Computing | Institution-wide common | 4 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CM-TT-01_FundamentalsOfComputing_Gov_v1.2.docx) |
| NB-SOCE-L3-CM-TT-02 | Mathematical Thinking | Institution-wide common | 4 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CM-TT-02_MathematicalThinking_Gov_v1.2.docx) |
| NB-SOCE-L3-CM-TT-03 | Algorithmic Thinking | Institution-wide common | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CM-TT-03_AlgorithmicThinking_Gov_v1.2.docx) |
| NB-SOCE-L3-CM-TT-04 | Digital Electronics and Logic Design | Institution-wide common | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CM-TT-04_DigitalElectronicsAndLogicDesign_Gov_v1.2.docx) |
| NB-SOCE-L3-CC-TT-01 | Programming Concepts | Cluster common | 4 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CC-TT-01_ProgrammingConcepts_Gov_v1.4.docx) |
| NB-SOCE-L3-CC-TT-02 | Data Models and Management Systems | Cluster common | 4 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CC-TT-02_DataModelsAndManagementSystems_Gov_v1.2.docx) |
| NB-SOCE-L3-SE-TT-01 | Software Engineering and Systems Analysis | Pathway (SE) | 4 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-SE-TT-01_SoftwareEngineeringAndSystemsAnalysis_Gov_v1.0.docx) |
| NB-SOCE-L3-SE-TT-02 | Software Architecture Foundations | Pathway (SE) | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-SE-TT-02_SoftwareArchitectureFoundations_Gov_v1.0.docx) |
| NB-SOCE-L3-SE-TT-03 | Web Application Foundations | Pathway (SE) | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-SE-TT-03_WebApplicationFoundations_Gov_v1.1.docx) |
| NB-SOCE-L3-CM-IS-01 | Effective Communication Skills I | Integrative Skills | 2 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CM-IS-01_EffectiveCommunicationSkillsI_Gov_v1.1.docx) |
| NB-SOCE-L3-CM-IS-02 | Creative Project | Integrative Skills | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CM-IS-02_CreativeProject_Gov_v1.1.docx) |
| NB-SOCE-L3-CM-IS-03 | Industry Horizons | Exit Block (Diploma) | 2 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CM-IS-03_IndustryHorizons_Gov_v1.1.docx) |
| NB-SOCE-L3-CM-IS-04 | Professional Practice Foundations | Exit Block (Diploma) | 2 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L3-Year1-Diploma/NB-SOCE-L3-CM-IS-04_ProfessionalPracticeFoundations_Gov_v1.1.docx) |

### Year 2 - Higher Diploma Stage

<sub>39 credits · 2,200 notional hours</sub>

| Code | Module | Type | Credits | Descriptor |
|---|---|---|---|---|
| NB-SOCE-L4-CC-TT-01 | Programming, Data Structures and Algorithms I | Cluster common | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-CC-TT-01_PDSA_I_Gov_v1.4.docx) |
| NB-SOCE-L4-SE-TT-01 | Enterprise Application Development | Pathway (SE) | 4 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-TT-01_EnterpriseApplicationDevelopment_Gov_v1.1.docx) |
| NB-SOCE-L4-SE-TT-02 | Web and Cloud Application Development | Pathway (SE) | 4 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-TT-02_WebAndCloudApplicationDevelopment_Gov_v1.1.docx) |
| NB-SOCE-L4-SE-TT-03 | Mobile Application Development I | Pathway (SE) | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-TT-03_MobileApplicationDevelopmentI_Gov_v1.2.docx) |
| NB-SOCE-L4-SE-TT-04 | Software Quality and Testing | Pathway (SE) | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-TT-04_SoftwareQualityAndTesting_Gov_v1.1.docx) |
| NB-SOCE-L4-SE-TT-05 | User Experience and Interaction Design | Pathway (SE) | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-TT-05_UserExperienceAndInteractionDesign_Gov_v1.0.docx) |
| NB-SOCE-L4-SE-TT-06 | IoT Application Development | Pathway (SE) | 2 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-TT-06_IoTApplicationDevelopment_Gov_v1.1.docx) |
| NB-SOCE-L4-SE-TT-07 | AI-Enabled Application Development | Pathway (SE) | 3 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-TT-07_AIEnabledApplicationDevelopment_Gov_v1.1.docx) |
| NB-SOCE-L4-SE-TT-08 | Business and Project Management Practice | Pathway (SE) | 2 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-TT-08_BusinessAndProjectManagementPractice_Gov_v1.0.docx) |
| NB-SOCE-L4-SE-SK-01 | Capstone Project | Pathway (SE) | 5 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-SK-01_CapstoneProject_Gov_v1.0.docx) |
| NB-SOCE-L4-SE-SK-02 | Industrial Training | Pathway (SE) | 5 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-SE-SK-02_IndustrialTraining_Gov_v1.0.docx) |
| NB-SOCE-L4-CM-IS-01 | Entrepreneurship, Creativity and Innovation (CREST) | Integrative Skills - non-credit, pass/fail | 0 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-CM-IS-01_CREST_Gov_v1.1.docx) |
| NB-SOCE-L4-CM-IS-02 | Effective Communication Skills II | Integrative Skills | 2 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-CM-IS-02_EffectiveCommunicationSkillsII_Gov_v1.1.docx) |
| NB-SOCE-L4-CM-IS-03 | Professional Standing and Career Strategy | Exit Block (HND) | 2 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-CM-IS-03_ProfessionalStandingAndCareerStrategy_Gov_v1.1.docx) |
| NB-SOCE-L4-CM-IS-04 | Ethics and Responsibility in Computing Practice | Exit Block (HND) | 2 | [Descriptor](https://nibm-soce.github.io/CurRes26-CS-SE/modules/L4-Year2-HigherDiploma/NB-SOCE-L4-CM-IS-04_EthicsAndResponsibilityInComputingPractice_Gov_v1.1.docx) |

### Recent Specification Changes

The shared modules below were re-issued on 13 August 2026. Anyone working from an earlier copy should replace it.

| Module | What changed |
|---|---|
| Programming Concepts | Object-oriented programming is now stated explicitly in the module's scope, outcomes and syllabus, taught as a way of organising a program rather than as syntax. Funded from within the module's existing lecture hours; credits unchanged. |
| Effective Communication Skills I | Communication within a team added as a fourth strand. |
| Effective Communication Skills II | Interpersonal communication, assertiveness and reflective practice restored alongside reporting and interview performance. Academic-writing and research-readiness preparation is owned by the Capstone Project and is stated as outside this module. |
| Creative Project | Delivered as a team-based build with an individually graded reflective component. Individual contribution is defined during planning and evidenced through a contribution log, so each student's own work is attributable. |
| Entrepreneurship, Creativity and Innovation | Scope held to opportunity identification, evaluation, value proposition and pitching. Business-model construction and intellectual-property content are outside the module. |

The four institution-wide commons, the cluster common, Programming, Data Structures and Algorithms I and the four exit-block modules were re-issued at the same time with no change to what is taught: their descriptors now quote the shared specification directly and carry SLQF category mapping for every learning outcome.

## 6. Feeder and Consumer Map

[Open the CS(SE) Feeder and Consumer Map](https://nibm-soce.github.io/CurRes26-CS-SE/map/NIBM_SOCE_SE_FeederConsumerMap_v8_1.html)

An interactive view of how Year 1 and Year 2 modules feed into each other and into the Years 3-4 Coventry modules, and which modules each one draws on in turn. It opens directly in the browser.

## 7. Repository Structure

```
CurRes26-CS-SE/
├── README.md
├── modules/
│   ├── L3-Year1-Diploma/          Governance descriptors, Year 1 (13 modules)
│   ├── L4-Year2-HigherDiploma/    Governance descriptors, Year 2 (15 modules)
│   └── sources/                   Working source files behind the descriptors above
└── map/
    └── NIBM_SOCE_SE_FeederConsumerMap_v8_1.html   Interactive feeder/consumer map for CS(SE)
```

The `modules/sources` directory holds the working markdown behind each descriptor and is not linked module-by-module above; it carries more internal drafting detail than the governance descriptors and is intended for the curriculum team rather than external readers.

## 8. Status and Conventions

Descriptors in this repository are issued as governance-ready drafts for review. Where a descriptor still has an open item (for example, a learning-outcome set, an assessment weighting or a staffing name awaiting confirmation), that is stated explicitly at the head of the descriptor itself. Documents follow UK English, Title Case module titles, and a table-first presentation throughout.
