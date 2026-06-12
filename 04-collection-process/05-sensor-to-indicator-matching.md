# Sensor-to-Indicator Matching

_Process › Matching_

---

> *"Don't task SIGINT to confirm a visual signature, choom. The Emperor weeps when you waste a Rivet Joint orbit on something a commercial SAR refresh could answer."*

The single most expensive class of collection error is **mismatching sensor to signature**. The fix is a deliberate sensor-to-indicator matching step before any EEI gets tasked.

## The Matching Rule

For every EEI, ask:

1. **What is the physical/electromagnetic signature** the indicator produces?
2. **What sensor(s) can detect that signature** at the required resolution and time scale?
3. **What is the LTIOV** and can the candidate sensor make that window?
4. **What is the threat environment** at the collection point — can the sensor survive it?
5. **What is the cost** (orbit time, opportunity cost, escalation risk)?
6. **Is there a cheaper sensor that gives "good enough"** for this EEI's priority?

The right answer is rarely a single sensor. It is usually a primary + cueing + redundancy stack.

## Sensor-to-Signature Cheat Sheet

| Indicator / Signature | Primary INT | Sensor Options | Notes |
|---|---|---|---|
| Static vehicle count / disposition | GEOINT | Commercial EO (Maxar / Planet / BlackSky), NGA NTM, U-2, MQ-9 EO/IR | Weather-dependent for optical; SAR substitute |
| Moving vehicles / convoys | GMTI | (Legacy E-8C JSTARS), HALE GMTI substitutes, ASIP-equipped manned platforms | GMTI gap since JSTARS retirement is real; space-based MTI emerging |
| Bridging / construction equipment | GEOINT | SAR (U-2 ASARS-2A, commercial SAR — Capella, Umbra, ICEYE), commercial EO | SAR penetrates weather and detects metal mass |
| Communications net activity | SIGINT (COMINT) | RC-135V/W Rivet Joint, RC-12X Guardrail, PROPHET, NSA national | Frequency-dependent; range-limited |
| Radar / EW emitter activity | SIGINT (ELINT) | RC-135U Combat Sent, RC-135V/W, EA-18G, U-2 sensors | ELINT geolocation requires TDOA/FDOA across multiple platforms |
| Missile launch / hot signature | MASINT | SBIRS (space-based IR), RC-135S Cobra Ball | National-level; integrated through NORAD/USNORTHCOM |
| CBRN signatures | MASINT | WC-135 Constant Phoenix, ground sensors, national | Highly specialized |
| Tunnel / underground activity | MASINT + GEOINT | Hyperspectral, SAR change detection, seismic | Multi-INT required |
| Personnel intent / morale | HUMINT | Source networks, CI/HUMINT teams, captured personnel | Slow, but irreplaceable for intent |
| Cellular traffic patterns | SIGINT | National-tactical NSA, PROPHET in some modes | Legal authorities matter — see ICD-204 and EO 12333 |
| Cyber activity / network traffic | Cyber / DNI | NSA, USCYBERCOM CMF | Authorities and disclosure rules apply |
| Maritime contacts | GEOINT + SIGINT | P-8A, MQ-4C Triton, SSN/SSGN, surface combatants, SURTASS | Multi-INT maritime picture |
| Submarine activity | MASINT + acoustic | SURTASS / T-AGOS, SSN, P-8A MAC | Acoustic is its own world |
| Construction / bed-down at airfield | GEOINT | Commercial EO refresh, U-2 SAR, MQ-9 EO/IR | Long timeline; commercial often best |
| Pattern of life at single facility | GEOINT (WAMI) | Persistent surveillance — Gorgon Stare class, commercial persistent | WAMI is bandwidth- and PED-intensive |

See [Discipline Deep-Dives](../06-discipline-deep-dives/) for INT-by-INT signature catalogs.

## The Cheaper-First Heuristic

Always ask: **what is the cheapest sensor that satisfies this EEI?**

- A commercial EO refresh of a known building costs essentially zero marginal orbit time and answers a static-disposition EEI as well as an MQ-9.
- A SIGINT pickup costs a fraction of the daily Rivet Joint orbit you're already flying.
- An MQ-9 FMV pass is cheap *if* the orbit is already planned over the area; very expensive if it requires diverting from another tasking.
- A U-2 / RQ-4 sortie is a multi-million-dollar event with limited daily availability.
- A national imagery tasking has high political/strategic visibility and can take days to schedule.

**Reserve high-end sensors for high-end EEIs.** That's how you don't burn out the architecture.

## The Threat-Environment Check

Every sensor has a survivability envelope:

| Platform | Survivable In | At-Risk In | No-Go |
|---|---|---|---|
| MQ-9A | Permissive, light contested | Heavy SAM threat | Modern double-digit SAM rings |
| MQ-9B SkyGuardian | Same — slightly hardened | Same | Same |
| RQ-4 | Permissive at altitude | Long-range SAM (S-300/400 class) | Inside engagement zone |
| U-2 | Permissive at altitude | Double-digit SAM | Inside engagement zone |
| RC-135 series | Standoff only | Inside threat ring | Inside engagement zone |
| F-35 (sensor role) | Contested / denied | — | — (until kinetic threat exceeds survivability) |
| Space-based | Almost all environments | Counter-space threats emerging | Kinetic/EW counter-space |
| MQ-4C Triton | Permissive maritime | Contested maritime | Same |
| Commercial space | All environments | Same — politically sensitive in some AORs | — |
| Small UAS (Group 1–3) | Tactical AO | EW jamming, small arms, dedicated C-UAS | Same |

In a peer fight, the contested-environment problem forces **standoff sensors + space + cyber/SIGINT** to carry the load, with penetrating ISR limited to F-35 sensor fusion and selected SOF.

## The Multi-INT Bias

Three reasons to default to multi-INT layering:

1. **Deception defeat.** Single-INT collection is the easiest thing to deceive. Multi-INT raises the adversary's deception cost.
2. **Confidence.** Two independent INT confirmations dramatically raise analyst confidence and the commander's willingness to act.
3. **Robustness.** Any single sensor can abort. Multi-INT means no single point of failure on a P1 EEI.

The trade is bandwidth, PED capacity, and orbit time. Worth it for P1 EEIs; usually not for P3.

## Cross-Cueing — The Operational Glue

Cross-cueing is when one sensor's detection automatically (or near-automatically) tasks another sensor. JP 2-0 codifies this; modern systems automate parts of it.

Classic cross-cue patterns:

- **SIGINT → IMINT:** ELINT/COMINT geolocation cues SAR/EO/FMV for visual confirmation.
- **GMTI → FMV:** GMTI track on a road cues MQ-9 to drop onto the vehicle for PID.
- **MASINT → IMINT:** SBIRS missile launch cues imagery for impact area assessment.
- **HUMINT → IMINT:** Source reporting cues imagery refresh.
- **IMINT → SIGINT:** Detection of new SAM site cues ELINT to characterize emissions.

Cross-cue authorities should be **pre-coordinated** in the collection plan, not negotiated during a TST event.

## Sources

- [JP 2-0, Joint Intelligence](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [JP 2-01, Joint and National Intelligence Support to Military Operations](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [ATP 2-01, Planning Requirements and Assessing Collection](https://armypubs.army.mil/)
- [AFDP 2-0, Intelligence](https://www.doctrine.af.mil/)
