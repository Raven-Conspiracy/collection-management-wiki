# PIR → SIR → EEI → SOR Decomposition

_Process › Requirements Decomposition_

---

> *"The PIR is the question. The EEI is what a sensor can actually see. The space between them is where collection managers earn their keep."*

This is the single most important workflow in collection management: turning a commander's vague but vital question into a discrete, observable thing a sensor can be tasked against.

## The Hierarchy (Joint, JP 2-01)

```
CCIR — Commander's Critical Information Requirement
  │
  ├── PIR — Priority Intelligence Requirement
  │     │  ("What is the commander betting decisions on?")
  │     │
  │     ▼
  │   SIR — Specific Information Requirement
  │     │  ("What specific information would answer the PIR?")
  │     │
  │     ▼
  │   EEI — Essential Element of Information
  │     │  ("What discrete, observable fact must be collected?")
  │     │
  │     ▼
  │   SOR — Specific Orders & Requests
  │        ("Sensor X, NAI Y, between time A and time B, looking for indicator Z.")
  │
  └── FFIR — Friendly Force Information Requirement
        (Same decomposition logic, friendly-side)
```

**Cross-service terminology:**

| Joint | Army (ATP 2-01) | Air Force (AFDP 2-0) | Navy/USMC |
|---|---|---|---|
| CCIR | CCIR | CCIR | CCIR |
| PIR | PIR | PIR | PIR |
| SIR | SIR (or Information Requirement, IR) | Same concept, sometimes implicit | Same |
| EEI | Indicator + SIR (Army merges concepts) | EEI | EEI |
| SOR | Specific Information Requirement → tasking | Collection Task | Tasking |

The Joint hierarchy is canonical at the JTF/CCMD level. Use service variants when working inside that service staff.

## What Makes a Good PIR

A PIR is a **question** that:

1. **Drives a decision.** If the answer doesn't change what the commander does, it's not a PIR — it's a "nice to know."
2. **Is answerable.** Don't write "Will Russia escalate to nuclear use?" — write "Are Russian SNF units conducting indicators 1–4 of nuclear readiness within the JOA?"
3. **Is time-bound.** Implicit or explicit LTIOV.
4. **Is collectable by the architecture available.** A PIR that requires sources you don't have is just a wish.
5. **Has a defined decision-maker.** Usually the commander, sometimes a specified subordinate.

**Bad PIR:** "What are Russian intentions?"
**Good PIR:** "Will the 20th Guards Combined Arms Army deploy from garrison to forward assembly area WEST within the next 72 hours, sufficient to enable offensive operations against [named avenue of approach]?"

## Decomposition Walkthrough

Let's take the good PIR above and grind it down to taskable SORs.

### Step 1 — Develop Indicators (per ATP 2-01.3 and JP 2-01)

> "An indicator is an item of information that reflects the intention or capability of an adversary to adopt or reject a course of action." — ATP 2-01.3

Brainstorm what observable things would have to be true for the PIR's "yes" or "no" answer.

For our example PIR, indicators of imminent deployment include:
- I-1: Forward deployment of bridging assets (PMP, MTU-72) to crossing sites
- I-2: Departure of motorized rifle units from garrison
- I-3: Forward arming and refueling point (FARP) preparation at FAA WEST
- I-4: Logistics surge — ammunition trains, POL convoys
- I-5: C2 displacement — division HQ jump CP forward
- I-6: EW unit activity at expected operating frequencies
- I-7: Family/dependent removal from garrison (HUMINT-detectable)
- I-8: Recall of personnel on leave (SIGINT-detectable via cell traffic)

### Step 2 — Develop SIRs

A **SIR** wraps each indicator (or group) into an information requirement statement.

> "A specific information requirement describes the information required to answer all or part of an intelligence requirement." — JP 2-01

- SIR-1: Determine the location, type, and quantity of bridging equipment in the 20 GdsCAA AOR. (covers I-1)
- SIR-2: Determine the readiness posture and movement of motorized rifle units assigned to 20 GdsCAA. (covers I-2, I-8)
- SIR-3: Determine the developmental status of forward assembly area WEST. (covers I-3, I-4)
- SIR-4: Identify forward displacement of division-level C2 nodes. (covers I-5)
- SIR-5: Identify EW unit activity at signatures associated with offensive ops. (covers I-6)

### Step 3 — Decompose to EEIs

Each SIR breaks down to multiple **EEIs** — the discrete, observable, tasked facts a sensor will go get. An EEI must satisfy the **SMART-O** test:

- **S**pecific — one fact, one observation
- **M**easurable — sensor can confirm/deny
- **A**ttributable — clear collector, clear PED path
- **R**elevant — ties back to the PIR via a SIR
- **T**ime-bound — has an LTIOV
- **O**bservable — there's a real signature/indicator a sensor can detect

**SIR-1 → EEI decomposition:**

| EEI ID | EEI | NAI | LTIOV | Best Sensor Mix |
|---|---|---|---|---|
| EEI-1.1 | Number and type of PMP pontoon bridge sections within 5km of Bridge Site ALPHA | NAI-101 | 12 JUN 0600Z | SAR (U-2/Triton) cued by EO commercial refresh |
| EEI-1.2 | Number and type of MTU-72 / MTU-90 bridgelayers within 10km of Crossing Sites BRAVO and CHARLIE | NAI-102, NAI-103 | 12 JUN 0600Z | EO/IR FMV (MQ-9) + SAR confirm |
| EEI-1.3 | Movement of bridging equipment on rail from depot DELTA toward forward sites | NAI-104 (rail line) | 11 JUN 1800Z | Commercial EO refresh + SIGINT rail traffic |
| EEI-1.4 | Forward-deployed engineer reconnaissance teams at crossing sites | NAI-101, NAI-102, NAI-103 | 12 JUN 0600Z | HUMINT + FMV |

**SIR-2 → EEI decomposition:**

| EEI ID | EEI | NAI | LTIOV | Best Sensor Mix |
|---|---|---|---|---|
| EEI-2.1 | Vehicle count and disposition at MRB garrison ECHO | NAI-201 | 11 JUN 2400Z | EO/IR FMV (MQ-9) or commercial EO |
| EEI-2.2 | Volume of cellular and military comms in/out of garrison ECHO | NAI-201 | Continuous | SIGINT (RC-135 V/W, PROPHET ground if available) |
| EEI-2.3 | Personnel recall traffic in garrison cellular network | Garrison ECHO | Continuous | SIGINT national-tactical |
| EEI-2.4 | Departure of armored columns on Route FOXTROT | NAI-202 (road) | 12 JUN 0600Z | GMTI (formerly JSTARS, now space/HALE substitutes) |

Continue for SIR-3, SIR-4, SIR-5. The decomposition table **is** the foundation of the [IC Matrix](../08-templates-and-formats/ic-matrix-template.md) / [ISR Sync Matrix](04-isr-synchronization-matrix.md).

### Step 4 — Generate SORs

An SOR turns each EEI into a tasked collection action. It includes:

- Sensor / platform identification
- NAI / TAI / geo-coordinates of collection point
- Time window (collection start, collection end, **LTIOV**)
- Indicator/signature to look for
- PED routing (where the data goes for exploitation)
- Reporting requirement (who gets the answer, in what format, by when)

**SOR Example for EEI-1.1:**

```
SOR ID:           SOR-2026-1106-0042
EEI ID:           EEI-1.1
Sensor:           U-2S, ASARS-2A mode, swath width X km
NAI:              NAI-101 (Bridge Site ALPHA, [coordinates])
Collection Start: 12 JUN 2026 0200Z
Collection End:   12 JUN 2026 0400Z
LTIOV:            12 JUN 2026 0600Z
Look For:         PMP pontoon bridge sections (signature library entry XYZ)
Cued By:          RC-135V/W ELINT pickup of engineer net activity (if detected)
PED Route:        AF DCGS-A site OFFUTT → 480 ISRW exploitation
Reporting:        SAR product + written assessment to JTF J-2 CM cell
                  via JWICS NLT 0530Z
Backup Sensor:    NGA commercial EO tasking via NTM channels if U-2 aborts
```

This is what gets transmitted to the COM cell (AOC ISRD for the U-2 task) for inclusion in the next ATO cycle.

## Layering: Cueing, Redundancy, Mix (ATP 2-01)

A good collection plan doesn't put one EEI on one sensor and hope. It **layers**:

- **Cueing** — Sensor A's detection triggers Sensor B's collection. Example: RC-135 SIGINT hit on engineer net cues U-2 SAR pass.
- **Redundancy** — Two or more sensors on the same EEI to mitigate weather, threat, or platform abort. Example: U-2 SAR + commercial SAR.
- **Mix** — Different INT disciplines on the same target to reduce deception risk and increase confidence. Example: EO/IR FMV + SAR + SIGINT + HUMINT all on the same crossing site.

Every EEI in your decomposition should have a cueing/redundancy/mix decision documented.

## Common Decomposition Failure Modes

| Failure | Fix |
|---|---|
| EEI is too abstract ("determine adversary intent at FAA WEST") | Re-decompose; intent is never an EEI, only inferred from observable indicators |
| EEI has no LTIOV | Add one; an EEI with no time bound is impossible to prioritize |
| EEI requires a sensor the architecture doesn't have | Either substitute, escalate via national-to-tactical, or document the gap as a [COLLECTION-REQUIREMENT] |
| Multiple EEIs all routed to the same sensor without deconfliction | Plan sensor time deliberately; layer with backups |
| EEI satisfaction never assessed | Build the assessment loop into the plan; close requirements explicitly |

## Templates

- [PIR Worksheet](../08-templates-and-formats/pir-worksheet.md)
- [EEI Worksheet](../08-templates-and-formats/eei-worksheet.md)
- [SOR Template](../08-templates-and-formats/sor-template.md)
- [IC Matrix Template](../08-templates-and-formats/ic-matrix-template.md)

## Sources

- [JP 2-01, Joint and National Intelligence Support to Military Operations](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [ATP 2-01, Planning Requirements and Assessing Collection](https://armypubs.army.mil/)
- [ATP 2-01.3, Intelligence Preparation of the Battlefield](https://armypubs.army.mil/)
- [FM 3-55, Information Collection](https://armypubs.army.mil/)
