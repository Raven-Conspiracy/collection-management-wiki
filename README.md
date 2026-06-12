# Collection Management Wiki

> *"Collection is the heartbeat of intelligence. Stop the heart, and the body of analysis dies on the table."*

**An expert reference on US Joint Force intelligence collection management — joint and service doctrine, the full requirements-to-tasking process, and the platforms that actually do the collecting.**

Maintained by **[Task Force Raven / Raven Conspiracy](https://github.com/Raven-Conspiracy)** as a companion to the [Inquisitor](https://github.com/Raven-Conspiracy/Inquisitor) intelligence orchestrator and [The Red Ledger](https://github.com/Raven-Conspiracy/the-red-ledger). All content is **UNCLASSIFIED** and grounded in publicly available US military doctrine.

---

## Who This Is For

- **35F / 35D / 350F** Army intelligence analysts, all-source officers, and warrant officers
- **14N / 1N** Air Force ISR officers and operators (AOC ISRD assignees)
- **183X / IS** Navy intelligence officers and specialists
- **0203 / 0204 / 0210** Marine Corps intelligence officers
- **J-2 staff** at any echelon — combatant command, joint task force, theater
- **Civilian IC counterparts** integrating with DoD collection
- **Anyone learning** to author a PIR, decompose it to EEIs, and task the right asset against the right indicator at the right time

If you can't recite the difference between CRM and COM, the IC Matrix columns, or which authority can task an MQ-9 vs. an RC-135 — this wiki is for you.

---

## Wiki Map

```
01-foundations/                 # Core concepts: intel cycle, ISR, CRM/COM, CMA
02-joint-doctrine/              # JP 2-0, JP 2-01, JP 3-0, JP 3-60
03-service-doctrine/            # Army, Air Force, Navy, Marines, National/IC
04-collection-process/          # CM cycle, PIR→EEI, ISR sync, RFI workflow
05-platforms/                   # Every major US collection asset, by domain
06-discipline-deep-dives/       # HUMINT, SIGINT, GEOINT, MASINT, OSINT, TECHINT
07-tools-and-systems/           # DCGS family, PED, tasking authority chains
08-templates-and-formats/       # PIR, EEI, IC Matrix, ISR Sync Matrix, RFI
09-case-studies/                # Worked examples (historical/notional/declassified)
references/                     # Master pub list, glossary, quick-reference
assets/                         # Diagrams, ISR sync mockups
```

---

## Start Here

### If you are new to collection management
1. [What Is Collection Management?](01-foundations/01-what-is-collection-management.md)
2. [The Intelligence Cycle and Where Collection Lives](01-foundations/02-intelligence-cycle.md)
3. [CRM vs COM vs CMA — Who Owns What](01-foundations/03-crm-com-cma.md)
4. [PIR → SIR → EEI → SOR Hierarchy](04-collection-process/02-pir-to-eei-decomposition.md)
5. [Your First Collection Plan](04-collection-process/03-authoring-a-collection-plan.md)

### If you are looking up a platform
- [Platforms Quick-Reference Table](references/platforms-quick-reference-and-glossary.md) — every platform in one table
- [Airborne Unmanned](05-platforms/airborne-unmanned/) · [Airborne Manned](05-platforms/airborne-manned/) · [Space](05-platforms/space/) · [Maritime](05-platforms/maritime/) · [Ground/SOF](05-platforms/ground-sof/) · [Cyber/National SIGINT](05-platforms/cyber-sigint/)

### If you are working an actual collection problem
1. [PIR → EEI Decomposition Walkthrough](04-collection-process/02-pir-to-eei-decomposition.md)
2. [Building an ISR Synchronization Matrix](04-collection-process/04-isr-synchronization-matrix.md)
3. [Sensor-to-Indicator Matching](04-collection-process/05-sensor-to-indicator-matching.md)
4. [Writing an RFI / Collection Request](04-collection-process/06-rfi-and-collection-request-workflow.md)
5. [Templates](08-templates-and-formats/)

### If you are running a joint board
- [JCMB — Joint Collection Management Board](02-joint-doctrine/jp-2-01-joint-and-national-intel-support.md#jcmb-joint-collection-management-board)
- [JIPCL — Joint Integrated Prioritized Collection List](02-joint-doctrine/jp-2-01-joint-and-national-intel-support.md#jipcl-joint-integrated-prioritized-collection-list)
- [Tasking Authority by Echelon](07-tools-and-systems/tasking-authority-reference.md)

---

## Doctrinal Anchors

This wiki is anchored in — and cites directly to — the following US military publications. Everything in this repo is traceable to one of these primary sources.

| Pub | Title | Owner |
|---|---|---|
| **JP 2-0** | Joint Intelligence | CJCS |
| **JP 2-01** | Joint and National Intelligence Support to Military Operations | CJCS |
| **JP 3-0** | Joint Campaigns and Operations | CJCS |
| **JP 3-60** | Joint Targeting | CJCS |
| **FM 2-0** | Intelligence | HQDA |
| **ATP 2-01** | Planning Requirements and Assessing Collection | HQDA |
| **ATP 2-01.3** | Intelligence Preparation of the Battlefield | HQDA |
| **FM 3-55** | Information Collection | HQDA |
| **AFDP 2-0** | Intelligence | HAF |
| **AFI 14-202** | Intelligence Standardization & Evaluation | SAF/A2/6 |
| **NWP 2-01** | Intelligence Support to Naval Operations | OPNAV N2/N6 |
| **NTTP 2-01.3** | Maritime Intelligence Preparation of the Operational Environment | OPNAV N2/N6 |
| **MCWP 2-10** | MAGTF Intelligence Operations | HQMC |
| **MCWP 2-14 / 2-6** | Counterintelligence / Intelligence Activities | HQMC |
| **ICD 113** | Functional Managers | DNI |
| **ICD 204** | National Intelligence Priorities Framework (NIPF) | DNI |
| **ICD 300** | Management, Integration, and Oversight of Intelligence Collection | DNI |

See the [Master Doctrine Reference Table](references/doctrine-publications-master-list.md) for URLs and an annotated glossary.

---

## Coverage Status

| Section | Status |
|---|---|
| Joint Doctrine (JP 2-0, JP 2-01, JP 3-0, JP 3-60) | ✅ Complete |
| Army Doctrine (FM 2-0, ATP 2-01, ATP 2-01.3, FM 3-55) | ✅ Complete |
| Air Force Doctrine (AFDP 2-0, AOC/ISRD, DCGS-AF) | ✅ Complete |
| Navy Doctrine (NWP 2-01, MOC/MIOC, ONI) | ✅ Complete |
| Marine Corps Doctrine (MCWP 2-10, 2-14, MIG) | ✅ Complete |
| National / IC Integration (NGA, NSA, NRO, DIA, NIPF) | ✅ Complete |
| Airborne Unmanned Platforms (13 platforms) | ✅ Complete |
| Airborne Manned Platforms (12 platforms) | ✅ Complete |
| Space-Based Platforms (5 platforms + commercial) | ✅ Complete |
| Maritime Platforms (5 platforms) | ✅ Complete |
| Ground / SOF Platforms (4 platforms) | ✅ Complete |
| Cyber / National SIGINT | ✅ Complete |
| Process Pages (PIR→EEI, ISR Sync, RFI) | ✅ Complete |
| Templates (PIR, EEI, IC Matrix, ISR Sync, RFI) | ✅ Complete |
| Discipline Deep-Dives (HUMINT/SIGINT/GEOINT/MASINT/OSINT/TECHINT/CYBINT) | ✅ Complete |
| Case Studies | 🟡 Stubbed — open for contribution |

---

## Companion Repos in the Raven Conspiracy

- **[Inquisitor](https://github.com/Raven-Conspiracy/Inquisitor)** — Intelligence orchestrator with 8 domain agents (HUMINT/SIGINT/GEOINT/OSINT/MASINT/AllSource/CI/TargetingIntel) trained on a 30M-token doctrinal corpus. This wiki is the human-readable companion to the TargetingIntel and AllSource agents.
- **[The Red Ledger](https://github.com/Raven-Conspiracy/the-red-ledger)** — Russian Ground Forces OOB intelligence application. Operational consumer of collection products.
- **[munitions-uav-wiki](https://github.com/Raven-Conspiracy/munitions-uav-wiki)** — Sister wiki on kinetic/non-kinetic effects, UAVs, and EW.
- **[The Fellowship](https://github.com/Raven-Conspiracy/The-Fellowship)** — AI orchestration layer that routes between Conspiracy repos.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the contribution rules. The short version:

1. **Cite or it didn't happen.** Every claim links to an unclassified doctrinal source.
2. **No classified content. No CUI. No tactics, techniques, or signatures not already in the public domain.** When in doubt, leave it out.
3. **Doctrinal voice over speculation.** Quote directly from publications when possible.
4. **One platform per file, one doctrinal pub per file** in their respective sections.
5. **All PRs reviewed by a maintainer** before merge.

---

## Disclaimer

This is an **independent reference work** maintained by Task Force Raven. It is **not** an official publication of the US Department of Defense, the Joint Staff, any service, or any element of the US Intelligence Community. Doctrinal interpretations are the contributors' best-effort synthesis of unclassified, publicly available materials. **Use it to learn — not as a primary source for operational planning.** When operating, go to the original publication.

---

*"The Emperor protects. The collection plan does the actual work."*
