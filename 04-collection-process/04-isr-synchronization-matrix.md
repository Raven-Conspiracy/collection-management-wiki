# Building an ISR Synchronization Matrix

_Process › Synchronization_

---

> *"The matrix is where the collection plan stops being a wish list and starts being a schedule."*

The **ISR Synchronization Matrix** (Joint / AF term) — also called the **Information Collection Matrix** (Army, per ATP 2-01) — is the time-phased visualization of the collection plan. It is the document that hangs on the CM cell's wall and tells everyone at a glance: what sensor is doing what, where, when, against what EEI.

## What It Shows

A correctly built ISR Sync Matrix shows, at minimum:

- **Rows:** Collection assets / sensors (one per row)
- **Columns:** Time slices (typically 1-hour or ATO-cycle blocks)
- **Cells:** Tasking — NAI/TAI, EEI ID, indicator/signature

Some variants flip this — EEIs as rows, time as columns — but the asset-row / time-column layout is most common because it surfaces gaps and conflicts in sensor utilization.

## Canonical Structure (ATP 2-01 IC Matrix)

| Asset | H-24 to H-18 | H-18 to H-12 | H-12 to H-6 | H-6 to H | H to H+6 |
|---|---|---|---|---|---|
| U-2S #1 | — | NAI-101 (EEI-1.1) ASARS | NAI-102 (EEI-1.2) ASARS | — | (mx) |
| RC-135V/W | NAI-201 area, EEI-2.2 ELINT | continuous | continuous | continuous | continuous |
| MQ-9 #1 | NAI-202 FMV, EEI-2.4 | NAI-202 | (transit) | NAI-103 FMV, EEI-1.2 | NAI-103 |
| MQ-9 #2 | (mx) | NAI-301 FMV, EEI-3.1 | NAI-301 | NAI-301 | NAI-301 |
| Triton #1 | maritime AOR-1 | maritime AOR-1 | maritime AOR-1 | maritime AOR-1 | maritime AOR-1 |
| NGA commercial EO | scheduled refresh NAI-104 | — | — | scheduled refresh NAI-101 | — |
| RC-12X #1 | NAI-201 SIGINT | NAI-201 | NAI-202 | NAI-202 | (mx) |
| PROPHET ground | NAI-201 (BCT AO) | continuous | continuous | continuous | continuous |
| HUMINT teams | reporting cycle 1 | reporting cycle 2 | — | reporting cycle 3 | — |

## How to Build One

### Step 1 — Lock the time window
Decide what the matrix covers: typically one ATO cycle (24–72 hours) for joint air ops, or one operational phase for ground.

### Step 2 — List every available asset as a row
Include organic, apportioned, and reachback. Include national assets only as scheduled refresh windows you know about. Mark maintenance, transit, and crew-rest windows.

### Step 3 — Pull EEIs from the collection plan
For each EEI, identify:
- Primary sensor
- Cueing sensor
- Redundancy sensor
- LTIOV (constrains which time slice it must land in)

### Step 4 — Slot tasking into cells
Each cell gets: **NAI/TAI** + **EEI ID** + **sensor mode** (e.g., "NAI-101 EEI-1.1 ASARS"). Keep cells terse — the detail lives in the SOR.

### Step 5 — Identify gaps and conflicts
- **Gap:** EEI with no sensor coverage during its required window
- **Conflict:** Same asset double-booked
- **Over-coverage:** Multiple high-end sensors on the same low-priority EEI (waste)

### Step 6 — Apply cueing/redundancy/mix
For high-priority EEIs (P1, TST-related), ensure at least two sensors of different disciplines in the same time slice.

### Step 7 — Coordinate with COM
The matrix is CRM's view. COM (AOC ISRD for air, MOC for maritime, etc.) takes it and produces the executable tasking order (ATO ISR Annex, RSTA, SPINS).

### Step 8 — Publish, brief, update
Brief at every JCMB / CCB / commander's update brief. Update at least every ATO cycle, more often during dynamic operations.

## Sample Tools / Systems That Render the Matrix

| Tool | Used By | Notes |
|---|---|---|
| **PRISM** (Planning tool for Resource Integration, Synchronization, and Management) | Joint, IC-wide | Web-based collection requirements management tool; integrates with COLISEUM |
| **GIMS** (Geospatial Intelligence Management System) | NGA, joint | GEOINT requirements management |
| **COLISEUM** | National + joint | Community On-Line Intelligence System for End Users and Managers; legacy but still referenced |
| **TPED Manager** | Service PEDs | Tracks exploitation throughput |
| Service DCGS family | Per-service | DCGS-A / DCGS-N / DCGS-AF; native sync tools |
| Excel / SharePoint | Everyone, when systems fail | The honest truth |

## Reading the Matrix as a Commander

A commander glancing at the matrix should be able to answer:

1. **Which of my PIRs is fully covered, partially covered, or uncovered?**
2. **Where am I taking risk** (single-sensor coverage on a P1 EEI)?
3. **What am I asking external organizations for** (RFIs out)?
4. **What's the highest-cost orbit I'm flying and what's it answering?**
5. **Where is the dead time I could reallocate?**

If the matrix doesn't surface those answers in 60 seconds of looking, it is too cluttered or wrongly structured.

## Common Mistakes

| Mistake | Fix |
|---|---|
| Matrix has assets but no EEI IDs in cells | Add EEI IDs; otherwise the matrix is sensor schedule, not collection plan |
| All cells filled even with low-value tasking | Leave gaps visible; gaps surface where dynamic re-tasking is possible |
| No representation of national / commercial scheduled refresh | Always show what's coming in from outside, even if you don't control it |
| Time slices too coarse (24-hour blocks) | Move to 6-hour or ATO-cycle blocks for air; 1-hour for TST-heavy ops |
| Matrix produced once and never updated | Update every ATO cycle minimum; in TST ops, update continuously |

## Templates

- [ISR Sync Matrix Template (markdown)](../08-templates-and-formats/isr-sync-matrix-template.md)
- [IC Matrix Template (Army, ATP 2-01)](../08-templates-and-formats/ic-matrix-template.md)

## Sources

- [ATP 2-01, Planning Requirements and Assessing Collection](https://armypubs.army.mil/)
- [JP 2-01, Joint and National Intelligence Support to Military Operations](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [AFDP 2-0, Intelligence](https://www.doctrine.af.mil/)
