# CYBINT — Cyber and Digital Network Intelligence

_Disciplines › CYBINT_

---

> **Classification:** UNCLASSIFIED. All content grounded in publicly available US doctrine and IC publications. See [CONTRIBUTING.md](../CONTRIBUTING.md) for sourcing rules.

## 1. Doctrinal Definition

### Taxonomic Overview

"CYBINT" is a contested term. Across the US national security enterprise, cyber-derived intelligence travels under at least three distinct labels depending on the functional community discussing it: **CYBINT** (cyber intelligence as an INT discipline in its own right), **DNI** (Digital Network Intelligence, a formal NSA/SIGINT sub-discipline), and **CTI** (Cyber Threat Intelligence, a broader analytic synthesis discipline). A fourth frame—cyber as a *domain* supporting all operations rather than as an INT source in itself—further complicates the taxonomy. Understanding which label applies requires knowing which community produced the product and which legal authority governed its collection.

### JP 2-0 Treatment

[JP 2-0, *Joint Intelligence*](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/) is the keystone document for joint intelligence operations. It does not establish "CYBINT" as a formally designated INT discipline in the way HUMINT, SIGINT, GEOINT, or MASINT are designated. Instead, JP 2-0 addresses cyber threats and adversary use of cyberspace as part of the broader all-source intelligence requirement. The J-2 intelligence directorate is responsible for providing commanders understanding of the operational environment, including adversaries' cyber capabilities, vulnerabilities, and targeting interests. Cyber-specific intelligence requirements are generated through the standard intelligence process—planning and direction, collection, processing and exploitation, analysis and production, dissemination, and feedback. [JP 2-01, *Joint and National Intelligence Support to Military Operations*](https://www.usna.edu/Training/_files/jp2_01_20170705v2.pdf) explicitly describes intelligence support to cyberspace operations and cyberspace ISR considerations as part of the joint intelligence enterprise, noting that intelligence provides commanders with "a better understanding of an adversary's use of cyberspace, an adversary's vulnerabilities, and reliance on cyberspace and potential exploitation opportunities."

### JP 3-12 Treatment

[JP 3-12, *Cyberspace Operations*](https://www.onlinelibrary.iihl.org/wp-content/uploads/2021/05/2018-JP-3-12-Cyberspace-Operations.pdf) (current version December 2022; public summary sourced from June 2018 edition and [DefenseScoop reporting](https://defensescoop.com/2023/05/12/new-dod-doctrine-officially-outlines-and-defines-expeditionary-cyberspace-operations/)) defines **cyberspace operations (CO)** as "the employment of cyberspace capabilities where the primary purpose is to achieve objectives in or through cyberspace." Military CO are organized into three mission types: **Offensive Cyberspace Operations (OCO)**, intended to project power in and through foreign cyberspace; **Defensive Cyberspace Operations (DCO)**, executed to defend the DoD Information Network (DODIN) or other designated cyberspace; and **DODIN Operations**, which secure, configure, operate, extend, maintain, and sustain DoD cyberspace. JP 3-12 also recognizes *national-level intelligence operations in and through cyberspace*, conducted by national intelligence organizations in response to national intelligence priorities and distinct from military CO. The December 2022 revision introduced the formal definition of **expeditionary cyberspace operations**: "[c]yberspace operations that require the deployment of cyberspace forces within the physical domains," reflecting lessons from close-access operations in contested environments.

JP 3-12 defines **cyberspace** as "a global domain within the information environment consisting of the interdependent networks of information technology infrastructures and resident data, including the Internet, telecommunications networks, computer systems, and embedded processors and controllers." The DODIN is the DoD's portion of cyberspace: "the set of information capabilities and associated processes for collecting, processing, storing, disseminating, and managing information on-demand to warfighters, policy makers, and support personnel." JP 3-12 uses a three-layer cyberspace model—physical network layer, logical network layer, and cyber-persona layer—to support planning and targeting.

### DNI: Digital Network Intelligence as a SIGINT Sub-Discipline

**DNI (Digital Network Intelligence)** is the NSA's formal designation for SIGINT collected from and about digital computer networks. It is not a separately listed INT discipline in JP 2-0 but is treated within the SIGINT functional account. As [NSA's public SIGINT mission statement](https://www.nsa.gov/signals-intelligence/) explains, NSA "provides foreign signals intelligence to our nation's policymakers and military forces." DNI represents the digital-network facet of NSA's SIGINT mission—the collection, processing, analysis, and reporting of intelligence derived from data transiting or residing in networked computing systems, as distinct from traditional COMINT (voice/communications) or ELINT (electronic emissions). Because DNI is a SIGINT sub-discipline, it is governed by the same legal framework as all NSA SIGINT: Executive Order 12333, the Foreign Intelligence Surveillance Act (FISA), and NSA's statutory authority.

### CTI: Cyber Threat Intelligence as an Analytic Discipline

**CTI (Cyber Threat Intelligence)** is a broader analytic discipline that synthesizes information from multiple sources—SIGINT, HUMINT, OSINT, commercial threat feeds, vulnerability data, and incident reports—to characterize adversary intent, capability, and activity in cyberspace. CTI is the common currency of the commercial cybersecurity sector and has been progressively formalized in the US government through CISA, NSA's Cybersecurity Directorate, USCYBERCOM's public threat disclosures, and inter-agency sharing mechanisms. Unlike DNI, which is a collection sub-discipline, CTI is defined by its analytic output—threat actor profiles, indicator sets, campaign assessments, and TTPs—regardless of the collection source.

### Cyber as INT vs. Cyber as Domain

A persistent taxonomic tension exists between treating cyber as an intelligence *source* (analogous to SIGINT or GEOINT) and treating cyber as an operational *domain* in which all functions—command and control, fires, maneuver, intelligence—occur. JP 3-12 and JP 2-0 reflect the domain framing: cyberspace is one of five operational domains (land, sea, air, space, cyber), and intelligence support to cyber operations follows the same principles as intelligence support to operations in any other domain. However, NSA's DNI construct treats network-derived data as a distinct collection source, parallel to communications intercept and radar returns. Commercial CTI practice tends toward the domain view—treating cyber intelligence as a cross-INT synthesis product about threats operating in the cyber domain. This wiki covers all three framings.

---

## 2. Functional Manager (ICD 113)

### ICD 113 Framework

[ICD 113, *Functional Managers*](https://www.intel.gov/assets/documents/intelligence-community-directives/ICD_113.pdf) (effective 19 May 2009), issued by the Director of National Intelligence under the authority of EO 12333, establishes the Functional Manager construct. Functional Managers are "the principal advisors to the DNI on the performance of their respective functions" and serve as cognizant authorities over the totality of activities for an enterprise-wide intelligence function across all IC elements. Their role is distinct from the IC element head, who is responsible for executing that element's mission. Functional Managers set tradecraft standards, advise on resource allocation, and evaluate the performance of their function against the National Intelligence Priorities Framework (NIPF).

### NSA/CSS: Functional Manager for SIGINT (Including DNI)

**NSA/CSS** is the Functional Manager for SIGINT across the IC. This explicitly covers DNI as a SIGINT sub-discipline. Under [NSA's public mission](https://www.nsa.gov/signals-intelligence/), the Agency "collects, processes, analyzes, produces, and disseminates signals intelligence information for foreign intelligence and counterintelligence purposes." NSA's Cybersecurity Collaboration Center also provides unclassified threat intelligence and defensive capabilities to the Defense Industrial Base (DIB), offering non-public indicators of known malicious activity derived from SIGINT and cybersecurity expertise. As the SIGINT Functional Manager, NSA sets tradecraft standards for DNI collection, processing, and reporting across all service cryptologic components.

### USCYBERCOM: Combatant Command for Cyberspace Operations

**US Cyber Command (USCYBERCOM)**, established in 2009 as a sub-unified command and elevated to a full unified combatant command in 2018, is the DoD entity responsible for directing, synchronizing, and coordinating cyberspace planning and operations. Per [USCYBERCOM's public mission](https://www.cybercom.mil/About/History/), the Command "defends the Department of Defense information systems, supports joint force commanders with cyberspace operations, and defends the nation from significant cyberattacks." USCYBERCOM does not hold an ICD 113 Functional Manager designation for intelligence, but it is the combatant command authority over the Cyber Mission Force and sets operational and training standards for military cyberspace forces. USCYBERCOM also coordinates intelligence gain/loss equities with the IC when planning military cyber operations.

### DIA: Functional Manager for MASINT and Defense Intelligence

**DIA (Defense Intelligence Agency)** is the Functional Manager for MASINT under the IC and serves as the DoD's all-source defense intelligence organization. For cyber-relevant purposes, DIA provides timely, objective military intelligence to warfighters and defense planners—including foreign intelligence threats to DoD cyber systems—and supports combatant commanders with cyber-related threat assessments. DIA's role as cited in [JP 3-12](https://www.onlinelibrary.iihl.org/wp-content/uploads/2021/05/2018-JP-3-12-Cyberspace-Operations.pdf) is to "provide timely, objective, and cogent military intelligence to warfighters, defense planners, and defense and national security policy makers," encompassing foreign cyber capabilities and orders of battle.

### DCSA: Insider Threat and Supply Chain

**DCSA (Defense Counterintelligence and Security Agency)** performs the Functional Manager role for counterintelligence within DoD security and is the lead agency for insider threat programs in the defense industrial base. [DCSA and NCSC jointly publish SCRM guidance](https://www.dni.gov/index.php/safeguarding-science/supply-chain-risk-management) addressing the exploitation of ICT supply chains by Foreign Intelligence Entities (FIE). For cyber intelligence, DCSA's contribution centers on the human vector—cleared personnel, contractors, and supply chain actors who represent adversary access pathways into DoD and DIB networks.

### ODNI / National Cyber Director Coordination

The ODNI coordinates national cyber intelligence priorities through the National Intelligence Priorities Framework. The [Office of the National Cyber Director (ONCD)](https://www.whitehouse.gov/oncd/), established by the National Defense Authorization Act of 2021, coordinates federal cybersecurity policy and cyber workforce strategy at the national level. ONCD is not an intelligence entity but coordinates across agencies—including NSA, CISA, USCYBERCOM, and the IC—on national cyber threat assessments and strategy. The [DNI's Annual Threat Assessment](https://industrialcyber.co/reports/odni-report-us-critical-infrastructure-faces-escalating-cyber-risks-from-china-russia-iran-and-north-korea/) provides the IC's authoritative unclassified assessment of foreign cyber threats, identifying China, Russia, Iran, and North Korea as the principal state cyber adversaries.

### CISA: Defensive Role

**CISA (Cybersecurity and Infrastructure Security Agency, DHS)** is not a military intelligence organization but is operationally significant to the cyber intelligence enterprise. CISA leads federal civilian network defense, issues public advisories on threats and vulnerabilities, and co-produces Joint Cybersecurity Advisories (JCAs) with NSA, FBI, and USCYBERCOM. These unclassified JCAs represent the public face of US government CTI. CISA coordinates with DCSA and NCSC on [supply chain integrity](https://www.dcsa.mil/Portals/128/Documents/about/err/CDSE_Pulse_April2023.pdf) and hosts the ICT Supply Chain Resource Library.

---

## 3. Collection Authorities and Legal Anchors

### JP 3-12 Authority Framework

[JP 3-12](https://www.onlinelibrary.iihl.org/wp-content/uploads/2021/05/2018-JP-3-12-Cyberspace-Operations.pdf) establishes that "DoD conducts CO consistent with US domestic law, applicable international law, and relevant USG and DoD policies." Cyberspace forces operating outside the DODIN are "generally limited to operating in gray and red cyberspace only, unless they are issued different rules of engagement." The Secretary of Defense (SecDef), through DoD, "uses cyberspace capabilities to shape cyberspace and provide integrated offensive and defensive cyberspace capabilities." The CDRUSCY BERCOM, as coordinating authority for CO, plans, coordinates, integrates, synchronizes, and conducts activities to direct security of the DODIN and, when directed, conduct military CO external to the DODIN in support of national objectives.

### Title 10 vs. Title 50

[Title 10 of the US Code](https://uscode.house.gov/view.xhtml?req=granuleid%3AUSC-prelim-title10-section394&num=0&edition=prelim) governs military forces and authorizes the Secretary of Defense to direct DoD agencies and commands, including combatant commands. Title 10, Section 394 addresses authorities for military cyber operations. [Title 50](https://www.americansecurityproject.org/ASP%20Reports/Ref%200073%20-%20U.S.C.%20Title%2010,%20Title%2022,%20and%20Title%2050.pdf) governs intelligence community activities, establishing CIA covert action authority and SecDef control over intelligence agencies within DoD (NSA, DIA, NRO, NGA). As analyzed in [*Cyber Defense Review* (Fall 2021)](https://cyberdefensereview.army.mil/Portals/6/Documents/2021_fall/07_Albert_Barth_Thompson_CDR_V6N4-Fall_2021.pdf): "Title 10 delineates the functions, duties, and responsibilities of the US military and gives the Secretary of Defense control over all DoD agencies and commands…Title 50 establishes the IC's authorities, and constitutes CIA's authority to conduct intelligence operations and covert actions." The critical distinction: **intelligence gathering** that exploits a network to collect information without altering, controlling, or degrading its function is generally treated as a Title 50 intelligence activity; **operations** that alter, control, or degrade a network cross into Title 10 military activity. This line is blurred in practice because cyber operations often require collection to prepare the operational environment. The 2019 NDAA (Section 1642) amended Title 10 to explicitly empower USCYBERCOM to conduct operations short of hostilities in cyberspace and to designate "clandestine military activity in cyberspace" as a "traditional military activity," removing some Title 50-induced interagency friction.

### USCYBERCOM Authorities: The Cyber Mission Force (CMF)

USCYBERCOM's operational arm is the [Cyber Mission Force (CMF)](https://www.cybercom.mil/Media/News/Article/3206393/cyber-101-cyber-mission-force/), consisting of 135 teams organized into four types:

- **Cyber National Mission Teams (NMTs):** Defend the nation by identifying adversary activity, blocking attacks, and maneuvering to defeat adversary cyber actors. Aligned under the **Cyber National Mission Force (CNMF)**, activated January 2014.
- **Cyber Combat Mission Teams (CMTs):** Conduct military cyberspace operations in support of combatant command priorities and missions.
- **Cyber Protection Teams (CPTs):** Defend the DODIN, protect priority missions, and prepare cyber forces for combat.
- **Cyber Support Teams (CSTs):** Provide analytic and planning support to National Mission and Combat Mission teams.

Per [USCYBERCOM's FOC announcement (2018)](https://www.cybercom.mil/Media/News/News-Display/Article/1524492/cyber-mission-force-achieves-full-operational-capability/), the CMF reached Full Operational Capability in 2018 with approximately 6,200 military and civilian personnel. JFHQ-DODIN (now designated [Department of Defense Cyber Defense Command — DCDC — since May 2025](https://defensescoop.com/2025/05/30/cybercom-jfhq-dodin-dcdc-designated-sub-unified-command/)) provides command and control of DODIN operations and defensive cyberspace operations globally.

### Service Cyber Components

Each military service provides cyber forces to USCYBERCOM through a Service Cyber Component (SCC):

- **ARCYBER (US Army Cyber Command):** Headquartered at Fort Gordon (now Fort Eisenhower), Georgia. Provides 41 CMF teams. Subordinate units include the [780th Military Intelligence Brigade (Cyber)](https://www.arcyber.army.mil/Organization/Units/) and the 1st Information Operations Command (inactivated 2025 per [INSCOM reporting](https://www.usainscom.army.mil/MSCs/780th-MI/Praetorian-News/)).
- **AFCYBER / 16th Air Force (Air Forces Cyber):** [16th AF](https://www.16af.af.mil/About-Us/) is headquartered at JBSA-Lackland, Texas. It serves simultaneously as the Service Cryptologic Component to NSA/CSS and the Service Cyber Component to USCYBERCOM, with approximately 45,000 Total Force Airmen across 123 global locations. Subordinate wings include the 67th Cyberspace Wing and 70th ISR Wing.
- **FLTCYBER (US Fleet Cyber Command) / US Tenth Fleet:** Based at Fort Meade, Maryland. [Fleet Cyber Command](https://www.fcc.navy.mil) is responsible for Navy information network operations, offensive and defensive cyberspace operations, space operations, and SIGINT, with 13,000+ billets and 40 Cyber Mission Force units. TENTH Fleet is its operational arm.
- **MARFORCYBER (US Marine Corps Forces Cyberspace Command):** The Marine Corps' service cyber component.
- **SPACECOM Cyber Component:** US Space Command receives cyber support through service components; Space Force cyber forces (Delta units) support SPACECOM missions.
- **SOCOM Cyber:** US Special Operations Command integrates cyber capabilities into special operations; expeditionary cyberspace operations support SOF.
- **CGCYBER (Coast Guard Cyber Command):** DHS-aligned but supports national cyber missions.

### NSA SIGINT Authority over DNI

NSA's statutory authority for SIGINT collection—including DNI—derives from the National Security Act of 1947, EO 12333, National Security Council Intelligence Directive (NSCID) 6, and FISA. [Per NSA's public mission statement](https://www.nsa.gov/signals-intelligence/), NSA "collects, processes, analyzes, produces, and disseminates signals intelligence (SIGINT) information for foreign intelligence and counterintelligence purposes as part of NSA's role as a combat support agency in the Department of War." NSA provides direct cryptologic and cyberspace support to combatant command JIOCs through the Central Security Service (CSS) representative, and provides "signals intelligence support and cybersecurity guidance and assistance to DoD components and national customers" per JP 3-12.

### Persistent Engagement and Defend Forward

The 2018 DoD Cyber Strategy publicly articulated the **Defend Forward / Persistent Engagement** operational doctrine. Per [USCYBERCOM's public explanation](https://www.cybercom.mil/Media/News/Article/3198878/cyber-101-defend-forward-and-persistent-engagement/): "The United States will defend forward to disrupt malicious cyber activity at its source, including activity that falls below the level of armed conflict." [USCYBERCOM's 2018 Vision document](https://www.cybercom.mil/portals/56/documents/uscybercom%20vision%20april%202018.pdf) establishes that the United States must "increase resiliency, defend forward as close as possible to the origin of adversary activity, and persistently contest malicious cyberspace actors to generate continuous tactical, operational, and strategic advantage." Hunt Forward Operations (HFOs), conducted at partner invitation, are the public operationalization of this doctrine—USCYBERCOM operators work alongside allied partners to identify malicious activity in host-nation networks and share findings publicly.

---

## 4. Primary Collection Methods / Sub-Disciplines

### DNI — Digital Network Intelligence

**DNI** is the NSA SIGINT sub-discipline for collecting intelligence from and about digital networks. Traditional SIGINT sub-disciplines (COMINT, ELINT, FISINT) were designed for voice communications, radar emissions, and telemetry signals. DNI extends the SIGINT architecture to IP-based networks, capturing traffic metadata and content from global data flows, fiber optic infrastructure, and computing systems—subject to applicable legal authorities. DNI products inform national-level intelligence consumers, combatant commanders, and the broader IC on foreign network architecture, adversary cyber actor activity, and communications patterns. The Central Security Service coordinates DNI support from NSA to military commands through theater- and forward-deployed cryptologic support.

### CTI — Cyber Threat Intelligence

**CTI** synthesizes intelligence from all available sources—classified SIGINT and DNI products, HUMINT reporting, counterintelligence investigations, OSINT, commercial threat feeds, incident response data, and vulnerability research—to produce assessments of adversary intent, capability, and activity. CTI is both a product and a process. As an analytic discipline, CTI characterizes adversary actors (who), campaigns (what activity), TTPs (how), infrastructure (where), and objectives (why). In the US government context, the NSA Cybersecurity Directorate, CISA, and USCYBERCOM produce unclassified CTI in the form of Joint Cybersecurity Advisories and malware analysis reports (MARs). Commercial firms such as Mandiant (now Google), CrowdStrike, and Microsoft MSTIC publish extensive open-source CTI that the government both consumes and contributes to.

### CNE Support to CYBINT

**Computer Network Exploitation (CNE)** refers to intelligence-gathering activities enabled by gaining access to adversary or neutral computing systems—obtaining information while not altering, controlling, or degrading the targeted system's function. At the unclassified, public level, JP 3-12 acknowledges that cyberspace maneuver in "gray and red cyberspace is a cyberspace exploitation action" and includes "gaining access to adversary [systems] for intelligence gathering." CNE represents the classified intersection of Title 50 intelligence operations and the technical cyber collection mission; specific CNE programs, methods, and authorities remain classified. At the doctrinal level, CNE is distinct from CNO-D (Computer Network Attack, an OCO mission) precisely because it collects rather than degrades.

### Open-Source Cyber (Overlap with OSINT)

Open-source intelligence in the cyber domain encompasses commercial threat intelligence feeds, vendor security advisories, academic vulnerability disclosures, security conference research (DEF CON, Black Hat), CVE/NVD entries, malware repositories (VirusTotal, MalwareBazaar), passive DNS data, and public incident reports. OSINT cyber collection is foundational to CTI: much adversary infrastructure, TTP characterization, and indicator data originates in publicly available research before being correlated with classified collection. USCYBERCOM publicly releases malware samples and indicators through its CNMF Malware Alert (MA) program and via US-CERT/CISA advisories, operationalizing the "share forward" principle.

### Insider Threat Intelligence

Insider threat intelligence focuses on cleared personnel, contractors, and supply chain actors who may represent adversarial access to sensitive systems—either as witting agents or as unwitting vectors exploited through social engineering or malware. DCSA is the DoD's lead for insider threat programs in the cleared contractor community. The National Insider Threat Task Force (NITTF), co-chaired by the DNI and Attorney General, coordinates the broader federal insider threat program. For cyber systems, insider threats manifest as unauthorized data exfiltration, sabotage of security controls, and provision of credentials to foreign intelligence entities.

### Supply Chain Intelligence for ICT

The ICT supply chain represents a major adversary access vector: compromised hardware components, malicious firmware, backdoored software libraries, and counterfeit microelectronics can pre-position adversary access in DoD systems before they are fielded. [DCSA and NCSC SCRM guidance](https://www.dni.gov/index.php/safeguarding-science/supply-chain-risk-management) identifies Foreign Intelligence Entities (FIEs), criminals, and strategic competitors as supply chain threats. Intelligence collection in this area focuses on adversary acquisition activities, manufacturing infiltration, and software development supply chain attacks (e.g., SolarWinds-style compromises of trusted software update mechanisms).

### Vulnerability Research

The public CVE (Common Vulnerabilities and Exposures) ecosystem—managed by MITRE under NIST's NVD (National Vulnerability Database)—provides an unclassified catalog of software vulnerabilities. Government agencies (including NSA, CISA, and USCYBERCOM) contribute to CVE through coordinated vulnerability disclosure and publish advisories on actively exploited vulnerabilities. Classified vulnerability research by USG agencies identifies zero-day vulnerabilities before public disclosure; these represent collection and operational equities subject to the interagency Vulnerabilities Equities Process (VEP), established under EO 13694 and publicly described in a 2017 White House charter.

### Adversary TTP Characterization — MITRE ATT&CK

The [MITRE ATT&CK framework](https://attack.mitre.org) is the public standard for characterizing adversary TTPs in the cyber domain. ATT&CK provides a matrix of adversary behaviors across 14 tactical categories (Reconnaissance through Impact) with hundreds of specific techniques and sub-techniques, each mapped to real-world adversary groups and documented with open-source evidence. ATT&CK is used across the IC, DoD, and commercial CTI community as a common language for describing adversary behavior, identifying detection gaps, and scoring threat actors. MITRE ATT&CK for Enterprise currently documents 12 Reconnaissance techniques, 9 Resource Development, 11 Initial Access, and so on through 15 Impact techniques.

---

## 5. Signature / Indicator Catalog — What CYBINT Sees

CYBINT/CTI collection and analysis targets a layered indicator space. The [MITRE ATT&CK framework](https://attack.mitre.org) and the [Pyramid of Pain](https://www.sans.org/tools/the-pyramid-of-pain) (discussed in Section 7) together define the taxonomy of what is observable and the relative value of each indicator type.

### Adversary Cyber Actors and APT Attribution

Advanced Persistent Threat (APT) groups are nation-state-sponsored or -affiliated cyber actors conducting sustained intelligence collection, pre-positioning, or disruptive operations. The [ODNI Annual Threat Assessment 2026](https://industrialcyber.co/reports/odni-report-us-critical-infrastructure-faces-escalating-cyber-risks-from-china-russia-iran-and-north-korea/) identifies **China** as "the most active and persistent cyber threat to the U.S. government, private-sector, and critical infrastructure networks," **Russia** as posing "a persistent, advanced cyber attack and foreign intelligence threat," **Iran** as maintaining "a persistent intent to target the U.S. and its allies," and **North Korea** as operating a "sophisticated and agile" cyber program focused on espionage, financial crime (cryptocurrency theft), and capability development. Commercial CTI vendors (CrowdStrike, Mandiant, Microsoft, SentinelOne) maintain APT tracking under proprietary naming conventions (e.g., FANCY BEAR/APT28 for Russia-GRU; COZY BEAR/APT29 for Russia-SVR; VOLT TYPHOON for China-linked infrastructure pre-positioning).

### TTPs (Tactics, Techniques, Procedures) per MITRE ATT&CK

TTPs are the behavioral fingerprint of an adversary: how they gain initial access, establish persistence, escalate privileges, move laterally, collect data, and exfiltrate. TTPs are the highest-value indicator type because they reflect an adversary's learned methods that are costly to change. ATT&CK documents over 200 techniques across 14 tactical categories; specific APT groups are mapped to their observed technique sets, enabling defenders to identify actor-specific behavioral signatures.

### Indicators of Compromise (IOCs)

IOCs are technical artifacts that indicate a system has been compromised: IP addresses used for C2 communications, domain names of adversary infrastructure, file hashes of malicious tools, email sender addresses used in spear-phishing, SSL certificate hashes, and network traffic signatures. IOCs are shared through structured formats (STIX/TAXII) via automated threat sharing platforms (AIS, ISACs, CISAs CISA AIS). IOCs have a short operational shelf life—adversaries rotate infrastructure rapidly—but are critical for immediate defensive action and network detection.

### Infrastructure: Command and Control (C2), Staging, and Exfiltration

Adversary cyber infrastructure is a high-value CYBINT target: C2 servers, staging servers used to pre-position tools prior to an operation, proxy chains used to mask origin, and exfiltration nodes used to transmit collected data to adversary-controlled storage. Network mapping of adversary infrastructure reveals patterns, shared code, and actor attribution opportunities. USCYBERCOM and NSA publicly release infrastructure indicators through the CNMF malware alert program and joint advisories.

### Tooling and Malware Families

Adversary cyber tooling—custom and commercial malware, implants, loaders, remote access tools (RATs), and exploit frameworks—constitutes another CYBINT signature set. Specific malware families (e.g., SUNBURST for SolarWinds, EMOTET, COBALTSTRIKE) are documented in public reporting and carry attribution value. MITRE ATT&CK's Software database catalogs malware families, their techniques, and the threat groups known to use them.

### Targeting Interests

Understanding which sectors, systems, and data types an adversary prioritizes is an intelligence objective. ODNI assessments and government advisories consistently identify critical infrastructure sectors—defense industrial base, energy, water, financial, healthcare, and communications—as adversary targeting priorities. USCYBERCOM hunt-forward operations specifically seek to understand adversary targeting patterns in partner nations' networks.

### Capability Development

Monitoring adversary capability development—acquisition of zero-day exploits, development of new malware strains, testing of attack infrastructure, and investment in cryptographic attack capabilities—provides strategic warning. Indicators include dark web marketplace activity, vulnerability researcher recruitment, government contractor compromise aimed at capability theft, and observed use of previously unknown techniques against early targets (pre-deployment indicators).

### Network Mapping

Both friendly and adversary network topology is a CYBINT objective. Understanding the DODIN's own topology is essential for defensive operations; understanding adversary networks enables offensive operations and supports ISR to find adversary command nodes and dependencies. JP 3-12 frames "access to key terrain in cyberspace" as an intelligence and operations planning priority.

### Pre-Attack Indicators

Pre-attack indicators include adversary reconnaissance activity (scanning, spear-phishing reconnaissance, open-source research), access preparation (establishing footholds in peripheral systems), and staging (pre-positioning tools). Identifying these indicators before exploitation begins is the intelligence contribution to anticipatory defense. MITRE ATT&CK's Reconnaissance tactic (12 techniques) and Resource Development tactic (9 techniques) document the observable signatures of pre-attack phases.

### Influence Operations and Information Operations Infrastructure

Cyber infrastructure supports adversary influence operations: sockpuppet account networks, state-sponsored media amplification infrastructure, hack-and-leak operation C2, and computational propaganda platforms are targets of CYBINT collection. Joint Cybersecurity Advisories and FBI/CISA reports have documented foreign influence infrastructure (e.g., Russian Internet Research Agency, Iranian "Endless Mayfly" operations). JP 3-13 (*Information Operations*) treats information operations as an adjacent but distinct mission area, with cyber intelligence supporting both the detection and characterization of adversary IO campaigns.

---

## 6. PED Chain

The CYBINT Processing, Exploitation, and Dissemination (PED) chain spans national-level cryptologic agencies through theater and tactical cyber organizations, with commercial CTI feeds providing an increasingly integrated supplementary stream.

### NSA Cryptologic Centers (DNI as SIGINT)

NSA, as the SIGINT Functional Manager and central authority for DNI, anchors the national-level PED chain. NSA processes and exploits digital network collection through its classified cryptologic infrastructure and produces finished intelligence products for national-level consumers, combatant commands, and other IC members. The Central Security Service (CSS), composed of the Service Cryptologic Components (SCCs), extends NSA's SIGINT authority into the military services. [JP 2-01](https://www.usna.edu/Training/_files/jp2_01_20170705v2.pdf) notes that "through the National Security Agency/Central Security Service representative, the National Security Agency provides direct cryptologic and cyberspace support to the CCMD JIOCs through the Central Security Service."

### USCYBERCOM: JFHQ-DODIN (DCDC) and JFHQ-Cyber

The [Department of Defense Cyber Defense Command (DCDC)](https://www.dcdc.mil), formerly JFHQ-DODIN (redesignated May 2025), "leads DoD's unified force approach to network operations, security, and defense across the DODIN." It provides command and control for DODIN defensive operations globally. JFHQ-Cyber is the service-aligned combatant command-support element through which USCYBERCOM delivers cyber capabilities to geographic combatant commanders. Per the [DONCIO](https://www.doncio.navy.mil/Chips/ArticleDetails.aspx?ID=5666), USCYBERCOM designated Fleet Cyber Command as the Joint Force Headquarters-Cyber (JFHQ-C) to support US Pacific Command and US Southern Command in full-spectrum cyberspace operations planning, command and control, and execution.

### 16th Air Force / AFCYBER

[16th Air Force (Air Forces Cyber)](https://www.16af.af.mil/About-Us/) at JBSA-Lackland serves simultaneously as the Air Force SCC, providing SIGINT/DNI support to NSA/CSS, and as AFCYBER, the Air Force Service Cyber Component to USCYBERCOM. Key 16 AF cyber PED elements include the **67th Cyberspace Wing** (offensive/defensive cyber operations) and the **70th ISR Wing** at Fort Meade (signals intelligence processing and exploitation). As JFHQ-Cyber (Air Force), 16 AF provides offensive and defensive cyber C2 and assessments for USCYBERCOM, EUCOM, SPACECOM, and STRATCOM. The [480th ISR Wing](https://www.af.mil/About-Us/Fact-Sheets/Display/Article/104525/air-force-distributed-common-ground-system/) operates the AF DCGS system, exploiting data from U-2, RQ-4 Global Hawk, MQ-9, and other ISR platforms.

### ARCYBER: 780th MI Brigade (Cyber)

The [780th Military Intelligence Brigade (Cyber)](https://www.arcyber.army.mil/Organization/Units/) at Fort Meade is "the Army's sole offensive cyberspace operations brigade" per [INSCOM public reporting](https://www.usainscom.army.mil/MSCs/780th-MI/Praetorian-News/). It provides teams to support National and Combatant Command offensive cyberspace operations requirements and maintains the Army's cyberspace operations infrastructure. Subordinate battalions include the 781st MI Battalion and 782d MI Battalion. The [Wikipedia entry on the 780th](https://en.wikipedia.org/wiki/780th_Military_Intelligence_Brigade_(United_States)) notes that the 11th Cyber Battalion activated on October 16, 2022, further expanding Army offensive cyber capacity.

### FLTCYBER / NIOC / Tenth Fleet

[US Fleet Cyber Command / TENTH Fleet](https://www.fcc.navy.mil) is responsible for Navy information network operations, offensive and defensive cyberspace operations, space operations, and SIGINT. TENTH Fleet's operational structure includes numerous **Navy Information Operations Commands (NIOCs)** at locations globally (Menwith Hill, Sugar Grove, Misawa, Texas, Georgia, Hawaii, Maryland, Colorado, and others) that provide SIGINT collection and cyber intelligence support. NIOCs serve as the Navy's principal SIGINT collection and processing nodes, operating under Fleet Cyber Command as the Navy's SCC for NSA/CSS.

### Commercial CTI Integration

Commercial CTI firms—Mandiant (Google), CrowdStrike, Microsoft MSTIC, Palo Alto Unit 42, SentinelOne, Recorded Future, and others—produce threat intelligence that the US government both consumes and augments. NSA's Cybersecurity Collaboration Center provides [DIB Cybersecurity Services](https://www.nsa.gov/about/cybersecurity-collaboration-center/dib-cybersecurity-services/) to defense contractors using non-public indicators from SIGINT. CISA's Automated Indicator Sharing (AIS) program enables bidirectional sharing of machine-readable CTI between government and private sector. Government-sponsored ISACs (Information Sharing and Analysis Centers) across 16 critical infrastructure sectors provide sector-specific threat intelligence.

### DCGS Integration

The **Distributed Common Ground System (DCGS)** is the DoD family of ISR processing systems. [DCGS-A](https://www.dote.osd.mil/Portals/97/pub/reports/FY2016/army/2016dcgs-a.pdf) is the Army service component, fusing intelligence information from 700+ sources to produce enemy situational awareness products from battalion to Echelons Above Corps. The [AF DCGS](https://www.af.mil/About-Us/Fact-Sheets/Display/Article/104525/air-force-distributed-common-ground-system/) (AN/GSQ-272 SENTINEL) is the Air Force's primary ISR analysis and exploitation system. DCGS feeds connect through the DCGS Integration Backbone (DIB), a modular, standards-based data services architecture for enterprise information sharing, enabling cyber-relevant intelligence to flow from collection platforms through tactical exploitation nodes to finished all-source intelligence products.

---

## 7. Exploitation Tradecraft (Unclassified, Doctrinal)

### MITRE ATT&CK Framework

The [MITRE ATT&CK framework](https://attack.mitre.org) (Adversarial Tactics, Techniques, and Common Knowledge) is the authoritative public taxonomy for adversary behavior in cyberspace. Maintained by MITRE Corporation, ATT&CK catalogues 14 tactical categories (Reconnaissance, Resource Development, Initial Access, Execution, Persistence, Privilege Escalation, Stealth, Defense Impairment, Credential Access, Discovery, Lateral Movement, Collection, Command and Control, Exfiltration, Impact) with hundreds of documented techniques and sub-techniques. Each technique entry includes procedure examples from observed real-world adversary campaigns, defensive mitigations, and detection methods. ATT&CK matrices exist for Enterprise (Windows/Linux/macOS/network/cloud), Mobile, and ICS environments. The framework is used by US government agencies, allied nations, and commercial CTI teams as a common language for threat characterization, detection engineering, and red-team assessment.

### Diamond Model of Intrusion Analysis

The [Diamond Model of Intrusion Analysis](https://www.activeresponse.org/wp-content/uploads/2013/07/diamond.pdf), developed by Sergio Caltagirone, Andrew Pendergast, and Christopher Betz and published as a US Department of Defense technical report in 2013, provides a formal scientific framework for cyber intrusion analysis. The model establishes that every intrusion event has four core features: **Adversary**, **Capability**, **Infrastructure**, and **Victim**, arranged in a diamond shape with edges representing the relationships between features. From any vertex, analysts can pivot to adjacent vertices to develop additional intelligence—for example, moving from victim to capability to identify tools used, or from infrastructure to adversary to attribute the attacker. The model introduces **activity threads** (ordered sequences of events in a single adversary-victim pair) and **activity groups** (clusters of events sharing common features) to support campaign-level analysis. The Diamond Model was groundbreaking in applying "measurement, testability, and repeatability" to cyber analysis and remains foundational to CTI tradecraft.

### Cyber Kill Chain (Lockheed Martin)

The [Cyber Kill Chain](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html) was developed by Lockheed Martin in 2011 as part of the Intelligence-Driven Defense model. It describes seven sequential phases of a targeted cyberattack: (1) **Reconnaissance** — target selection and vulnerability identification; (2) **Weaponization** — creating a deliverable payload; (3) **Delivery** — transmitting the payload; (4) **Exploitation** — triggering the vulnerability; (5) **Installation** — establishing persistence; (6) **Command and Control** — enabling hands-on-keyboard access; and (7) **Actions on Objective** — exfiltration, destruction, or other effects. The model's key contribution is that **defenders who interrupt any phase prevent mission completion**, shifting the analytic frame from detection-after-compromise to detection-at-any-phase. The Kill Chain is most effective against signature-based, malware-delivered attacks and has been augmented by ATT&CK and the Diamond Model for more complex, living-off-the-land adversary behaviors.

### Pyramid of Pain (David Bianco)

The [Pyramid of Pain](https://www.sans.org/tools/the-pyramid-of-pain), created by David J. Bianco in 2013 and hosted by the SANS Institute, provides a framework for understanding the relative value and adversary cost of different IOC types. The pyramid has seven levels from easiest to hardest for an adversary to change:

| Level | Indicator Type | Attacker Cost to Change |
|-------|---------------|------------------------|
| 1 | Hash values | Trivial (recompile) |
| 2 | IP addresses | Easy (rotate infrastructure) |
| 3 | Domain names | Moderate (register new domains) |
| 4 | Network artifacts | Moderate-High (modify C2 protocols) |
| 5 | Host artifacts | High (modify footprint) |
| 6 | Tools | Very High (develop or acquire new tools) |
| 7 | **TTPs** | **Highest** (retool entire attack methodology) |

The Pyramid's strategic implication: CTI programs that prioritize TTP detection impose the highest costs on adversaries, while hash-based or IP-based detection is easily bypassed through trivial changes. MITRE ATT&CK operationalizes this insight by cataloguing TTPs as the durable signature target for detection engineering.

### Attribution Methodology (Public-Level)

Cyber attribution is the analytic process of associating a cyber intrusion or operation with a specific adversary. At the unclassified, public level, attribution methodology relies on technical indicators (malware code reuse, infrastructure overlap, tool signature), behavioral indicators (TTPs mapped to known actor profiles per ATT&CK), linguistic analysis (code comments, error messages), victimology (who the adversary targets), and strategic context (which state benefits from the operation). Attribution is inherently probabilistic; public government attributions (e.g., DoJ indictments, joint advisories) represent assessed conclusions rather than proof. False flag operations—where an adversary mimics another actor's TTPs—represent a fundamental challenge. JP 3-12 notes that "attribution of threats in cyberspace is crucial for any actions external to the defended cyberspace beyond authorized self-defense."

### Coalition CTI Sharing: Five Eyes and NATO CCDCOE

The [Five Eyes intelligence alliance](https://ccdcoe.org/library/publications/the-five-eyes-and-offensive-cyber-capabilities-building-a-cyber-deterrence-initiative/) (United States, United Kingdom, Australia, Canada, New Zealand) shares SIGINT and CTI extensively, including coordinated public attributions of state cyber operations and Joint Cybersecurity Advisories. The alliance has moved toward collective cyber response through the US-led Cyber Deterrence Initiative (CDI), which coordinates "the joint imposition of consequences against malign actors." The [NATO Cooperative Cyber Defence Centre of Excellence (CCDCOE)](https://ccdcoe.org) in Tallinn, Estonia, is a NATO-accredited research and training hub focused on cyber defense doctrine, the Tallinn Manual (international law applicable to cyber operations), and the annual Locked Shields live-fire exercise—the world's largest international cyber defense exercise.

### Active Defense and Hunt-Forward Operations

Authorities for **hunt-forward operations (HFOs)** are publicly described by USCYBERCOM: teams deploy to partner nations at host invitation, operating side-by-side with partner cyber forces to identify malicious activity in partner networks. [USCYBERCOM describes HFOs](https://www.cybercom.mil/Media/News/Article/3198878/cyber-101-defend-forward-and-persistent-engagement/) as "strictly defensive and at the invitation of the host nation." Intelligence collected during HFOs is shared publicly through government advisories and malware disclosures.

### Persistent Engagement / Defend Forward

As described in [USCYBERCOM's 2018 Vision](https://www.cybercom.mil/portals/56/documents/uscybercom%20vision%20april%202018.pdf), persistent engagement operationalizes defend forward by continuously "intercepting and halting cyber threats, degrading the capabilities and networks of adversaries, and continuously strengthening cybersecurity." The [*Cyber Defense Review* analysis](https://cyberdefensereview.army.mil/Portals/6/CDR-SE_S5-P3-Fischerkeller.pdf) explains that persistent engagement "is expected to allow for greater freedom of maneuver to impose tactical friction and strategic costs on US adversaries pursuing more dangerous activities before they impair US national power."

---

## 8. Strengths and Limitations

### Strengths

**Persistent and scalable.** Unlike HUMINT (which requires sources) or ISR (which requires sensor tasking), network-based CYBINT/DNI operates continuously against adversary infrastructure. Once collection access is established, the sensor can operate persistently without requiring physical proximity or human handling. SIGINT/DNI is particularly well-suited to high-volume, machine-speed environments where adversary activity occurs faster than human analysis can track.

**Integrates with all other INTs.** CYBINT/DNI cross-cues every other collection discipline (see Section 9). Network-derived indicators expose communications targets for COMINT collection, physical infrastructure for GEOINT, and human operators for HUMINT targeting. Conversely, all-source intelligence enriches CYBINT analysis with strategic context, organizational attribution, and capability assessments unavailable from technical collection alone.

**Supports OPE (Operational Preparation of the Environment).** Pre-operational network reconnaissance—understanding adversary network topology, identifying high-value nodes, and positioning for potential access—is an intelligence function that directly enables future military options. This OPE function is a particular strength of the cyber INT enterprise.

**Informs cross-domain operations.** Cyber intelligence supports kinetic targeting (understanding which cyber-physical systems control what physical effects), EW operations (network topology informs spectrum management), and IO/MISO (characterizing influence campaign infrastructure).

### Limitations

**Attribution is hard.** As noted in JP 3-12, attribution "is crucial for any actions external to the defended cyberspace beyond authorized self-defense" but is technically and analytically challenging. Nation-states invest heavily in attribution denial: VPN chains, compromised third-party infrastructure, false flag TTPs, and deliberate code similarities to other actors. Even with significant collection access, attribution confidence is rarely absolute.

**Authorities are tangled.** The [Title 10/Title 50 friction](https://cyberdefensereview.army.mil/Portals/6/Documents/2021_fall/07_Albert_Barth_Thompson_CDR_V6N4-Fall_2021.pdf) described in Section 3 creates interagency coordination requirements that slow operational response. The boundary between intelligence preparation (Title 50) and operational preparation (Title 10) is difficult to draw in cyberspace because they often require the same access and tradecraft. Deconfliction between military cyber operations and ongoing intelligence collection (intelligence gain/loss) is a persistent planning challenge.

**Fast TTP evolution.** Adversaries adapt TTPs in response to defensive detection. The shelf life of a specific technique before adversaries modify it is shrinking; defenders using static signatures are permanently behind. This is the core argument for ATT&CK-based behavioral detection over IOC-based detection.

**Encryption, anonymization, and deception.** Ubiquitous end-to-end encryption (TLS, Signal, WhatsApp) reduces the yield of network-layer collection that relies on plaintext content. VPNs, TOR, and bulletproof hosting complicate infrastructure attribution. Adversaries deliberately plant false flags, use public-domain tools (living-off-the-land with legitimate system utilities), and conduct false flag operations to confuse attribution.

**Fleeting signatures.** IOCs (IPs, domains, hashes) have extremely short useful lives. Adversaries rotate infrastructure within hours or days of exposure. This requires near-real-time intelligence sharing and automated indicator dissemination (STIX/TAXII, AIS) to maintain defensive utility.

### Title 10/Title 50 Friction

The 2019 NDAA addressed some friction by clarifying that clandestine military activity in cyberspace is a "traditional military activity" not requiring the same advance congressional notification as Title 50 covert action. However, as [Lawfare analysis](https://www.lawfaremedia.org/article/title-10-and-title-50-issues-when-computer-network-operations-impact-third-countries) notes, USCYBERCOM operating under Title 10 against infrastructure in third countries faces "the full thicket of international law concerns" without the implicit statutory shield that Title 50 covert action authority carries. This creates persistent legal tension for forward cyber operations.

### US Persons / Domestic Boundary

The Fourth Amendment, the Foreign Intelligence Surveillance Act (FISA), EO 12333, and US person minimization procedures all constrain collection that involves US persons or infrastructure located in the United States. CYBINT collection that transits domestic US internet infrastructure requires careful legal handling, particularly for NSA/DNI authorities. CISA, not NSA or USCYBERCOM, holds the lead for cybersecurity operations on civilian federal government networks, and no military cyber organization has authority to conduct offensive or active-defense operations on domestic civilian infrastructure without specific legal authorization.

### Coalition Release

Sharing cyber intelligence with allies and partners involves complex classification and source-method protection considerations. DNI/SIGINT products often cannot be released in original form due to third-party collection agreements, sensitive source protection, and classification levels. Downgraded or "tear-line" products, unclassified Joint Cybersecurity Advisories, and the Five Eyes framework mitigate but do not eliminate this constraint. NATO nations outside the Five Eyes may receive CTI products tailored for release within NATO SECRET rather than full-access SIGINT products.

---

## 9. Cross-Cueing Patterns

Cross-cueing—where one intelligence discipline's collection cues or supports another—is particularly dynamic in the cyber domain. CYBINT both drives and is driven by all other INTs.

### CYBINT → SIGINT

Network access and infrastructure mapping from DNI collection can identify adversary communications nodes, transmission frequencies, and operator patterns that enable traditional COMINT collection targeting. Discovery of an adversary's C2 server through DNI provides the network selector (IP, domain, email address) needed to task SIGINT collection against that node. Conversely, adversary network activity patterns revealed through DNI can inform SIGINT collection requirements for specific foreign intelligence entities.

### SIGINT → CYBINT

SIGINT intercepts of adversary communications may reveal cyber operation planning, malware deployment timelines, C2 server assignments, and operator identities. A COMINT intercept of adversary cyber operators discussing target selection directly enriches CTI analysis with intent and targeting intelligence unavailable from technical network collection alone. SIGINT is a primary source for understanding the human element of adversary cyber organizations—the command relationships, resource constraints, and decision-making processes behind technical operations.

### CYBINT → HUMINT

Network intrusion analysis can identify specific adversary cyber operators through behavioral patterns (operational security failures, unique coding styles, use of personal infrastructure), providing targeting data for HUMINT operations. An identified cyber operator's online persona, travel patterns, and organizational affiliation—derived from DNI collection—can support recruitment, surveillance, or liaison operations. This CYBINT-to-HUMINT path is a primary method for converting technical attribution into actionable counterintelligence leads.

### HUMINT → CYBINT

Insider sources or recruited agents with access to adversary cyber programs provide intelligence unavailable from technical collection: organizational charts of foreign cyber units, names of operatives, program funding levels, capability development timelines, and specific operational planning. HUMINT is the primary source for understanding adversary intent—the strategic decision to conduct a specific cyber operation—rather than the technical capability or infrastructure. Foreign counterintelligence programs targeting adversary cyber units exemplify this cross-cueing direction.

### CYBINT → TECHINT

Malware discovered during incident response or extracted from compromised systems constitutes "captured material" in the TECHINT (Technical Intelligence) sense—hardware and software whose analysis reveals adversary design choices, code provenance, capability levels, and supply chain origins. Malware reverse engineering is a TECHINT function applied to cyber artifacts. NSA's public Malware Analysis Reports (MARs), such as those published on CISA's ICS-CERT portal, represent the unclassified output of this analytical process.

### CYBINT → OSINT

Classified network indicators—infrastructure IPs, domains, and malware hashes—can be correlated with open-source data to enrich attribution (WHOIS registration patterns, passive DNS, social media personas linked to infrastructure). Conversely, open-source security research often predates classified collection on the same target; OSINT threat feeds and public advisories are integral to CYBINT analysis pipelines. USCYBERCOM's practice of releasing malware samples publicly operationalizes this connection by enabling the commercial security community to develop signatures for the same threats the government is tracking.

### CYBINT → IO/MISO

Cyber intelligence characterizes the technical infrastructure of adversary influence operations: the social media bot networks, disinformation amplification servers, hack-and-leak operation exfiltration nodes, and VPN infrastructure used by state-linked IO actors. This CYBINT output informs Information Operations (JP 3-13) and Military Information Support Operations (MISO) planning by revealing adversary IO intent, reach, and methods. Attribution of an adversary influence campaign's technical infrastructure—its origin IP ranges, hosting providers, and account network topology—is a CYBINT function that directly supports IO countermeasure and public attribution decisions.

---

## Publication Reference Table

| Publication | Type | URL / Source | Relevance |
|-------------|------|-------------|-----------|
| JP 2-0, *Joint Intelligence* | Joint Pub | [jcs.mil](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/) | Keystone intelligence doctrine |
| JP 2-01, *Joint and National Intelligence Support* | Joint Pub | [usna.edu (PDF)](https://www.usna.edu/Training/_files/jp2_01_20170705v2.pdf) | Intelligence organizations, cyber support |
| JP 3-12, *Cyberspace Operations* (2018/2022) | Joint Pub | [iihl.org (2018 PDF)](https://www.onlinelibrary.iihl.org/wp-content/uploads/2021/05/2018-JP-3-12-Cyberspace-Operations.pdf) | CO definition, authority framework |
| AFDP 3-12, *Cyberspace Operations* | AF Doctrine Pub | [doctrine.af.mil](https://www.doctrine.af.mil/Doctrine-Publications/AFDP-3-12-Cyberspace-Ops/) | AF-specific cyber doctrine (updated May 2026) |
| FM 3-12, *Cyberspace and Electromagnetic Warfare Operations* | Army Field Manual | [digitalcommons.unl.edu](https://digitalcommons.unl.edu/usainscom.army.mil/15/) | Army cyber/EW doctrine (2021) |
| ICD 113, *Functional Managers* | IC Directive | [intel.gov (PDF)](https://www.intel.gov/assets/documents/intelligence-community-directives/ICD_113.pdf) | Functional Manager framework |
| USCYBERCOM Vision 2018 | USCYBERCOM Pub | [cybercom.mil (PDF)](https://www.cybercom.mil/portals/56/documents/uscybercom%20vision%20april%202018.pdf) | Persistent engagement doctrine |
| USCYBERCOM CMF 101 | USCYBERCOM Pub | [cybercom.mil](https://www.cybercom.mil/Media/News/Article/3206393/cyber-101-cyber-mission-force/) | CMF structure and missions |
| USCYBERCOM Defend Forward 101 | USCYBERCOM Pub | [cybercom.mil](https://www.cybercom.mil/Media/News/Article/3198878/cyber-101-defend-forward-and-persistent-engagement/) | Defend forward/persistent engagement |
| MITRE ATT&CK | Public Framework | [attack.mitre.org](https://attack.mitre.org) | Adversary TTP taxonomy |
| Diamond Model | DoD Technical Report | [activeresponse.org (PDF)](https://www.activeresponse.org/wp-content/uploads/2013/07/diamond.pdf) | Intrusion analysis methodology |
| Cyber Kill Chain | Lockheed Martin | [lockheedmartin.com](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html) | Attack phase model |
| Pyramid of Pain | SANS / David Bianco | [sans.org](https://www.sans.org/tools/the-pyramid-of-pain) | IOC prioritization model |
| ODNI Annual Threat Assessment 2026 | ODNI | [industrialcyber.co (summary)](https://industrialcyber.co/reports/odni-report-us-critical-infrastructure-faces-escalating-cyber-risks-from-china-russia-iran-and-north-korea/) | Foreign cyber threat actors |
| NSA SIGINT Mission | NSA Public | [nsa.gov](https://www.nsa.gov/signals-intelligence/) | NSA SIGINT/DNI authority |
| DCSA/NCSC SCRM | ODNI/DCSA | [dni.gov](https://www.dni.gov/index.php/safeguarding-science/supply-chain-risk-management) | Supply chain cyber intelligence |
| Five Eyes and Offensive Cyber | NATO CCDCOE | [ccdcoe.org (PDF)](https://ccdcoe.org/uploads/2020/10/2020-Josh-Gold-Five-Eyes-and-Offensive-Cyber-Capabilities.pdf) | Coalition CTI sharing |
| Title 10/50 Cyber Analysis | Cyber Defense Review | [cyberdefensereview.army.mil (PDF)](https://cyberdefensereview.army.mil/Portals/6/Documents/2021_fall/07_Albert_Barth_Thompson_CDR_V6N4-Fall_2021.pdf) | Legal authority framework |
| Strategic Cyberspace Operations Primer | Army War College | [csl.armywarcollege.edu (PDF)](https://csl.armywarcollege.edu/pubs/Publications/Strategic_Cyberspace_Operations_Primer-2023_Dec_18.pdf) | Operational planning context |

---

*This page contains only UNCLASSIFIED information derived from publicly available US government publications, official .mil/.gov websites, and open-source academic and industry literature. No classified or protected sources were used. Last compiled: June 2026.*


---

## See Also

- [JP 2-0 — Joint Intelligence](../02-joint-doctrine/jp-2-0-joint-intelligence.md) — Appendix B owns the doctrinal definitions for all INT disciplines
- [Sensor-to-Indicator Matching](../04-collection-process/05-sensor-to-indicator-matching.md) — how this INT pairs with others in collection planning
- [PED Architecture](../07-tools-and-systems/ped-architecture.md) — where this INT's data is exploited
- [Discipline Index](README.md)
- [CONTRIBUTING.md](../CONTRIBUTING.md)

*Page version 1.0 — Raven Conspiracy Collection Management Wiki*
