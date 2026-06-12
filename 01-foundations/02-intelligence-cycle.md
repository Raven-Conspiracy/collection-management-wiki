# The Intelligence Cycle and Where Collection Lives

_Foundations › Concept_

---

## The Six Categories of the Joint Intelligence Process (JP 2-0)

> "The six categories of intelligence operations are: planning and direction; collection; processing and exploitation; analysis and production; dissemination and integration; and evaluation and feedback." — JP 2-0, Ch. I, Sec. 3

| # | Category | What Happens | Who Drives |
|---|---|---|---|
| 1 | **Planning & Direction** | Requirements identified; CCIRs/PIRs developed; collection strategy framed | Commander, J-2, Staff |
| 2 | **Collection** | Sensors and collectors execute against the plan | Components, asset owners (COM) |
| 3 | **Processing & Exploitation** | Raw data converted to usable form (decode, decrypt, transcribe, geo-rectify) | DCGS, NSA, NGA, service PED |
| 4 | **Analysis & Production** | Information becomes intelligence; ACH, SATs, all-source fusion | All-source analysts, JIOC, JISE |
| 5 | **Dissemination & Integration** | Intel pushed/pulled to the consumer in time to act | J-2, J-6, integrated systems |
| 6 | **Evaluation & Feedback** | Did it answer the requirement? What's the gap? | Collection manager + analyst + commander |

The cycle is **not strictly sequential** — multiple categories run in parallel against multiple requirements simultaneously. But every requirement passes through all six.

## The Service Variants

Each service has its own framing layered on top of the joint cycle. Use the service framework when working inside that service; use the joint framework when working across.

### Army — Five-Step Intelligence Process (FM 2-0)
1. **Plan and Direct**
2. **Collect**
3. **Produce**
4. **Disseminate**
5. **Assess** (continuous)

### Air Force — PCPADE (AFDP 2-0)
- **P**lan
- **C**ollect
- **P**rocess
- **A**nalyze
- **D**isseminate
- **E**valuate

### Navy — Aligned to joint cycle, framed inside the MOC battle rhythm (NWP 2-01)

### Marine Corps — Joint cycle applied via MAGTF intelligence operations (MCWP 2-10)

## The Intelligence Cycle ↔ Targeting Cycle Interface

The intelligence cycle does not run in isolation. It pairs with the **six-phase joint targeting cycle (JP 3-60)** and the kinetic **F2T2EA** kill chain. This is the marriage that lets fires happen.

```
INTEL CYCLE                          TARGETING CYCLE (JP 3-60)
                                     
Planning & Direction ◄────────────► 1. End-State & Commander's Objectives
                              │
Collection           ◄────────┼───► 2. Target Development & Prioritization
                              │
Processing/Exploit   ◄────────┼───► 3. Capabilities Analysis
                              │
Analysis/Production  ◄────────┼───► 4. Commander's Decision & Force Assignment
                              │
Dissemination        ◄────────┼───► 5. Mission Planning & Force Execution
                              │
Evaluation/Feedback  ◄────────┴───► 6. Assessment  (BDA / CDE)
                                       │
                                       └──► feeds back to 1
```

### F2T2EA — The Dynamic Targeting Kill Chain

For time-sensitive targets the intel→fires interface compresses into:

| Phase | Intel Cycle Role |
|---|---|
| **Find** | Collection — initial detection |
| **Fix** | Processing/Exploitation — positive geo-fix |
| **Track** | Persistent collection + Analysis |
| **Target** | Analysis/Production — PID, CDE, weaponeering input |
| **Engage** | Dissemination — handoff to shooter |
| **Assess** | Evaluation — BDA, re-attack decision |

This compressed loop is why **collection management for time-sensitive targets** requires pre-coordinated NAI/TAI coverage, pre-cleared sensor cross-cueing, and pre-validated PED capacity. See [JP 3-60](../02-joint-doctrine/jp-3-60-joint-targeting.md) and [Sensor-to-Indicator Matching](../04-collection-process/05-sensor-to-indicator-matching.md).

## What Drives the Cycle: The Requirements Hierarchy

The cycle starts (and re-starts) with requirements. The hierarchy:

```
CCIR (Commander's Critical Information Requirement)
├── PIR (Priority Intelligence Requirement)
│   └── SIR (Specific Information Requirement)
│        └── EEI (Essential Element of Information)
│             └── SOR (Specific Orders & Requests) → tasked to a collector
└── FFIR (Friendly Force Information Requirement)
```

Each level decomposes the level above into something more observable and tasked. See [PIR → EEI Decomposition](../04-collection-process/02-pir-to-eei-decomposition.md) for a worked example.

## Sources

- [JP 2-0, Joint Intelligence](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [JP 3-60, Joint Targeting](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/3-0-Operations-Series/)
- [FM 2-0, Intelligence](https://armypubs.army.mil/)
- [AFDP 2-0, Intelligence](https://www.doctrine.af.mil/)
