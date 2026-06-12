# Authoring a Collection Plan

_Process › Planning_

---

> *"A collection plan that lives in someone's head is a collection wish. Write it down or it doesn't exist."*

The **collection plan** is the master working document of the CRM cell. It captures every validated PIR, its decomposition to EEIs, the sensor mix and tasking against each, the LTIOV, the PED routing, and the assessment status. It is a living document, updated continuously.

## What It Is — and What It Isn't

The collection plan is **not** the same as:

- **Collection Strategy** — the higher-level concept of how collection will support the operation. Strategy is paragraphs of intent; the plan is rows of execution.
- **ISR Synchronization Matrix** / **IC Matrix** — the time-phased visualization of the plan. The matrix is a **view** of the plan, not a replacement.
- **JIPCL** — the joint-level prioritized list of validated requirements. JIPCL feeds the plan; the plan operationalizes JIPCL inside the JOA.
- **ATO ISR Annex / Naval Tasking Order / IC Tasking Order** — the COM-side execution document. These are downstream products derived from the plan.

## Minimum Required Contents (per JP 2-01)

A complete collection plan contains, at minimum:

1. **Reference and basis** — what operation, what OPORD, what commander, what CCIR/PIR set
2. **Collection strategy summary** — high-level intent paragraph
3. **Validated requirements list** — every PIR/SIR/EEI active, with priority
4. **Sensor / capability inventory** — what's available to the JOA (organic + apportioned + national)
5. **Sensor-to-EEI mapping** — the core table; every EEI mapped to one or more sensors
6. **Time-phasing** — when each EEI is collected against; LTIOV per EEI
7. **NAI/TAI overlay reference** — geographic anchor (separate map product)
8. **PED routing** — where collected data goes for exploitation
9. **Reporting requirements** — who gets the answer, in what format, by when
10. **Assessment / satisfaction tracking** — current status per EEI
11. **Re-tasking / dynamic event procedures** — pre-coordinated authorities for TSTs
12. **External requests / RFIs out** — what you're asking national or other components for
13. **Inbound RFIs and disposition** — what others have asked you for

## Structure (Recommended Format)

The collection plan in practice is usually a **spreadsheet or database** with multiple views. The canonical row structure:

| Field | Example |
|---|---|
| Plan ID | CP-OPERATION-NAME-2026-001 |
| Requirement Source | PIR-1, JIPCL P1 |
| PIR | Will 20 GdsCAA move to FAA WEST in 72hrs? |
| SIR | SIR-1: Bridging equipment posture |
| EEI ID | EEI-1.1 |
| EEI Text | PMP pontoon bridge sections within 5km of Bridge Site ALPHA |
| NAI | NAI-101 |
| Priority | P1 |
| LTIOV | 12 JUN 0600Z |
| Sensor Primary | U-2S ASARS-2A |
| Sensor Cueing | RC-135V/W (SIGINT pickup of engineer net) |
| Sensor Redundancy | NGA commercial SAR |
| Tasking Cycle | ATO Day +1 |
| PED | AF DCGS / 480 ISRW |
| Reporting Channel | JWICS to JTF J-2 CM cell |
| LTIOV (reporting) | 12 JUN 0530Z |
| Status | TASKED / COLLECTED / EXPLOITED / REPORTED / CLOSED |
| Last Update | timestamp |
| Notes | weather risk, threat ring, etc. |

## Authoring Workflow

```
┌──────────────────────────────────────────────────────────────┐
│  1. Receive and validate CCIR / PIR set from commander       │
└──────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│  2. Conduct IPB / IPOE / MIPOE                               │
│     (ATP 2-01.3 / JP 2-01.3 / NTTP 2-01.3)                   │
│     → Output: NAIs, TAIs, indicators                         │
└──────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│  3. Decompose PIRs to SIRs to EEIs                           │
│     → see 02-pir-to-eei-decomposition.md                     │
└──────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│  4. Inventory available sensors (organic, joint, national)   │
└──────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│  5. Match sensors to EEIs (sensor-to-indicator matching)     │
│     → see 05-sensor-to-indicator-matching.md                 │
│     → apply cueing / redundancy / mix                        │
└──────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│  6. Time-phase collection into ATO cycles / orbit slots      │
│     → output: ISR Synchronization Matrix                     │
│     → see 04-isr-synchronization-matrix.md                   │
└──────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│  7. Generate SORs / RFCs                                     │
│     → push to COM elements (AOC ISRD, NSA SOTA, etc.)        │
│     → push RFIs up the architecture for what JOA can't do    │
└──────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│  8. Monitor execution and EEI satisfaction                   │
│     → re-task as needed                                      │
│     → close requirements                                     │
│     → feed assessment back to commander                      │
└──────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│  9. JCMB / CCB review — re-prioritize JIPCL nightly          │
└──────────────────────────────────────────────────────────────┘
```

## Service-Specific Output Names

| Service / Echelon | Plan Output | Tasking Output |
|---|---|---|
| Joint (JTF/CCMD) | Collection Plan + JIPCL | RFI to components / national |
| Army | Information Collection Plan (Annex L of OPORD) + IC Matrix + IC Overlay | IC Tasking Order |
| Air Force | Theater ISR Strategy → ISR Operations Annex of AOD | ATO ISR Annex / RSTA / SPINS |
| Navy | MOC Collection Plan | Naval Tasking Order |
| Marine Corps | Collection Plan (per MCWP 2-10) | Intel Tasking |

These are not the same documents — they are service-specific instantiations of the same underlying logic. A joint collection manager has to know all of them by name.

## Plan Hygiene Rules

1. **Every row tied to a PIR.** If you can't trace the row back to a PIR, kill the row.
2. **No row without an LTIOV.** Period.
3. **No row without a closure mechanism.** Define what "satisfied" looks like before you task.
4. **Update status at least daily.** A stale plan is worse than no plan.
5. **Kill requirements aggressively.** Sensor time is a zero-sum resource. Dead PIRs cost real collection minutes.
6. **Document your sensor mix decision.** Why this sensor and not that one — so the next CM can audit your logic.
7. **Publish the plan.** The plan that only the CRM cell sees doesn't get fed by the rest of the staff.

## Templates

- [Collection Plan Spreadsheet Template](../08-templates-and-formats/collection-plan-template.md)
- [IC Matrix Template](../08-templates-and-formats/ic-matrix-template.md)
- [ISR Sync Matrix Template](../08-templates-and-formats/isr-sync-matrix-template.md)

## Sources

- [JP 2-01, Joint and National Intelligence Support to Military Operations](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [ATP 2-01, Planning Requirements and Assessing Collection](https://armypubs.army.mil/)
- [FM 3-55, Information Collection](https://armypubs.army.mil/)
- [AFDP 2-0, Intelligence](https://www.doctrine.af.mil/)
