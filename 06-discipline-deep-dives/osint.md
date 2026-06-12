# OSINT — Open-Source Intelligence

_Disciplines › OSINT_

---

> **Classification:** UNCLASSIFIED. All content grounded in publicly available US doctrine and IC publications. See [CONTRIBUTING.md](../CONTRIBUTING.md) for sourcing rules.

## 1. Doctrinal Definition

### Statutory and Joint Definitions

Open-Source Intelligence (OSINT) has a statutory definition rooted in the **National Defense Authorization Act for Fiscal Year 2006 (Public Law 109-163)**: "Intelligence that is produced from publicly available information and is collected, exploited, and disseminated in a timely manner to an appropriate audience for the purpose of addressing a specific intelligence requirement." This federal-law definition is the bedrock from which all DoD and Army doctrine derives. ([ICD 301, National Open Source Enterprise, 11 July 2006](https://info.publicintelligence.net/ICD301.pdf))

**JP 2-0, Joint Intelligence** (Appendix B, "Intelligence Disciplines") defines OSINT as: *"Relevant information derived from the systematic collection, processing, and analysis of publicly available information in response to known or anticipated intelligence requirements."* JP 2-0's Appendix B places OSINT within the canonical taxonomy of intelligence disciplines (GEOINT, HUMINT, SIGINT, MASINT, OSINT, TECHINT, CI) and specifies that OSINT "supports warnings, tips, and cues other intelligence disciplines, and provides the context for understanding classified information." The publication notes that OSINT "is susceptible to adversary deception attempts" and "requires tradecraft in the areas of research expertise and OPSEC for Internet-based activities." ([JP 2-0, Joint Intelligence, pp. B-7–B-8, via USNA](https://www.usna.edu/Training/_files/documents/References/2C%20MQS%20References/2015-2016%20MQS/Joint%20Publication%20JP%202-0%20Joint%20Intelligence.pdf))

**ATP 2-22.9, Open Source Intelligence** (Army) adds: *"OSINT is the intelligence discipline that pertains to intelligence produced from publicly available information that is collected, exploited, and disseminated in a timely manner to an appropriate audience for the purpose of addressing a specific intelligence and information requirement (FM 2-0)."* The publication further states that OSINT "is also intelligence developed from the overt collection and analysis of publicly available and open-source information not under the direct control of the U.S. Government." ([ATP 2-22.9, Open Source Intelligence, 2012, via BITS](https://www.bits.de/NRANEU/others/amd-us-archive/atp2-22-9(12).pdf))

The **IC OSINT Strategy 2024–2026** provides the current IC-level definition: *"OSINT is intelligence derived exclusively from publicly or commercially available information that addresses specific intelligence priorities, requirements, or gaps."* This formulation adds *commercially available information* (CAI), reflecting the rise of data-broker markets and the proliferation of commercial datasets (geolocation, satellite imagery, ship-tracking, RF data) since earlier statutory definitions. ([IC OSINT Strategy 2024–2026, p. 1, ODNI/CIA, 8 March 2024](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf))

### The PAI/OSINT Distinction

**Publicly Available Information (PAI)** is the raw material from which OSINT is made; OSINT is PAI that has been analyzed and produced in response to an intelligence requirement. DoD Manual 5240.01 defines PAI as: *"Information that has been published or broadcast for public consumption, is available on request to the public, is accessible on-line or otherwise to the public, is available to the public by subscription or purchase, could be seen or heard by any casual observer, is made available at a meeting open to the public, or is obtained by visiting any place or attending any event that is open to the public."*

The doctrinal implication is critical: PAI collection by itself is not OSINT. Any military intelligence MOS can access PAI; only intelligence personnel with proper authority, training, and collection management coordination are conducting OSINT when that PAI is collected, exploited, and produced in response to an intelligence requirement. This distinction drives Army policy because OSINT activities require special mission authorities, approved tools, managed attribution, and compliance with AR 381-10 and EO 12333, whereas incidental PAI access does not. The 2022 MIPB article "The OSINT Conundrum" describes the resulting bureaucratic tension: the permissiveness of avoiding "OSINT" labels creates an incentive for intelligence professionals to forgo formal OSINT activities in favor of informal "PAI exploitation," degrading accountability and tradecraft standards. ([MIPB, "The OSINT Conundrum," 2022, Army.mil](https://mipb.ikn.army.mil/media/dlvl0yrl/2022-04-se1-gack_osint-conundrum_online.pdf))

JP 2-0 further distinguishes **open source information** (the raw feed) from OSINT (the analyzed product): *"Open source information: Information that any member of the public could lawfully obtain by request or observation as well as other unclassified information that has limited public distribution or access."* The glossary entry for OSINT in JP 2-0 then requires the additional element of systematic analysis in response to intelligence requirements — completing the PAI→OSINT production chain. ([JP 2-0, GL-10](https://www.usna.edu/Training/_files/documents/References/2C%20MQS%20References/2015-2016%20MQS/Joint%20Publication%20JP%202-0%20Joint%20Intelligence.pdf))

**First Army doctrinal mention:** OSINT was first recognized as a separate intelligence discipline in Change 1 to FM 2-0, Intelligence, dated 11 September 2008. ([MIPB, OSINT Support to Targeting, 2023, Army.mil](https://mipb.ikn.army.mil/media/mkxlezii/2024-01-06-s_idx23_online.pdf))

---

## 2. Functional Manager (ICD 113)

### ICD 113: The Functional Manager Framework

**Intelligence Community Directive 113 (ICD 113), Functional Managers** (effective 19 May 2009) implements EO 12333, Section 1.3(b)(12)(A), which authorizes the DNI to designate Functional Managers for intelligence disciplines. ICD 113 defines a Functional Manager as the *"principal advisor to the DNI on the performance of their respective function"* and specifies that they serve as *"cognizant authorities with respect to the overall performance of their functions within and across IC elements and activities."* Functional Managers are distinct from IC element heads: element heads are responsible for mission execution and resource management, while Functional Managers are responsible for setting IC-wide standards, tradecraft, training, interoperability, and strategic direction for their discipline. ([ICD 113, Functional Managers, 19 May 2009, intel.gov](https://www.intel.gov/assets/documents/intelligence-community-directives/ICD_113.pdf))

ICD 113 authorizes Functional Managers to *"prescribe training, tradecraft, reporting, and function-specific technical architecture standards"* and to *"advise IC research and development (R&D) activities with regard to the function's most difficult problems."* The DNI issues annual strategic guidance to Functional Managers by 1 November, and Functional Managers report annually to the DNI on the state of the function by 1 July.

### OSINT Functional Manager: D/CIA and the Open Source Enterprise

Under EO 12333, the DNI designated the **Director of Central Intelligence Agency (D/CIA)** as the OSINT Functional Manager (OSFM) for the IC. The IC OSINT Strategy 2024–2026 confirms: *"The Director of the Central Intelligence Agency (D/CIA) serves as the OSINT Functional Manager (OSFM) for the IC and delegates day-to-day functional management responsibilities to the Director of the Open Source Enterprise (D/OSE) to oversee and guide open source activities across the IC."* ([IC OSINT Strategy 2024–2026, p. 6, ODNI/CIA](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf))

The **Open Source Enterprise (OSE)** is the successor to the former **Open Source Center (OSC)**, which was itself the successor to the **Foreign Broadcast Information Service (FBIS)**. ICD 301 (2006) established the **DNI Open Source Center** at CIA, with the D/CIA as Executive Agent. ICD 301 was rescinded in 2012 and superseded by revised policy; the OSC was subsequently renamed the Open Source Enterprise. ([ICD 301, National Open Source Enterprise, 11 July 2006, publicintelligence.net](https://info.publicintelligence.net/ICD301.pdf))

The IC OSINT Strategy 2024–2026 describes the governance structure: *"CIA, as the Open Source Functional Manager, works in close collaboration with the Defense Intelligence Enterprise Manager for OSINT at the Defense Intelligence Agency (DIA) and the IC OSINT Executive at the Office of the Director of National Intelligence to develop IC policy and coordinate resource requests."* The ODNI IC OSINT Executive ensures *"alignment between the IC's and Department of Defense's open source activities."* ([IC OSINT Strategy 2024–2026, p. 6](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf))

### IC OSINT Strategy 2024–2026

On 8 March 2024, ODNI and CIA jointly released the **IC OSINT Strategy 2024–2026**, titled *"The INT of First Resort: Unlocking the Value of OSINT."* DNI Avril Haines stated: *"By harnessing the potential of Open Source Intelligence (OSINT), the Intelligence Community will continue to provide comprehensive support to national security policymakers and will create additional opportunities to be transparent with our partners and the public about the threats we face."* ([ODNI Press Release No. 06-24, 8 March 2024, dni.gov](https://www.dni.gov/index.php/newsroom/press-releases/press-releases-2024/3784-odni-and-cia-release-the-intelligence-community-osint-strategy-for-2024-2026))

The strategy's four **Strategic Focus Areas** are:
1. **Coordinate Open Source Data Acquisition and Expand Sharing** — coordinate acquisition of PAI and CAI to avoid redundancy; establish a centralized multi-domain data catalog; deliver IC OSINT products to the broader US Government.
2. **Establish Integrated Open Source Collection Management** — develop community-wide collection orchestration; ensure deconfliction *"so the IC is not expending its most sensitive collection capabilities to obtain intelligence that can be derived from open source information."*
3. **Drive OSINT Innovation To Deliver New Capabilities** — accelerate AI, machine learning, and human language technologies; partner with industry and academia to develop, test, and deploy OSINT tools on unclassified systems.
4. **Develop the Next-Generation OSINT Workforce and Tradecraft** — establish common IC training pathways from foundational to expert level; address generative AI opportunities and risks; develop tradecraft standards for *"human-machine teaming that will be the foundation of OSINT in the future."*

The **DIA OSINT Strategy 2024–2028** complements the IC strategy at the DoD level, articulating the vision of making OSINT *"the 'first resort' source of intelligence for decisionmakers and warfighters"* and establishing four guiding principles: *"Data Centricity, Diversified Collection, Dispersed Operations, Distributed Enterprise."* ([DIA OSINT Strategy 2024–2028, dia.mil](https://www.dia.mil/Portals/110/Documents/OSINT-Strategy.pdf))

---

## 3. Collection Authorities and Legal Anchors

### Primary Statutory and Executive Authority

The legal architecture for DoD and Army OSINT rests on several interlocking authorities:

- **EO 12333, United States Intelligence Activities** (as amended) — the foundational executive order governing all US intelligence activities, including OSINT. It specifies the intelligence functions assigned to the Army and requires that collection activities *"protect the constitutional rights of US persons."* EO 12333 also designated functional managers for HUMINT, GEOINT, and SIGINT; the DNI later used authority granted by EO 12333 to designate D/CIA as OSINT Functional Manager. ([EO 12333, 4 December 1981, as amended](https://www.esd.whs.mil/Portals/54/Documents/DD/issuances/dodi/311512p.pdf))
- **Intelligence Reform and Terrorism Prevention Act of 2004 (IRTPA), Public Law 108-458** — established the DNI position and directed the IC to make full use of open source information. IRTPA also mandated the creation of the National Open Source Center.
- **National Defense Authorization Act for Fiscal Year 2006 (Public Law 109-163)** — provided the statutory definition of OSINT and directed the Defense Intelligence Enterprise to establish OSINT specialty plans in the Military Services.

### DoD Manual 3115.12 (Open Source Intelligence)

**DoD Instruction 3115.12**, *Open Source Intelligence (OSINT)* (effective 24 August 2010; Change 2 effective 16 July 2020) is the primary DoD-level policy document. It *"establishes policy, assigns responsibilities, and prescribes procedures for OSINT operations within the Department of Defense."* Key provisions include: ([DoDI 3115.12, OSD/WHS, esd.whs.mil](https://www.esd.whs.mil/Portals/54/Documents/DD/issuances/dodi/311512p.pdf))

- The **Under Secretary of Defense for Intelligence and Security (USD(I&S))** oversees DoD OSINT policy and promotes alignment of IC and DoD OSINT strategies.
- The **Director, DIA** serves as the *"DoD Lead Component for OSINT"* and issues DoD OSINT operational and technical guidance, sets DoD intelligence standards for OSINT collection/acquisition/processing/exploitation/dissemination, and chairs the **Defense Open Source Council (DOSC)** (originally titled the DoD Open Source Council, DOSC).
- The **DOSC** *"shall be the primary governance mechanism for DoD OSINT"* and *"shall advise and report to the USD(I&S) on OSINT issues."* The DOSC chair is a senior executive designated by the Director, DIA; standing members include representation from USD(I&S), DIRNSA/CHCSS, Director NGA, USD(AT&L), DoD CIO, Secretaries of the Military Departments, and Combatant Command representatives, with the ODNI as ex-officio participant.
- OSINT collection, acquisition, exploitation, analysis, and dissemination *"shall conform to the tradecraft and information security policies, directives, and guidelines set forth by the DNI, USD(I&S), and Director, DIA."*
- **DIA DIEM-OSINT designation:** In December 2021, the USD(I&S) further designated the Director, DIA as the **Defense Intelligence Enterprise Manager (DIEM) for OSINT**; this was codified in DoD Directive 5105.21 on 25 January 2023. DIA operates the **Open Source Intelligence Integration Center (OSIC)** to execute DOSC and DIEM responsibilities. ([DIA OSINT Strategy 2024–2028, dia.mil](https://www.dia.mil/Portals/110/Documents/OSINT-Strategy.pdf))

### DoD Directive 3115.18: PAI Access and Use

**DoDD 3115.18**, *DoD Access to and Use of Publicly Available Information (PAI)* (11 June 2019, as amended), establishes policy for non-intelligence DoD component access to PAI, distinct from OSINT production requiring intelligence authority. The DIA OSINT Strategy references this as a governing document alongside DoDI 3115.12.

### Army-Specific Authorities: ATP 2-22.9 and AR 381-10

**ATP 2-22.9** specifies that *"all OSINT operations conducted by intelligence personnel must comply with the legal restrictions as outlined in Executive Order 12333, DoD 5240.1-R, DoDD 3115.12, JP 2-0, and AR 381-10."* ([ATP 2-22.9, 2012, bits.de](https://www.bits.de/NRANEU/others/amd-us-archive/atp2-22-9(12).pdf))

**AR 381-10** enables Army intelligence components to perform intelligence functions while protecting the constitutional rights of US persons. It defines a **US person** as: a US citizen; a US permanent resident alien; an unincorporated association substantially composed of US citizens or permanent resident aliens; or a corporation or subsidiary incorporated in the United States not directed or controlled by a foreign government. Army intelligence activities may collect PAI on US persons *"only when it is necessary to fulfill an assigned function,"* using the **least intrusive means** feasible. Collection must be coordinated with FBI when involving US persons within the United States.

### ICD 301 and the Open Source Enterprise

**ICD 301, National Open Source Enterprise** (11 July 2006, later rescinded in 2012 and superseded by revised IC policy) established the policy framework for the National Open Source Committee (NOSC) and the DNI Open Source Center. It mandated that IC open source efforts *"support a wide range of intelligence activities, including all-source analysis, and human, signals, geospatial, and measurement and signature intelligence"* and required all exploiters to *"exercise appropriate tradecraft and information security practices."* ICD 301 also established the principle that open source is the *"source of first resort"* — a concept echoed and formalized in the IC OSINT Strategy 2024–2026. ([ICD 301, 11 July 2006, publicintelligence.net](https://info.publicintelligence.net/ICD301.pdf))

### Commercial Data and the Data-Broker Debate

The explosive growth of commercially available information (CAI) — location data, biometric data, financial data, and related personal data sold by commercial data brokers — has created significant legal and policy debate within the OSINT community. **Executive Order 14117**, *Preventing Access to Americans' Bulk Sensitive Personal Data and United States Government-Related Data by Countries of Concern* (28 February 2024), addressed one dimension of this debate: restricting foreign adversary (China, Russia, Iran, North Korea, Cuba, Venezuela) access to bulk US sensitive personal data through commercial data-broker channels. The DoJ finalized implementing regulations under 28 C.F.R. Part 202, effective 8 April 2025. ([DoJ, Data Security Program Implementation, April 2025, justice.gov](https://www.justice.gov/opa/pr/justice-department-implements-critical-national-security-program-protect-americans-sensitive))

From the US intelligence side, the IC OSINT Strategy 2024–2026 explicitly addresses CAI acquisition: *"The IC will implement the CAI Framework and track PAI and CAI in a centralized, multi-domain data catalog to enhance transparency."* The DIA OSINT Strategy 2024–2028 notes that *"novel sources of information stemming from the commercial data marketplace will present new opportunities for the OSINT community to diversify collection"* while warning that *"diverse procedures for acquiring commercial data and tools increase the risks of poor data quality, malicious code, and low return on investment."*

### OPSEC During Collection

AR 380-5 directs that Army personnel *"will not apply classification or other security markings to an article or portion of an article that has appeared in a newspaper, magazine, or other public medium,"* although the resulting OSINT analysis may be deemed Controlled Unclassified Information. The open paradox of OSINT is that the same public sources that reveal adversary activity also reveal friendly activity: *"Information generally available to the public can reveal the existence of, and sometimes details about classified or sensitive information that can be used to neutralize or exploit military operations."* OSINT cells must therefore apply managed attribution and digital OPSEC (anonymized browsing, VPN use, avoiding high-value targets on unsecured connections).

---

## 4. Primary Collection Methods / Sub-Disciplines

OSINT collection is normally accomplished through monitoring, data-mining, and research across multiple source types. ATP 2-22.9 identifies four primary collection modes: public speaking forums, public documents, public broadcasts, and Internet websites. The following taxonomy maps more granular sub-disciplines. ([ATP 2-22.9, 2012, bits.de](https://www.bits.de/NRANEU/others/amd-us-archive/atp2-22-9(12).pdf))

### Print and Broadcast Media Monitoring

The oldest OSINT sub-discipline, traceable to FBIS (founded 1941). Involves monitoring foreign print press, radio, and television for political statements, military doctrine publications, order of battle indicators, and economic reporting. The OSC/OSE maintained the Foreign Broadcast Information Service successor capability, providing translated and transcribed foreign media in near-real time. Key indicators include: official statements on military deployments, doctrinal publications, budget announcements, and propaganda analysis. Gray literature — defined in JP 2-0 as *"a subset of open source information usually produced by research establishments that is neither published commercially nor universally accessible"* — includes academic reports, institutional data, informal draft papers, and unofficial government exchanges. ([JP 2-0, Appendix B, p. B-7](https://www.usna.edu/Training/_files/documents/References/2C%20MQS%20References/2015-2016%20MQS/Joint%20Publication%20JP%202-0%20Joint%20Intelligence.pdf))

### Internet and Social Media Intelligence (SOCMINT)

Social Media Intelligence (SOCMINT) is the exploitation of social media platforms for intelligence collection. Applications include: adversary network mapping, propaganda and disinformation detection, tracking personnel locations and unit affiliations through soldier-posted content, monitoring civil unrest indicators, assessing population sentiment, and target development. Key tradecraft concerns include attribution (sock-puppet accounts, state-controlled personas), bot detection using transmission volume and online patterns, and exploitation of metadata embedded in digital files (images, videos, documents). The MIPB "OSINT Conundrum" notes unique OSINT data categories including *"collection of bulk volume and content data across public platforms"* and *"collection of social network information, based on user content and online interaction."* ([MIPB, "The OSINT Conundrum," 2022, Army.mil](https://mipb.ikn.army.mil/media/dlvl0yrl/2022-04-se1-gack_osint-conundrum_online.pdf))

The Strava global heatmap incident (January 2018), in which commercial fitness app data revealed the locations and running routes at military installations worldwide, is a canonical example of SOCMINT/commercial data's dual-use intelligence value and OPSEC risk. ([USNI Proceedings, "OSINT: A Double-Edged Sword," August 2018](https://www.usni.org/magazines/proceedings/2018/august/open-source-intelligence-double-edged-sword))

### Commercial Imagery (OSINT overlap with GEOINT)

Commercial satellite imagery from providers such as Maxar, Planet Labs, Airbus Defence and Space, and others constitutes a major OSINT source that overlaps with GEOINT. The MIPB "OSINT Conundrum" notes that the commercial imagery market has exploded worldwide with *"more than 300 imaging platforms fielded in the past decade,"* and that *"commercial platforms now deliver better image quality than spy satellites did just two decades ago."* Ground-based imagery from social media, bloggers, and activists supplements commercial satellite data. NGA manages commercial imagery contracts under the Commercial GEOINT Activity. Unlike NTM (national technical means) imagery, commercial imagery can be freely shared with partners, posted in analytical reports, and incorporated into unclassified products.

### Commercial AIS / ADS-B / Maritime and Aviation Tracking

**Automatic Identification System (AIS)** and **Automatic Dependent Surveillance–Broadcast (ADS-B)** are mandatory safety systems for ships and aircraft respectively, transmitting unencrypted position and identity data that is publicly re-broadcast by commercial aggregators (FlightRadar24, MarineTraffic, ADS-B Exchange, FlightAware). These data streams constitute one of the most operationally significant modern OSINT sub-disciplines. Force movement indicators including naval vessel transits, unusual port calls, military aircraft flight patterns, and airlift surges can be monitored at no cost using public aggregators. The USNI Proceedings (2018) notes that *"the proliferation of ADS-B receivers parallels the 'democratization of signals intelligence'"* and that *"AIS and most V2V systems transmit unencrypted data that can be read by anyone with a receiver nearby."* AIS spoofing and transponder deactivation during sensitive operations create OSINT collection gaps that are themselves indicators of intent. ([USNI Proceedings, "OSINT: A Double-Edged Sword," 2018](https://www.usni.org/magazines/proceedings/2018/august/open-source-intelligence-double-edged-sword); [CCDCOE, "Utilizing Air Traffic Communications for OSINT," 2018](https://ccdcoe.org/uploads/2018/10/Art-16-Utilizing-Air-Traffic-Communications-for-OSINT-on-State-and-Government-Aircraft.pdf))

### Academic and Grey Literature

Academic journals, conference proceedings, think-tank reports, and doctoral dissertations constitute grey literature intelligence. Priority collection targets include: foreign military doctrine journals, defense university publications, national security strategy documents, and academic research on military technology. Foreign military journals (e.g., Chinese PLA publications, Russian Military Thought) offer insight into adversary doctrine and strategic intent that may not be discernible from operational-level reporting alone.

### Government and Parliamentary Records

Legislative testimony, parliamentary debates, budget documents, government procurement records, official press releases, and regulatory filings constitute a rich OSINT source. Defense budget documents often reveal capability acquisition priorities; parliamentary questions may expose classified programs; official military journals publish doctrine and personnel movements. Court records in open proceedings may contain intelligence-relevant technical information.

### Geospatial Open Data

Open-source geospatial data includes **OpenStreetMap (OSM)**, public NASA/USGS satellite imagery, public LiDAR datasets from national mapping agencies, and government-produced geographic data. OSM volunteer mapping has proven accurate enough to reveal military installations and infrastructure in denied areas. Public lidar from USGS 3DEP (3D Elevation Program) provides elevation data useful for terrain analysis.

### Public Commercial RF / SIGINT-Like Data

Commercial Radio Frequency (RF) monitoring companies such as **Hawkeye 360** (now HawkEye 360) and **Kleos Space** use low-Earth orbit satellites to detect and geolocate RF emissions (AIS, VHF, radar) from ships and other emitters, publishing results as commercial open-source products. These capabilities represent an OSINT-adjacent domain: the emissions themselves may be classified SIGINT topics if targeted by NSA, but the *commercial availability* of patterns derived from those emissions creates a publicly discussable intelligence layer. The MIPB "OSINT Conundrum" (2022) notes that *"ship and aircraft transponder signatures, reported over publicly available AIS and ADS-B systems, fit well into the NSA's definition of electronic intelligence"* — illustrating the discipline overlap challenge.

### Court Records, Business Filings, Sanctions Lists

Open court records (PACER in the US, equivalents abroad), corporate filings (SEC EDGAR, Companies House, national registries), OFAC/UN/EU sanctions lists, and beneficial ownership registries provide intelligence on entity networks, front companies, financial flows, and individual affiliations. These databases are increasingly automated through commercial intelligence platforms and are central to financial intelligence (FININT) under OSINT. The MIPB "OSINT Conundrum" identifies *"exploitation of transaction data, including blockchain and foreign currency transfers"* as a unique OSINT collection category.

### Internet Infrastructure Data (WHOIS, DNS, BGP)

At the unclassified tradecraft level, network infrastructure analysis includes: WHOIS domain registration records, passive DNS databases, BGP routing tables (route-views.org, RIPE NCC), SSL/TLS certificate transparency logs, and Autonomous System (AS) mapping. These sources enable attribution of websites and online infrastructure to organizations, identification of hosting patterns, and detection of adversary cyber infrastructure — particularly relevant to identifying disinformation platforms, criminal infrastructure, and state-sponsored cyber operations at the pre-attribution level.

### Imagery-Derived OSINT (Bellingcat Methodology)

Open-source investigation organizations, most notably **Bellingcat**, have operationalized a systematic methodology for imagery-derived OSINT that has become a recognized tradecraft standard. The core techniques include: ([Bellingcat, "Using the Sun and the Shadows for Geolocation," 3 December 2020](https://www.bellingcat.com/resources/2020/12/03/using-the-sun-and-the-shadows-for-geolocation/))

- **Geolocation:** Identifying the exact location where a photo or video was taken by cross-referencing visible landmarks, terrain features, signage, vegetation, and architectural details against satellite imagery (Google Earth, Sentinel Hub) and OpenStreetMap.
- **Chronolocation (shadow analysis):** Using the **SunCalc** tool and Bellingcat's **Shadow Finder Tool** to determine when a photo was taken based on shadow length and direction relative to a known object's height, given a date and time input. This allows independent verification of claimed timestamps. ([Bellingcat, "Geolocate Images with Bellingcat's Shadow Finder Tool," 22 August 2024](https://www.bellingcat.com/resources/2024/08/22/shadow-geolocate-geolocation-locate-image-tool-open-source-bellingcat-measure/))
- **Multi-source corroboration:** Combining satellite imagery, social media posts, AIS/ADS-B data, and other open sources to independently establish facts about events on the ground — used prominently in documenting the downing of MH17 and the Salisbury poisoning.

---

## 5. Signature / Indicator Catalog — What OSINT Sees

OSINT's unique contribution to all-source analysis is its ability to detect strategic, operational, and tactical indicators across the full operational variables (PMESII: Political, Military, Economic, Social, Information, Infrastructure). The following catalog is derived from Army and IC doctrine and unclassified analytical practice. ([MIPB, OSINT Support to Targeting, 2023, Army.mil](https://mipb.ikn.army.mil/media/mkxlezii/2024-01-06-s_idx23_online.pdf))

### Order of Battle from Public Sources

Military parade imagery reveals equipment types, unit insignia, and formation structures. Social media posts by conscripts, military families, and local populations provide unit locations, equipment photographs, morale indicators, and deployment timelines. Vehicle license plates and unit markings visible in publicly posted photos can be cross-referenced against known unit databases. Commercial satellite imagery reveals military base expansion, equipment marshaling, and logistic stockpiling. The identification of new or previously unknown equipment types in parade photography and defense industry exhibitions is a standard OSINT indicator for equipment fielding timelines.

### Political Indicators

Elections (candidates, campaign financing, foreign interference indicators), official government statements, leadership succession patterns (biographic databases, official media appearances), and parliamentary/legislative debates all generate OSINT indicators of strategic intent and political stability. State media messaging shifts often precede policy changes or military actions; monitoring of official press for linguistic or tonal changes is a foundational media analysis tradecraft task.

### Economic Indicators

Sanctions impact can be measured through: shipping data (vessels avoiding sanctioned ports), commodity price changes in public markets, government procurement records (emergency sole-source contracts), and corporate earnings disclosures. Supply chain disruption indicators include: cargo AIS tracking, port arrival/departure data, and logistics sector reporting. Defense industrial output can be inferred from defense company press releases, export license applications (available from BIS/DDTC public datasets), and trade publication reporting.

### Force Movements

Public transport (rail manifests, flight schedules, bus bookings for military personnel) and AIS/ADS-B data are the primary OSINT sensors for force movements. Unusual clustering of military flights (c-17/AN-124 movements visible on FlightRadar24), naval vessel departures from homeports, and anomalous cargo rail traffic are classic pre-crisis indicators. ATP 2-22.9 notes that OSINT personnel should *"confirm or deny threat courses of action based on publicly available indicators."* ([ATP 2-22.9, 2012, bits.de](https://www.bits.de/NRANEU/others/amd-us-archive/atp2-22-9(12).pdf))

### Equipment Fielding

Defense industry press (Jane's, Defense News, The War Zone), manufacturer announcements, official military press releases, and equipment photographs at exercises and parades provide indicators of new system deployments. Commercial satellite imagery of known test ranges, defense facilities, and storage areas supplements open-source reporting. The MIPB OSINT targeting article (2023) specifically identifies *"equipment and supply movements"* as a key OSINT collection target during competition and conflict.

### Strategic Intent: Doctrinal Publications and Military Journals

Foreign military doctrine (service manuals, joint publications, staff college publications), military journal articles authored by senior officers, and national security strategy documents reveal strategic intent, operational concepts, and capability priorities. This is particularly valuable for understanding long-horizon capability development that may not yet manifest in observable activities.

### Adversary Disinformation Campaigns and Counter-OSINT

OSINT is both a tool for detecting disinformation and a target of it. Indicators of adversary information operations include: coordinated inauthentic behavior on social media (bot detection through transmission patterns), fabricated imagery (metadata analysis, reverse image search), sockpuppet networks (account history analysis), and narrative manipulation (topic modeling, sentiment analysis). Adversaries also conduct counter-OSINT operations: seeding publicly available sources with false information, conducting AIS spoofing to obscure vessel locations, and manipulating commercial satellite imagery ordering patterns to cue false collection priorities.

### Open Civil Unrest Indicators

Protest location and scale (social media, local press, live streaming), opposition organization capabilities (fundraising data, social media reach), government crackdown indicators (communications disruptions, detention reports), and strike/labor action data (union communications, labor ministry records) provide indicators of political instability that may precede internal conflict or state repression.

---

## 6. PED Chain

The OSINT **Processing, Exploitation, and Dissemination (PED)** chain translates raw publicly available information into finished intelligence. Unlike classified collection disciplines, OSINT PED must navigate the cross-domain challenge of collecting at the unclassified level and transmitting to classified mission command systems.

### Collection via OSINT Teams, Contractors, and Brigade S-2 OSINT Cells

At the tactical level, ATP 2-22.9 establishes the Brigade Combat Team (BCT) OSINT section structure: a **Section Leader** (primary liaison to the BCT S-2, supervisory oversight), a **Requirements Manager** (quality control, synchronization), a **Situation Development Analyst** (monitors PAI for common operational picture; analyzes population, tribal affiliations, political beliefs, key leaders), and a **Target Development Analyst** (identifies target components and characteristics). The section leader *"ensures that all OSINT products are included in the planning for current and future operations."* ([ATP 2-22.9, 2012, bits.de](https://www.bits.de/NRANEU/others/amd-us-archive/atp2-22-9(12).pdf))

OSINT does not have a specific Military Occupational Specialty (MOS) or additional skill identifier; any military intelligence MOS may conduct OSINT if they receive mission authority, use approved tools with managed attribution, and meet security and training requirements. The 2023 MIPB article on OSINT support to targeting identified the need for a dedicated **OSINT integrator** role responsible for acquiring mission approval authorities, synchronizing collection with higher, adjacent, and subordinate headquarters, and translating PIRs and IRs into OSINT-specific collection requirements. ([MIPB, OSINT Support to Targeting, 2023, Army.mil](https://mipb.ikn.army.mil/media/mkxlezii/2024-01-06-s_idx23_online.pdf))

At the strategic/operational level, OSINT-trained personnel in theater intelligence centers, IC elements, and contracted analytical support perform bulk collection and processing against standing collection requirements registered in the **Open Source Collection Acquisition Requirements Management System (OSCARMS)** — the IC's collection management program of record for OSINT collection requirements. ([JP 2-0, Appendix B, p. B-8](https://www.usna.edu/Training/_files/documents/References/2C%20MQS%20References/2015-2016%20MQS/Joint%20Publication%20JP%202-0%20Joint%20Intelligence.pdf))

### Translation, Gisting, and Language Support

Multilingual exploitation is a foundational OSINT capability. The OSC/OSE maintains linguist teams for high-priority language collection (Arabic, Mandarin, Farsi, Russian, Korean). At the tactical level, military linguists (MOS 09L, contracted civilian interpreters, and indigenous scouts) support translation and gisting of locally acquired PAI. The IC OSINT Strategy 2024–2026 specifically identifies the need for *"substantive, language, and cultural knowledge"* as requirements for OSINT officers, and notes that some foreign partners have *"a high density of native language expertise"* that can supplement US collection. The National Virtual Translation Center (NVTC), referenced in ICD 301, provides surge translation support to the IC.

### Database Entry, Tagging, and Metadata Standards

Collected OSINT is entered into intelligence databases with metadata tags enabling search, retrieval, and fusion with other intelligence. ICD 301 required implementing organizations to *"tag the information in accordance with IC standards and make available all information and tools/capabilities to other community elements."* The IC OSINT Strategy 2024–2026 addresses the ongoing challenge of data interoperability: *"The OSINT community will leverage ongoing efforts to enhance data management across the IC through the development of interoperability and data tagging standards to ensure data reaches mission users in a timely and usable manner."*

### Integration into All-Source Analysis via DCGS

OSINT products are integrated into all-source analysis through the **Distributed Common Ground System – Army (DCGS-A)**, the Army's deployable intelligence systems suite that *"fuses intelligence information and produces enemy situational awareness products"* from battalion to Echelons Above Corps (EAC). DCGS-A integrates data from more than 700 sources via the **DCGS Integration Backbone (DIB)**, enabling all-source analysts to correlate OSINT reporting with SIGINT, GEOINT, HUMINT, and MASINT. ([DCGS-A, DOT&E FY2016 Report, osd.mil](https://www.dote.osd.mil/Portals/97/pub/reports/FY2016/army/2016dcgs-a.pdf))

The 2023 MIPB OSINT targeting experiment found that OSINT requires a **cross-domain solution** to collect information at the unclassified level and transmit it to classified mission command systems — a persistent architecture gap. OSINT cells' outputs should *"feed into the fusion cell where the G-2/S-2 staff can corroborate or confirm the OSINT reports."* The DIA OSINT Strategy 2024–2028 sets an enabling objective to *"develop and deploy an open source, cross-domain, Tasking, Collection, Processing, Exploitation, and Dissemination (TC-PED) system accessible to the Defense Intelligence Enterprise, FVEYs and IC partners."* ([DIA OSINT Strategy 2024–2028, dia.mil](https://www.dia.mil/Portals/110/Documents/OSINT-Strategy.pdf))

### ODNI OSE Products and Reachback

The Open Source Enterprise produces OSINT products across the intelligence cycle, including translated foreign media, thematic analytical reports, biographic assessments, and finished OSINT. Field units and COCOM intelligence staffs can request OSE reachback support through the OSCARMS collection requirement system. The DIA's OSIC serves as the DoD focal point for integration of OSE products into the Defense Intelligence Enterprise.

### Force Protection OSINT Cells

OSINT cells provide force protection support through monitoring of local area threat indicators: protest activity near installations, social media reporting on planned attacks, local press reporting on threat actor movements, and IED threat pattern analysis from open sources. The situation development analyst function in ATP 2-22.9's BCT OSINT section is specifically tasked to *"analyze information and produce current intelligence about the operational environment, enemy, terrain, and civil considerations before and during operations."*

---

## 7. Exploitation Tradecraft (Unclassified, Doctrinal)

### Source Evaluation (Provenance and Credibility)

ATP 2-22.9 establishes a standardized two-part source evaluation system for OSINT that mirrors the intelligence community's broader source rating framework: ([ATP 2-22.9, 2012, bits.de](https://www.bits.de/NRANEU/others/amd-us-archive/atp2-22-9(12).pdf))

**Source Reliability (A–F):**
- A = Reliable (complete reliability history)
- B = Usually reliable (minor doubt)
- C = Fairly reliable (has provided valid information in the past)
- D = Not usually reliable (significant doubt; has occasionally provided valid data)
- E = Unreliable (history of invalid information)
- F = Cannot be judged (first-time source — *all new sources default to F*)

**Information Credibility (1–8):**
- 1 = Confirmed by independent sources, logical, consistent
- 2 = Probably true
- 3 = Possibly true
- 4 = Doubtfully true
- 5 = Improbable
- 6 = Misinformation (unintentionally false)
- 7 = Deception (deliberately false)
- 8 = Cannot be judged (*all information from new sources defaults to 8*)

Source evaluation factors include: **Identity** (who produced the information), **Authority** (source expertise), **Motive** (why published), **Access** (direct vs. indirect), **Timeliness** (date of information), and **Consistency** (internal and external). Primary sources are preferred over secondary sources; authoritative over nonauthoritative. The 2023 MIPB OSINT targeting article adds social-media-specific credibility indicators: account history length, posting accuracy history, timeliness of posting after events, locational context (originating vs. reposting), and verified account status. ([MIPB, OSINT Support to Targeting, 2023, Army.mil](https://mipb.ikn.army.mil/media/mkxlezii/2024-01-06-s_idx23_online.pdf))

ICD 203, Analytic Standards, provides the IC-wide framework for evaluating source credibility in analytic products, and the MIPB targeting article directs that analysts *"assess each OSINT report for source reliability, credibility, and quality of the information in accordance with ICD 203."*

### Multilingual Exploitation

Foreign-language OSINT requires both translation fidelity and cultural literacy. Machine translation accelerates throughput but requires human review for nuance, politically loaded terminology, and culturally specific references that automated systems may render incorrectly. The IC OSINT Strategy 2024–2026 identifies language and cultural knowledge as essential OSINT workforce requirements: *"The OSINT discipline will continue to require officers with the substantive, language, and cultural knowledge necessary to identify, collect, and exploit the best source of information to address priority intelligence requirements."*

### Geolocation from Imagery (Chronolocation, Shadow Analysis)

The Bellingcat methodology for geolocation has become an unclassified tradecraft standard for OSINT imagery exploitation: ([Bellingcat, "Using the Sun and the Shadows for Geolocation," 2020](https://www.bellingcat.com/resources/2020/12/03/using-the-sun-and-the-shadows-for-geolocation/))

1. **Landmark matching:** Identifying visible structures, terrain features, and signage in an image and cross-referencing against commercial satellite imagery (Google Earth, Sentinel Hub) and OpenStreetMap to establish geographic location.
2. **Shadow analysis / chronolocation:** Using known object height, shadow length, date, and time inputs in tools like **SunCalc** or Bellingcat's **Shadow Finder Tool** to determine the ring of possible locations where a shadow of that proportion could occur at that time — intersected with landmark matching to produce a precise location fix. ([Bellingcat, "Chronolocation," 8 May 2023](https://www.bellingcat.com/resources/2023/05/08/chronolocation-determining-when-a-photo-was-taken-using-facebook-google-street-view-and-assorted-tiny-details/))
3. **Metadata exploitation:** EXIF data embedded in digital images (GPS coordinates, camera serial number, timestamps) provides direct geolocation and chronolocation when not stripped by social media platforms.

The MIPB targeting article identifies the following exploitation steps after source isolation: *"location verification through metadata, background, or landmark exploitation; date and time verification by metadata or other source; source network characterization; source activity characterization; and a pivot to related collection activities such as pattern of life characterization."*

### Verification (Multi-Source Corroboration)

Consistent with ICD 203, OSINT products require corroboration: *"Confirmation from another discipline, source, or multiple sources validates OSINT information."* Multiple independent reports from publicly available sources on the same target within a narrow temporal window increase credibility. The MIPB targeting article notes that *"multisource publicly available information about the same event but without supporting imagery or other corroborating reporting (or within a broad temporal window) would likely not meet validation requirements for targeting."* Corroboration can come from other OSINT sources (cross-platform confirmation) or from other intelligence disciplines (all-source fusion).

### OPSEC During OSINT (Signature Management)

ATP 2-22.9 devotes significant attention to OPSEC risks during OSINT collection. Digital footprints on visited websites — including IP addresses, browser fingerprints, search terms, and navigation patterns — are logged and may expose collection interests and intelligence priorities. Key OPSEC practices include: use of government computers on approved networks (INTELINK-U or approved commercial ISPs), avoidance of focused search terms that reveal intelligence targets, use of managed attribution tools (VPNs, anonymizing browsers where authorized), and periodic consultation with S-6/G-6 information assurance personnel for current security patch status. The 2018 Strava heatmap incident exemplifies the inverse OPSEC risk: adversary OSINT capabilities can reconstruct US force locations and patterns from commercial data generated by US personnel. ([ATP 2-22.9, 2012, bits.de](https://www.bits.de/NRANEU/others/amd-us-archive/atp2-22-9(12).pdf))

### Counter-Deception: Deepfakes, Fabricated Imagery, Sockpuppets

The IC OSINT Strategy 2024–2026 identifies the risks of generative AI: *"At the same time, the IC must be attuned to the risks in the open source domain, including the provenance and validity of information it obtains."* Tradecraft responses to adversary deception include: reverse image search to detect fabricated or recycled imagery; metadata analysis to identify image manipulation; account history analysis to detect sockpuppets and coordinated inauthentic behavior; cross-platform corroboration to verify claimed events; and AI-assisted deepfake detection. The **Defense Innovation Unit (DIU)** moved in June 2024 to rapidly acquire commercial deepfake detection and attribution capabilities, noting: *"This technology is increasingly common and credible, posing a significant threat to the Department of Defense, especially as U.S. adversaries use deepfakes for deception, fraud, disinformation, and other malicious activities."* ([DIU Deepfake Detection CSO, DefenseScoop, 26 June 2024](https://defensescoop.com/2024/06/26/why-diu-is-looking-to-speedily-buy-deepfake-detection-technology/)) DARPA's Media Forensics (MediFor) program has developed automated deepfake detection tools since at least 2019.

### AI/ML Augmentation

The IC OSINT Strategy 2024–2026 calls the integration of AI and ML into OSINT the most significant technology opportunity and risk simultaneously. Productive applications include: *"aiding the identification of common themes or patterns in underlying data and quickly summarizing large amounts of text"* (large language model summarization), machine translation, automated entity extraction, cross-platform content monitoring, and geolocation assistance. The strategy states *"the OSINT community should be at the forefront of the IC in testing the use of GAI,"* leveraging the advantage that OSINT *"presents a unique opportunity among collection disciplines to explore new partnership models to speed the adoption of new tools and tradecraft"* because of its unclassified nature. The DIA OSINT Strategy 2024–2028 envisions *"machine-based collection and processing"* that can *"cross-cue other collection platforms, and feed the all source analysis process."* ([DIA OSINT Strategy 2024–2028, dia.mil](https://www.dia.mil/Portals/110/Documents/OSINT-Strategy.pdf))

---

## 8. Strengths and Limitations

### Strengths

**Cost-effectiveness:** OSINT leverages an ecosystem — commercial media, academic publishing, social media, satellite imagery, AIS/ADS-B — that the private sector has already paid to build at global scale. IC and DoD access these sources at marginal cost compared to dedicated collection systems.

**Speed and availability:** PAI is often available in near-real time, particularly social media and live-stream content. OSINT can provide initial indicators hours or days before classified systems can be retasked.

**Low classification / shareability:** OSINT products are by default unclassified or at low classification levels, enabling sharing with coalition partners, law enforcement, foreign liaison services, and policymakers who lack SCI access. The IC OSINT Strategy 2024–2026 identifies this as a strategic differentiator: *"OSINT presents a unique opportunity among collection disciplines to explore new partnership models."*

**Tip-off function:** OSINT routinely provides the initial indicator that cues classified collection systems. The IC OSINT Strategy 2024–2026 explicitly states that OSINT collection should be pursued *"to ensure that the IC is not expending its most sensitive collection capabilities to obtain intelligence that can be derived from open source information."* ([IC OSINT Strategy 2024–2026, p. 4](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf))

**Volume and breadth:** The open-source environment encompasses essentially all human communication and activity that is not deliberately hidden from public view — a vastly larger collection surface than any classified INT.

**Scale advantage for strategic competition:** The DIA OSINT Strategy 2024–2028 notes: *"Since 2018, the total value of data bought and sold on the global economy surpassed that of crude oil"* — and much of that data is accessible for intelligence purposes at OSINT cost.

### Limitations

**Signal-to-noise ratio:** The volume of publicly available information vastly exceeds analytical capacity. Automated processing and AI are necessary but imperfect tools; human analyst judgment remains essential for quality control.

**Deception and disinformation:** Adversaries deliberately plant false information in open sources. JP 2-0 states: *"Incorrect information may be deliberately planted in public sources."* The growing sophistication of deepfakes, fabricated documents, and coordinated inauthentic behavior increases this risk significantly. ([JP 2-0, Appendix B, p. B-7](https://www.usna.edu/Training/_files/documents/References/2C%20MQS%20References/2015-2016%20MQS/Joint%20Publication%20JP%202-0%20Joint%20Intelligence.pdf))

**US persons and privacy constraints:** AR 381-10 and EO 12333 impose significant constraints on collection involving US persons, even through PAI. These constraints are legally necessary but can impede collection in domestic contexts and create compliance complexity in mixed-nationality environments.

**Ephemeral content:** Social media content, live streams, and web content are frequently deleted or modified after events. Content preservation and archiving must be built into collection procedures; delayed collection may lose evidence permanently.

**Attribution challenges:** Anonymous and pseudonymous online activity, VPN use, Tor networks, and coordinated inauthentic behavior complicate attribution of OSINT-derived indicators to specific actors.

**Deep web and dark web:** Content not indexed by standard search engines (deep web) and encrypted overlay networks (dark web) require specialized technical access. Dark web collection carries legal and policy complexities; DoD Manual 5240.01 and AR 381-10 constraints apply, and some dark web activities may require law enforcement coordination.

**Cultural and language barriers:** The global information environment is predominantly non-English. Without adequate language and cultural expertise, collectors miss nuance, misinterpret context, and may be deceived by culturally specific disinformation designed to exploit foreign analyst blind spots.

**Saturation / data overload:** The DIA OSINT Strategy 2024–2028 identifies the challenge of *"too much data"* as a central driver for AI/ML investment. The 2023 MIPB targeting experiment found that collectors and analysts had difficulty formulating focused collection requirements and managing the volume of available reporting.

**Doctrine and force structure gaps:** As of 2023, the Army *"does not currently have OSINT-specific collection management, all-source analysis, PED, and the associated tactics, techniques, and procedures for multidomain operations."* There are *"no established TTPs for OSINT integration into collection management and PED at echelons corps and below."* ([MIPB, OSINT Support to Targeting, 2023, Army.mil](https://mipb.ikn.army.mil/media/mkxlezii/2024-01-06-s_idx23_online.pdf))

---

## 9. Cross-Cueing Patterns

OSINT's role as an enabler of all other intelligence disciplines — its *"tip-off function"* — is arguably its most strategically under-utilized value. The IC OSINT Strategy 2024–2026 explicitly addresses the need to ensure *"the IC is not expending its most sensitive collection capabilities to obtain intelligence that can be derived from open source information,"* and the DIA OSINT Strategy 2024–2028 envisions OSINT as *"the premier source of intelligence information"* that *"provides broad insights for shaping collection plans, tips, and cues other collection capabilities, and fills gaps to round out all source analysis."* ([DIA OSINT Strategy 2024–2028, dia.mil](https://www.dia.mil/Portals/110/Documents/OSINT-Strategy.pdf))

### OSINT → All Classified INTs (Tip-Off Function)

OSINT provides the initial indicator that establishes a collection priority, enabling classification-protected collection systems to be tasked against known, validated targets rather than broad surveillance. JP 2-0 states: *"OSINT can reduce large target sets, quickly filling information gaps, allowing the more efficient use of low-density technical and HUMINT assets."* The MIPB targeting article describes the process: *"time-sensitive reporting and the associated processes will quickly enable dynamic, follow-on activities, such as tipping other assets for collection."* A social media indicator of a new military base can cue NGA commercial imagery; an AIS anomaly can cue SIGINT collection against a suspicious vessel. ([JP 2-0, Appendix B, p. B-7](https://www.usna.edu/Training/_files/documents/References/2C%20MQS%20References/2015-2016%20MQS/Joint%20Publication%20JP%202-0%20Joint%20Intelligence.pdf))

### OSINT → HUMINT (Target Development)

OSINT is a primary tool for HUMINT target development: identifying potential sources through social media activity, professional publications, conference attendance records, and publicly available biographical data; mapping organizational structures and identifying access and placement indicators; and establishing cover stories and elicitation approaches informed by a target's publicly expressed interests, concerns, and relationships. The MIPB "OSINT Conundrum" (2022) notes that *"ubiquitous data platforms, such as social media, present a virtually unlimited pool of potential sources, many of whom volunteer details of their placement and access online."*

### OSINT → IMINT (Cueing Commercial or NTM Imagery)

OSINT indicators (social media reporting of unusual military activity at a specific location; journalist photographs of equipment at a rail yard; AIS anomalies near a port) establish collection priorities that enable IMINT platforms to be tasked against specific coordinates rather than broad area surveillance. Commercial imagery orders can be placed within hours of an OSINT indicator; NTM collection requires more formal tasking through the national collection management system. The GEOINT-OSINT integration is the most mature cross-cueing relationship: NGA has used commercial imagery as an OSINT-adjacent product since the 1990s.

### OSINT → Cyber (Target Development for OCO/DCO)

Internet infrastructure data (WHOIS, passive DNS, BGP, certificate transparency logs) and dark web monitoring enable attribution of malicious cyber infrastructure to threat actors, identification of command-and-control domains, and development of targeting packages for Offensive Cyber Operations (OCO) or defensive actions (DCO). OSINT thus serves as the entry point for cyber targeting — establishing entity attribution and infrastructure mapping at the unclassified level before classified cyber collection confirms or elaborates. The 2023 MIPB targeting experiment included cyberspace operations representatives in the OSINT PED cell specifically to enable this cross-cue.

### OSINT as Ground Truth for SIGINT Geolocation

Commercial AIS and ADS-B data provide unclassified, independently verifiable ground truth for correlating SIGINT-derived vessel and aircraft tracks. When SIGINT collection geolocates an emitter to an approximate area, OSINT-derived AIS/ADS-B tracks can narrow the field of candidates or confirm the identity of the emitting platform — without requiring disclosure of SIGINT sources, methods, or capabilities. The MIPB "OSINT Conundrum" notes explicitly that AIS and ADS-B *"fit well into NSA's definition of electronic intelligence"* — the same data exists in both the OSINT and SIGINT tradespaces.

### OSINT for Battle Damage Assessment (BDA) in Publicly Visible Operations

In publicly visible operations (e.g., strikes on large fixed infrastructure targets, naval vessel casualties), OSINT provides a rapid, releasable BDA mechanism. Social media imagery, commercial satellite imagery, and local press reporting can confirm physical effects within hours of a strike. This capability was demonstrated repeatedly in coverage of the Russia-Ukraine conflict beginning in 2022, where commercial satellite imagery providers and OSINT investigators produced BDA products within hours of reported strikes. OSINT BDA is inherently limited for hardened, concealed, or deeply buried targets where physical effects are not visible in commercial imagery — but for operationally visible effects, it provides timely, releasable, and politically useful confirmation.

### Cross-Cueing by Discipline

| OSINT Source Type | Cues to INT | Mechanism |
|---|---|---|
| Social media force movement reporting | IMINT (NTM/commercial) | Location-specific tasking |
| AIS/ADS-B anomaly | SIGINT | Platform identity, emitter correlation |
| Biographic/organizational OSINT | HUMINT | Source identification and target development |
| Dark web / network infrastructure | Cyber (OCO/DCO) | Infrastructure attribution, target development |
| Commercial satellite imagery | All-source analysis | Independent BDA, pattern-of-life confirmation |
| Social media protest/civil unrest | HUMINT, IMINT | Ground truth for threat assessment |
| Foreign military doctrine publications | All-source analysis | Strategic intent and capability inference |

---

## References

All sources are publicly available and unclassified. Each claim above is cited inline with the originating publication and URL.

| Publication | Citation |
|---|---|
| JP 2-0, Joint Intelligence (2013) | [usna.edu](https://www.usna.edu/Training/_files/documents/References/2C%20MQS%20References/2015-2016%20MQS/Joint%20Publication%20JP%202-0%20Joint%20Intelligence.pdf) |
| ATP 2-22.9, Open Source Intelligence (2012) | [bits.de](https://www.bits.de/NRANEU/others/amd-us-archive/atp2-22-9(12).pdf) |
| DoDI 3115.12, Open Source Intelligence (2010, as amended 2020) | [esd.whs.mil](https://www.esd.whs.mil/Portals/54/Documents/DD/issuances/dodi/311512p.pdf) |
| IC OSINT Strategy 2024–2026 (ODNI/CIA, 8 March 2024) | [dni.gov](https://www.dni.gov/files/ODNI/documents/IC_OSINT_Strategy.pdf) |
| ICD 113, Functional Managers (19 May 2009) | [intel.gov](https://www.intel.gov/assets/documents/intelligence-community-directives/ICD_113.pdf) |
| ICD 301, National Open Source Enterprise (11 July 2006) | [publicintelligence.net](https://info.publicintelligence.net/ICD301.pdf) |
| DIA OSINT Strategy 2024–2028 | [dia.mil](https://www.dia.mil/Portals/110/Documents/OSINT-Strategy.pdf) |
| MIPB, "The OSINT Conundrum" (2022) | [army.mil/mipb](https://mipb.ikn.army.mil/media/dlvl0yrl/2022-04-se1-gack_osint-conundrum_online.pdf) |
| MIPB, "OSINT Support to Targeting" (2023) | [army.mil/mipb](https://mipb.ikn.army.mil/media/mkxlezii/2024-01-06-s_idx23_online.pdf) |
| ODNI Press Release No. 06-24 (8 March 2024) | [dni.gov](https://www.dni.gov/index.php/newsroom/press-releases/press-releases-2024/3784-odni-and-cia-release-the-intelligence-community-osint-strategy-for-2024-2026) |
| DCGS-A, DOT&E FY2016 Report | [osd.mil](https://www.dote.osd.mil/Portals/97/pub/reports/FY2016/army/2016dcgs-a.pdf) |
| EO 14117 (28 February 2024) / DoJ Data Security Program | [justice.gov](https://www.justice.gov/opa/pr/justice-department-implements-critical-national-security-program-protect-americans-sensitive) |
| USNI Proceedings, "OSINT: A Double-Edged Sword" (August 2018) | [usni.org](https://www.usni.org/magazines/proceedings/2018/august/open-source-intelligence-double-edged-sword) |
| Bellingcat, Shadow Analysis / Shadow Finder Tool | [bellingcat.com](https://www.bellingcat.com/resources/2020/12/03/using-the-sun-and-the-shadows-for-geolocation/) |
| CCDCOE, "Utilizing Air Traffic Communications for OSINT" (2018) | [ccdcoe.org](https://ccdcoe.org/uploads/2018/10/Art-16-Utilizing-Air-Traffic-Communications-for-OSINT-on-State-and-Government-Aircraft.pdf) |
| DIU Deepfake Detection CSO (DefenseScoop, June 2024) | [defensescoop.com](https://defensescoop.com/2024/06/26/why-diu-is-looking-to-speedily-buy-deepfake-detection-technology/) |

---

*Document compiled from publicly available US doctrine and IC publications. All content UNCLASSIFIED. Approved for public release: distribution unlimited.*


---

## See Also

- [JP 2-0 — Joint Intelligence](../02-joint-doctrine/jp-2-0-joint-intelligence.md) — Appendix B owns the doctrinal definitions for all INT disciplines
- [Sensor-to-Indicator Matching](../04-collection-process/05-sensor-to-indicator-matching.md) — how this INT pairs with others in collection planning
- [PED Architecture](../07-tools-and-systems/ped-architecture.md) — where this INT's data is exploited
- [Discipline Index](README.md)
- [CONTRIBUTING.md](../CONTRIBUTING.md)

*Page version 1.0 — Raven Conspiracy Collection Management Wiki*
