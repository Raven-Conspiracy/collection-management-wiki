# RFI and Collection Request Workflow

_Process › Requests_

---

> *"The RFI is the universal currency of joint intelligence. Write it badly and it bounces; write it well and you get answers."*

## What an RFI Is — and Isn't

A **Request for Information (RFI)** is a formal request from one element to another for information that the requesting element cannot collect or produce itself.

An RFI is **not**:
- A collection task. Collection tasks go to assets you control via SOR; RFIs go to elements outside your tasking authority.
- A casual question. RFIs are formal, tracked, prioritized, and dispositioned.
- A way to skip the validation step. RFIs go through CRM validation just like internal requirements.

Per JP 2-01, RFIs are the joint mechanism by which a JTF gets information from national agencies (NGA, NSA, NRO, DIA), from other components, or from coalition partners.

## RFI Lifecycle

```
   Originator          CRM Validator         Receiving Element       PED/Producer
       │                     │                       │                     │
       │── RFI submission ──►│                       │                     │
       │                     │── validate, prioritize                      │
       │                     │── source decision ───►│                     │
       │                     │                       │── task collector ──►│
       │                     │                       │                     │── produce
       │                     │◄── product────────────┤◄────────────────────┤
       │◄─── product ────────┤                       │                     │
       │                                                                   │
       │── feedback / close RFI ─────────────────────────────────────────► │
```

## Minimum RFI Content

A good RFI has every one of these fields. Missing fields are why RFIs bounce.

| Field | Description |
|---|---|
| RFI ID | Locally assigned, globally unique |
| Originator | Element + POC + secure contact |
| Requirement Statement | The actual question (one sentence) |
| Justification | What decision does this answer? Tied to which PIR/CCIR? |
| Priority | P1/P2/P3 per local convention, or NIPF tier reference |
| LTIOV | Latest Time Information is of Value (UTC) |
| Geographic Bounds | Lat/long, MGRS, or named area |
| Time Window | Period of interest |
| Format | Image, written assessment, raw report, briefing |
| Classification | Up to SECRET//REL or as required |
| Releasability | Who can see the answer — partner releasability matters |
| Prior Sourcing | What you've already tried and why it didn't satisfy |
| Suggested Sourcing | Who you think can answer — saves the validator time |
| Reporting Channel | Where the answer should go |

## Routing Logic

**Tactical → Higher:**
- BCT S-2 can't answer → division G-2 → corps G-2 → ASCC G-2 → CCMD J-2 → national

**Component → Component:**
- Land component needs maritime answer → routes through JTF J-2 to maritime component CMA

**JTF → National:**
- JTF J-2 routes RFI via JIPCL inclusion or direct to national functional managers:
  - GEOINT → NGA
  - SIGINT → NSA
  - HUMINT → DIA
  - MASINT → DIA (Defense MASINT Office)
  - Imagery from satellites → NRO via NGA
- Tooling: **COLISEUM**, **PRISM**, **GIMS**, **JWICS** messaging

**Coalition:**
- RFIs to partners go through ARO / SIO / Foreign Disclosure Officer (FDO); releasability fields become load-bearing

## The CRM Validator's Job on an Inbound RFI

When an RFI hits your CRM cell, you do **not** just forward it. You:

1. **Validate** the requirement. Is the question real? Is the justification valid?
2. **Check for duplication.** Is this already on the JIPCL? Already answered by an existing product?
3. **Assess sourcing.** Can your organic collection answer it? Cheaper than asking national?
4. **Prioritize.** Where does this sit relative to existing requirements?
5. **Disposition.** Accept / Deny / Defer / Refer:
   - **Accept** — task internally, add to collection plan
   - **Deny** — with reason (out of scope, already answered, infeasible, unfundable, classification mismatch)
   - **Defer** — when no current capacity but worth keeping
   - **Refer** — when another element is the right owner
6. **Communicate disposition back to the originator.** Silence is the worst failure mode.
7. **Track to closure.** Every RFI has a final state.

## RFI vs Other Request Forms

| Form | Used By | Difference |
|---|---|---|
| **RFI** | Joint, IC-wide | Generic request for information |
| **RFC** (Request for Collection) | Joint, sometimes | Specifically requests *collection* (not analysis) |
| **RFS** (Request for Support) | Army (ATP 2-01) | Request to another unit for collection support; semi-formal |
| **GIR** (General Intelligence Requirement) | National | Long-standing, baseline information needs |
| **SIR** | Joint | Specific Information Requirement — derived from PIR, internal artifact, not a request to elsewhere |
| **EEI** | Joint | Essential Element of Information — collectable fact, internal artifact |
| **PIR** | Joint | Priority Intelligence Requirement — commander-validated |
| **TTPD** (Time-Sensitive Targeting / Dynamic Tasking) | Joint | Compressed cycle for TSTs, bypassing normal RFI lag |

## Common Failure Modes

| Failure | Fix |
|---|---|
| RFI has no LTIOV | Reject; add LTIOV; resubmit |
| RFI is actually a tasking attempt to a sensor outside the originator's authority | Reroute as RFI to the proper CMA holder |
| RFI duplicates an existing product | Deny with link to existing product |
| RFI accepted but never tracked to closure | Use a tracker; standing JCMB review |
| Originator never notified of denial | Build notification into the workflow; deny in writing |
| RFI escalated to national for something organic can answer | Validator's job; push back on the originator |

## Templates

- [RFI Template](../08-templates-and-formats/rfi-template.md)
- [RFI Disposition Template](../08-templates-and-formats/rfi-disposition-template.md)

## Sources

- [JP 2-01, Joint and National Intelligence Support to Military Operations](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/)
- [ATP 2-01, Planning Requirements and Assessing Collection](https://armypubs.army.mil/)
- [ICD 204, National Intelligence Priorities Framework](https://www.dni.gov/index.php/what-we-do/ic-policies-reports/intelligence-community-directives)
