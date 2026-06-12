# What Is Collection Management?

_Foundations › Concept_

---

## The One-Sentence Answer

**Collection management** is the deliberate process of converting a commander's information needs into tasked, scheduled, and synchronized collection activities — and ensuring the results get to the analyst, the targeteer, and the shooter in time to matter.

## The JP 2-01 Answer

> "Collection management is the process of converting intelligence requirements into collection requirements, establishing priorities, tasking or coordinating with appropriate collection sources or agencies, monitoring results, and re-tasking, as required." — JP 2-01

It is **not**:
- Just sensor scheduling (that's part of Collection Operations Management).
- Just RFI processing (RFIs are one input).
- Just "ISR." ISR is the activity; collection management is the discipline that governs it.
- Owned by the J-3. The **J-2 owns collection management**; the J-3 owns the assets when they are flying / sailing / shooting.

## The Three Functions

Joint doctrine cleanly splits collection management into three functions. Internalize these:

| Function | Acronym | Owner | What It Does |
|---|---|---|---|
| **Collection Requirements Management** | **CRM** | J-2 / Collection Manager | Receives requirements, validates them, prioritizes them, develops a collection strategy and plan |
| **Collection Operations Management** | **COM** | Component / Asset owner | Translates the plan into tasking orders, schedules platforms, manages sensors, monitors execution |
| **Collection Management Authority** | **CMA** | Joint Force Commander (delegable) | The legal/command authority to establish, prioritize, and validate theater collection requirements |

**Mnemonic:** CRM asks "what," COM asks "how/when/with what," CMA decides "who has the right to say so."

See [CRM vs COM vs CMA](03-crm-com-cma.md) for the deep dive.

## Where Collection Lives in the Intelligence Cycle

```
       ┌─────────────────────┐
       │ Planning & Direction│ ◄────┐
       └──────────┬──────────┘      │
                  │                 │
                  ▼                 │
       ┌─────────────────────┐      │
       │     COLLECTION      │      │
       │  ← you are here     │      │
       └──────────┬──────────┘      │
                  │                 │
                  ▼                 │
   ┌──────────────────────────┐     │
   │ Processing & Exploitation│     │  Feedback drives
   └──────────┬───────────────┘     │  re-tasking and
              ▼                     │  refinement.
   ┌──────────────────────┐         │
   │ Analysis & Production│         │
   └──────────┬───────────┘         │
              ▼                     │
   ┌──────────────────────────┐     │
   │ Dissemination & Integration   │
   └──────────┬───────────────┘     │
              ▼                     │
   ┌──────────────────────┐         │
   │ Evaluation & Feedback│─────────┘
   └──────────────────────┘
```

Collection is **the second category** of the joint intelligence process per JP 2-0. Everything upstream defines what we need; everything downstream depends on collection delivering it on time.

## What Collection Management Actually Produces

A collection manager outputs (or shepherds) the following artifacts. Each is documented in this wiki under [Templates](../08-templates-and-formats/):

- **PIRs** (Priority Intelligence Requirements) — validated by the commander
- **SIRs** (Specific Information Requirements) — derived from PIRs
- **EEIs** (Essential Elements of Information) — observable, collectable facts
- **Collection Plan / Collection Strategy** — the master document
- **ISR Synchronization Matrix** — when, where, who, what sensor (the Army calls this the **IC Matrix**)
- **JIPCL** (Joint Integrated Prioritized Collection List) at joint level
- **Tasking orders** — ATO (Air Force-led), Naval Tasking Order, IC Tasking Order (Army)
- **RFI dispositions** — accepted, denied, deferred, sourced to another component
- **Collection assessments** — did the asset answer the EEI? Feed back to refinement.

## Why It Matters

A bad collection manager:
- Lets sensors fly empty orbits over the wrong NAIs
- Misses the LTIOV and delivers stale intel
- Tasks SIGINT to confirm a visual signature
- Burns a national asset on a tactical question a Group 2 UAV could answer
- Doesn't close the loop — the analyst never knows the EEI got answered or didn't

A good collection manager:
- Maps every sensor minute to a specific EEI
- Layers cueing, redundancy, and mix so no single point of failure breaks the plan
- Pushes the right RFIs up and down the architecture
- Kills requirements that are no longer relevant — sensor time is finite
- Closes the loop and feeds the next planning cycle

## Next Reads

- [The Intelligence Cycle](02-intelligence-cycle.md)
- [CRM vs COM vs CMA](03-crm-com-cma.md)
- [PIR → SIR → EEI → SOR Hierarchy](../04-collection-process/02-pir-to-eei-decomposition.md)
- [JP 2-01 — Joint and National Intelligence Support to Military Operations](../02-joint-doctrine/jp-2-01-joint-and-national-intel-support.md)

## Sources

- [JP 2-0, Joint Intelligence](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [JP 2-01, Joint and National Intelligence Support to Military Operations](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
