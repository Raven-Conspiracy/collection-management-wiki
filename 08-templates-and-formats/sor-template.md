# SOR (Specific Orders & Requests) Template

_Templates › Requirements_

---

```
CLASSIFICATION:    [...]
SOR ID:            SOR-[YYYY]-[MMDD]-[NNNN]
Linked EEI:        [EEI ID]
Linked SIR:        [SIR ID]
Linked PIR:        [PIR ID]
JIPCL Priority:    [P1 / P2 / P3]
Originator (CRM):  [CM cell + POC]
Recipient (COM):   [AOC ISRD / NSA SOTA / Navy MOC / Army G-2 CM / etc.]
Date issued:       [DD MMM YYYY HHMM Z]
```

## 1. Tasked Asset
- Platform: [e.g., U-2S]
- Sensor / mode: [e.g., ASARS-2A, spot mode]
- Tail / orbit ID: [if pre-assigned]

## 2. Collection Geometry
- NAI: [ID + coordinates]
- TAI (if applicable): [ID + coordinates]
- Stand-off geometry: [orbit anchor / pass profile]

## 3. Timing
- Collection start: [DD MMM YYYY HHMM Z]
- Collection end: [DD MMM YYYY HHMM Z]
- LTIOV (collection): [HHMM Z]
- LTIOV (reporting): [HHMM Z]

## 4. Target Signature
[What the sensor is specifically looking for — type, expected location, signature library reference]

## 5. Cueing
- Cued by: [sensor / detection event]
- Cueing trigger: [specific event that initiates this SOR's execution]

## 6. PED
- Processing site: [AF DCGS site / DCGS-A / DCGS-N / NSA cell]
- Expected exploitation timeline: [time from collect to report]

## 7. Reporting
- Reporting format: [SAR product / FMV clip / SIGINT report / written]
- Recipient: [JTF J-2 CM cell]
- Channel: [JWICS / JDISS / IBS / SI]
- Distribution: [TS//SI//NOFORN / SECRET//REL ...]

## 8. Backup Sensor
[If primary aborts: backup platform/sensor and escalation path]

## 9. Restrictions / Special Instructions
[ROE constraints, releasability, foreign disclosure, cross-cueing pre-authorizations]

## 10. Tracking
| Status | Time | Notes |
|---|---|---|
| Issued | | |
| Accepted by COM | | |
| Tasked into ATO/NTO | | |
| Executed | | |
| Reported | | |
| Closed | | |

---
*Template version 1.0 — Raven Conspiracy Collection Management Wiki*
