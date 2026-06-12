# CRM vs COM vs CMA — Who Owns What

_Foundations › Concept_

---

> *"Three letters, three lanes, three ways to get fired if you confuse them."*

The single most common mistake junior collection managers make is conflating **CRM**, **COM**, and **CMA**. They are three distinct functions, owned by three distinct entities, with three distinct authorities.

## Side-by-Side

| | **CRM** | **COM** | **CMA** |
|---|---|---|---|
| **Stands for** | Collection Requirements Management | Collection Operations Management | Collection Management Authority |
| **Owned by** | J-2 collection manager / theater collection element | Component or asset owner (e.g., AOC ISRD, NSA SOTA, theater Army G-2 CM cell) | Joint Force Commander (delegable to subordinate JFC or component) |
| **Type of thing** | A **function** | A **function** | An **authority** (legal/command) |
| **Verb** | Requires, validates, prioritizes, decomposes, plans | Tasks, schedules, executes, monitors, re-tasks | Establishes, prioritizes, validates |
| **Output** | Validated requirements, collection plan, JIPCL | Tasking orders (ATO, NTO, IC Tasking Order), sensor schedules, mission reports | Theater collection priorities, RFI denials/approvals, conflict resolution |
| **Time horizon** | Days–months (plan), minutes–hours (dynamic) | Hours–minutes (execution) | Continuous (governance) |

## CRM — Collection Requirements Management

> "Collection requirements management is the authoritative development and control of collection, processing, exploitation, and reporting requirements that normally result in either the direct tasking of resources under the control of the COCOM or the generation of tasking requests to collection sources outside the COCOM."  
> — JP 2-01

**What a CRM cell actually does:**
1. Receives requirements (RFIs from below, PIRs from the commander, EEIs from analysts, taskings from above).
2. **Validates** — is this a real requirement? Already answered? Better sourced elsewhere?
3. **Prioritizes** — slot into the JIPCL or service equivalent.
4. **Decomposes** — PIR → SIR → EEI → indicators/signatures observable by a sensor.
5. **Develops a collection strategy** — what mix of sensors, what cueing, what redundancy.
6. **Develops the collection plan** — the working document that maps EEIs to NAIs to assets to times.
7. **Routes tasking requests** to COM elements or external agencies.
8. **Monitors satisfaction** — did the EEI get answered? What's left?
9. **Closes or re-tasks** as needed.

**CRM never owns the platform.** CRM owns the *requirement* and the *plan*.

## COM — Collection Operations Management

> "Collection operations management is the authoritative direction, scheduling, and control of specific collection operations and associated processing, exploitation, and reporting resources."  
> — JP 2-01

**What a COM cell actually does:**
1. Receives validated, prioritized collection requirements from CRM.
2. Matches requirements to **specific platforms / sensors / orbits / passes**.
3. Produces the **tasking order** — for ISR aircraft this is the ATO ISR Annex / RSTA; for SIGINT this is the SOTA from NSA; for Army it's the IC Tasking Order.
4. Schedules sensors, deconflicts airspace, coordinates with the AOC, the maritime component, ground component, etc.
5. **Monitors execution in real time** — sensor up/down, weather aborts, threat reactions.
6. **Re-tasks dynamically** — divert a Reaper to a TST, surge a Triton orbit, drop a coverage line.
7. Pushes mission reports back to CRM and to PED.

**COM owns the schedule and the sensor.** COM does not get to decide what's important — that's CRM and CMA.

## CMA — Collection Management Authority

> "Collection management authority constitutes the authority to establish, prioritize, and validate theater collection requirements, establish sensor tasking guidance, and develop theater collection plans."  
> — JP 2-01

**CMA is an authority, not a function.** It is **vested in a commander** and **delegated** down the chain.

- The **Joint Force Commander (JFC)** holds CMA by default for the joint operations area.
- The JFC normally **delegates CMA to the J-2** (in practice, to a Collection Manager / Deputy J-2).
- For air-breathing ISR, the JFC typically designates the **JFACC** as the supported commander for theater ISR and delegates relevant CMA authorities to the AOC ISRD.
- For naval ISR, CMA flows through the **Maritime Component Commander / numbered fleet N-2**.
- For HUMINT, CMA is exercised through the **J-2X**.
- National collectors (NGA imagery, NSA SIGINT, NRO satellites) are not under JFC CMA — they are coordinated through CRM via national-to-tactical channels (COLISEUM, JWICS, JDISS, LNI).

**The CMA holder is who you escalate to when components disagree** — e.g., when the SOF JTF and the conventional JTF both want the same MQ-9 orbit during the same window.

## A Worked Example

**Scenario:** Commander needs to know if the 20th Guards CAA is moving from garrison to a forward assembly area in the next 72 hours.

| Step | Entity | Function | Action |
|---|---|---|---|
| 1 | Commander | — | Issues PIR: "Will 20 GdsCAA move to FAA WEST in 72hrs?" |
| 2 | J-2 (CMA delegate) | CMA | Validates PIR, slots P1 on JIPCL |
| 3 | Theater CM cell | CRM | Decomposes to SIRs: (a) movement of bridging assets, (b) departure indicators at garrison, (c) road march signatures, (d) FAA preparation |
| 4 | CM cell | CRM | Decomposes SIR(a) to EEI: "PMP pontoon bridge sections within 5km of Bridge Site ALPHA, NLT 12 JUN 2026 0600Z" |
| 5 | CM cell | CRM | Selects sensor mix: U-2 SAR cued by RC-135V/W ELINT, with NGA commercial EO refresh, MQ-9 standby for dynamic re-tasking |
| 6 | CM cell | CRM | Generates SOR / tasking request, routes to AOC ISRD (for U-2/MQ-9) and to NSA via SOTA (for RC-135 tasking) |
| 7 | AOC ISRD | COM | Slots U-2 mission in next ATO cycle, writes RSTA annex, deconflicts airspace |
| 8 | NSA SOTA | COM | Tasks RC-135 collection windows aligned with U-2 pass |
| 9 | Platforms | — | Fly the mission, collect against NAIs |
| 10 | AF DCGS / NSA | PED | Exploit; report against the EEI |
| 11 | CM cell | CRM | Tracks EEI satisfaction; closes or re-tasks |
| 12 | JCMB | CMA forum | Reviews JIPCL nightly, re-prioritizes for next cycle |

CRM owns steps 3–6 and 11. COM owns steps 7–9. CMA owns steps 2 and 12.

## Common Failure Modes

| Failure | Root Cause |
|---|---|
| Sensor flies the orbit but doesn't collect against the EEI | CRM-COM disconnect — EEI wasn't translated into a tasked collection point |
| Component goes outside JIPCL and burns priority sensor time on a pet requirement | CMA not enforced |
| RFI from a BCT bounces around for days | No clear CRM routing path — the BCT didn't know who owns the requirement |
| National asset tasked for a tactical question | CRM didn't push the request through national-to-tactical channels properly; or the tactical sensor was available and ignored |
| Re-tasking lag during a TST event | COM cell not pre-authorized for dynamic re-tasking by the CMA holder |

## See Also

- [PIR → SIR → EEI → SOR Hierarchy](../04-collection-process/02-pir-to-eei-decomposition.md)
- [Authoring a Collection Plan](../04-collection-process/03-authoring-a-collection-plan.md)
- [JP 2-01 deep-dive](../02-joint-doctrine/jp-2-01-joint-and-national-intel-support.md)
- [Tasking Authority by Echelon](../07-tools-and-systems/tasking-authority-reference.md)

## Sources

- [JP 2-01, Joint and National Intelligence Support to Military Operations](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [AFDP 2-0, Intelligence](https://www.doctrine.af.mil/)
- [ATP 2-01, Planning Requirements and Assessing Collection](https://armypubs.army.mil/)
