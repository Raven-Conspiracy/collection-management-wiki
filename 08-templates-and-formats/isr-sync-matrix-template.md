# ISR Synchronization Matrix Template (Joint / AF)

_Templates › Plans_

---

The **ISR Synchronization Matrix** is the joint and Air Force time-phased view of the collection plan. See [Building an ISR Synchronization Matrix](../04-collection-process/04-isr-synchronization-matrix.md) for the authoring walkthrough.

## Layout

- Rows = collection assets
- Columns = time slices (typically aligned to the ATO cycle — 24h windows broken into 6h or 1h blocks)
- Cells = tasking (NAI/TAI + EEI ID + sensor mode)

## Template

```
TIME WINDOW:    [start UTC] — [end UTC]
ATO CYCLE:      [Day +N]
CLASSIFICATION: [...]
COVERAGE DAY:   [DD MMM YYYY]
```

| Asset | Block 1 (H-24..H-18) | Block 2 (H-18..H-12) | Block 3 (H-12..H-6) | Block 4 (H-6..H) | Block 5 (H..H+6) |
|---|---|---|---|---|---|
| U-2S #1 | | | | | |
| U-2S #2 | | | | | |
| RQ-4B #1 | | | | | |
| MQ-4C Triton #1 | | | | | |
| RC-135V/W | | | | | |
| RC-135U | | | | | |
| RC-12X | | | | | |
| MQ-9 #1 | | | | | |
| MQ-9 #2 | | | | | |
| MQ-9 #3 | | | | | |
| MQ-1C Gray Eagle | | | | | |
| RQ-7 Shadow | | | | | |
| P-8A | | | | | |
| EA-18G | | | | | |
| F-35 ISR-capable | | | | | |
| Commercial EO refresh | | | | | |
| Commercial SAR refresh | | | | | |
| NGA NTM tasking | | | | | |
| PROPHET ground | | | | | |
| HUMINT reporting | | | | | |

## Cell Format

Each cell:

```
[NAI/TAI ID]  [EEI ID]  [sensor mode]
```

Example: `NAI-101 EEI-1.1 ASARS-spot`

## Companion Views

- **EEI-by-time view** — same data, EEIs as rows, surfaces coverage gaps per requirement
- **Geographic view (overlay)** — NAIs/TAIs on a map with sensor footprints
- **Gap report** — list of EEIs with no coverage in their LTIOV window
- **Conflict report** — list of double-booked assets

## See Also

- [IC Matrix Template (Army)](ic-matrix-template.md)
- [Collection Plan Template](collection-plan-template.md)
- [Joint Collection Doctrine](../02-joint-doctrine/jp-2-01-joint-and-national-intel-support.md)

---
*Template version 1.0 — Raven Conspiracy Collection Management Wiki*
