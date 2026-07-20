# Module Descriptor - IoT Application Development

**Code:** NB-SOCE-L4-SE-TT-06  ·  **Tier:** Pathway (SE)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NIBM_SOCE_SE_ModuleRecords_Y12 v2.3 (carries CR-SE-02, adopted at V12); v8.1 Phase 2 Register v1.0 (D1 Exception Register, Section 7); 00_Master_Decisions.md v2.5 (V5 as amended; V13); 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1

> **Items requiring confirmation at review:** (1) the learning-outcome set (canonical device: authored here from the record v2.3 stubs; ratified into the record set on confirmation); (2) the D1 exception restatement in Section 2 (the 2-credit standalone justification; watch condition: same review class as AI-Enabled Application Development); (3) assessment attributes and weightings at sign-off, including the no-examination stance; (4) syllabus hour allocations and any laboratory-weighted shift within the A-2 adjustment rule; (5) indicative reading; (6) staffing names.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-SE-TT-06 |
| Module title | IoT Application Development |
| Scope / type | Pathway: CS(SE)  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  2 credits  ·  100 notional hours |
| Feeder targets (named) | Soft connections only - NB6007CEM Web API Development (device API design); NB6020CEM Project and Capstone Project (IoT themes, now DELD-resourced with laboratory kit). This module carries the connected-systems D1 employability element standalone (standing flag 5, updated); admitted with written rationale and scoped to remain mission-consistent (software, per the V5 SE mission ruling). |
| Prerequisites | Digital Electronics and Logic Design (hardware literacy beneath the software - the named DELD to IoT chain, the structural I-016 answer within SE); Web Application Foundations; Programming Concepts; Data Models and Management Systems (device-data handling) |
| Delivery mode | Session-based: 3-hour blocks (V10); 10 lecture sessions plus tutorials, practicals and demonstration per the hours profile; laboratory-oriented |
| Hours profile | Taught 2-credit (A-2), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

The module builds connected-device application capability for the CS(SE) vertical: the software backends that devices talk to - device-facing APIs, device-data ingestion and handling, and integration with cloud services. It sits deliberately on the software side of the connected-systems territory, with hardware literacy supplied beneath it by Digital Electronics and Logic Design; with that Tier 1 foundation in place, the applied answer to the consultation demand for connected-systems provision is structurally complete - foundations common, application pathway.

**D1 exception restatement (required by the register):** this module carries no hard Coventry feeder; its connections are soft (device API design toward the Level 6 API destination; IoT themes in project work). It is a documented D1 employability exception, admitted with written rationale, and its 2-credit standalone scope is justified as follows: the split that produced it moved cloud territory into Web and Cloud Application Development where it deepens an existing strand, leaving a genuinely device-specific software core - device-facing APIs, device-data handling, cloud-service consumption - that is too distinct to fold into the web vertical without loss, and too small to hold 3 credits honestly. Its watch condition stands: the same external-review class as AI-Enabled Application Development. The scope limits are quoted below; this module consumes cloud territory, it does not re-teach it.

### Specification Boundary (from the record set - QUOTED, never edited)

> **Covers:** connected-device application backends; APIs to and from devices; device-data ingestion and handling; integration with cloud services (consuming Web and Cloud Application Development's territory, not re-teaching it).
>
> **Does NOT cover:** electronics and embedded-hardware programming (DELD owns the foundations; embedded depth remains out of scope per standing flag 9); device and network hardware (NEC); cloud deployment mechanics (Web and Cloud Application Development).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Build a connected-device application backend and its device-facing API | Apply (Bloom); K-SAM 2, 7 |
| LO2 | Ingest, store and process device data, analysing its flow from device to application | Analyse / Apply (Bloom); K-SAM 1, 2 |
| LO3 | Integrate the device backend with cloud services | Apply (Bloom); K-SAM 2 |

**LO provenance note (canonical device):** the set above is authored from the record v2.3 indicative stubs; LO2 absorbs the analytical outcome required by the Level 4 cluster rule ("analysing its flow from device to application", per the Level 4 descriptor row 1). No verb exceeds the Level 4 cognitive ladder; no K-SAM category 7 defence is required. On ratification the carrying register inherits this set verbatim; SLQF-04 for this module closes at that point.

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Digital Electronics and Logic Design | The foundations chain, quoted: "electronics and embedded-hardware programming (DELD owns the foundations; embedded depth remains out of scope per standing flag 9)" - hardware literacy beneath, software application above |
| NEC pathway | "device and network hardware (NEC)" - devices as software endpoints here, device and network hardware there |
| Web and Cloud Application Development | "integration with cloud services (consuming Web and Cloud Application Development's territory, not re-teaching it)" and "cloud deployment mechanics (Web and Cloud Application Development)" - consumption here, mechanics there |
| Data Models and Management Systems | Prerequisite: device-data handling assumes the taught SQL practice |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Connected systems: IoT application architecture; devices, gateways and backends; where the software boundary sits above the hardware foundations | 6 |
| U2 | Device-facing APIs: applied protocol awareness (HTTP and MQTT at consumer level); designing APIs to and from devices | 6 |
| U3 | Device-data ingestion and handling: receiving, validating and storing device data (SQL fluency assumed) | 6 |
| U4 | Processing and presenting device data: aggregation over device streams; presenting device state at applied level | 6 |
| U5 | Cloud-service integration: consuming cloud services from the device backend (deployment mechanics owned elsewhere) | 6 |
| | **Total lecture hours** | **30** |

**Language note (V13):** backend and API work is conducted in JavaScript with Node.js at applied level, within the pathway's JavaScript client-and-server posture; this applies the working-languages register, it does not extend it. C/C++ exposure is not extended here; device-side code is not taught.

Sessions run as 3-hour blocks (10 sessions); the practical allocation is laboratory-oriented and may shift within the A-2 adjustment rule at confirmation.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 30 |
| Tutorials | 9 |
| Practicals | 12 |
| In-class assignments | 6 |
| Demonstration | 3 |
| Self-guided study | 40 |
| **Total** | **100** |

## 5. Assessment

Components per the Assessment Component Taxonomy; weightings confirmed at specification sign-off.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Working device-backend build: a backend receiving, storing and presenting data from a simulated or kit device, integrated with a cloud service | Individual; take-home; graded; oral vehicle: Presentation | LO1, LO2, LO3 | 70 |
| CW-I-Class | Supervised applied exercise under open-resource conditions: device-data handling tasks | Individual; in-class; graded; oral vehicle: None | LO2 | 30 |

No examination is carried by design: at 2 credits the assessed capability is a single coherent applied build, and the presentation of the working backend plus the supervised in-class component anchor integrity and authorship. Weights sum to 100. Reassessment is by failed component. Academic-integrity and generative-AI expectations follow School policy.

## 6. Resources, Staff and Governance

### Indicative Reading

- Guinard, D. and Trifa, V., *Building the Web of Things*, Manning. (JavaScript- and Node.js-dependent text.)
- McEwen, A. and Cassimally, H., *Designing the Internet of Things*, Wiley.
- Laboratory kit documentation (the DELD-resourced kit), named as School-provided material; confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from connected-systems application-development expertise, distinct from NEC infrastructure delivery and from DELD electronics delivery; generic delivery is non-compliant.

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | SE descriptor thread |
