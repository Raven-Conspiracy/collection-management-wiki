# Contributing to the Collection Management Wiki

Welcome, choom. Read this before opening a PR.

## The Three Hard Rules

1. **Unclassified only.** No classified content, no CUI, no FOUO that hasn't been released through official channels. No tactics, techniques, signatures, frequencies, IP addresses, or unit dispositions that are not already in the public domain via JCS, service pubs, GAO, CRS, FAS, or manufacturer fact sheets. **When in doubt, leave it out.**

2. **Cite or it didn't happen.** Every doctrinal claim links to the publication number AND a public URL. Every platform spec links to a public source. No assertions without sources.

3. **Doctrinal voice.** Prefer direct quotes from doctrine. When paraphrasing, keep the doctrinal terminology exact (do not invent new terms — use what JP 2-01 / FM 2-0 / AFDP 2-0 / NWP 2-01 / MCWP 2-10 already established).

## Scope

In scope:
- US Joint and Service collection management doctrine
- US collection platforms (airborne, space, maritime, ground, SOF, cyber)
- Process artifacts: PIR/SIR/EEI, IC Matrix, ISR Sync Matrix, RFI templates
- Tasking authority chains, PED architecture, DCGS family
- Cross-walks between Joint and Service terminology
- Historical case studies (declassified or open-source only)

Out of scope (route to companion repos):
- Munitions, effects, EW employment → [munitions-uav-wiki](https://github.com/Raven-Conspiracy/munitions-uav-wiki)
- Order of battle data → [the-red-ledger](https://github.com/Raven-Conspiracy/the-red-ledger)
- Agent training corpus → [Inquisitor](https://github.com/Raven-Conspiracy/Inquisitor)
- Adversary doctrine (RU/PRC/DPRK/IRN collection systems) — separate wiki, future scope

## File and Folder Conventions

- **One topic per file.** One doctrinal publication per file. One platform per entry (multiple per file is OK if related, e.g., Group 1–2 small UAS).
- **kebab-case filenames** — `jp-2-01-joint-and-national-intel-support.md`.
- **Numbered prefixes** on process docs to enforce reading order — `01-`, `02-`, etc.
- **README.md** in each folder that has more than 3 files.
- **Frontmatter (informal):** First line is the H1 title. Second line is an italicized breadcrumb. Third line is `---`.

## Citation Format

Inline links to public sources are required. Use Markdown linking, not raw URLs:

✅ `According to [JP 2-01, Ch. III](https://www.jcs.mil/Doctrine/Joint-Doctrine-Pubs/2-0-Intelligence-Series/), CRM is...`

❌ `According to JP 2-01 (https://...), CRM is...`

For direct quotes, use blockquote + attribution:

```
> "Collection management authority constitutes the authority to establish, prioritize, and validate theater collection requirements."
> — JP 2-01, Ch. III
```

For platforms, every entry must include at least one public source URL (DoD/service fact sheet, GAO/CRS report, FAS, manufacturer public page).

## Platform Entry Template

When adding a new platform, use this exact block structure:

```markdown
### [Designation] — [Common Name]

**Operator:** [USAF / USA / USN / USMC / USCG / NRO / NGA / Joint]
**Type:** [HALE UAV / MALE UAV / Group X / Manned ISR / Satellite / Maritime / Ground]
**Status:** [Operational / Upgrading / Sundown / Retired]

| Attribute | Value |
|---|---|
| Collection Capability | [Sensors: EO/IR, SAR, GMTI, SIGINT, MASINT, hyperspectral...] |
| Endurance | |
| Ceiling | |
| Range | |
| Cruise Speed | |
| Payload | |
| Datalinks | [CDL / Ku/Ka SATCOM / Link-16 / TCDL] |
| PED Architecture | [AF DCGS / DCGS-A / DCGS-N / NSA / NGA] |
| Tasking Authority | [JFACC via ATO / Theater J2 / National] |
| Primary Mission Set | [What EEIs/SIRs this asset is best at answering] |
| Limitations | [Weather, jamming, threat ring, etc.] |

**Public sources:**
- [Source 1](url)
- [Source 2](url)
```

## Doctrine Page Template

```markdown
# [PUB NUMBER] — [Title]

_Doctrine Domain › [Sub-area]_

---

## Core Concept
[One-paragraph plain-language summary]

## Key Definitions
[Bulleted list of terms this pub owns, with direct quotes where possible]

## Process / Cycle / Framework
[Diagrams, lists, tables as needed]

## Roles and Responsibilities
[Who owns what under this pub]

## How It Connects
[Cross-references to other pubs and wiki sections]

## References
- [Pub link](url)
- [Companion/superseding documents](url)
```

## PR Process

1. Branch from `main` — `feature/short-description`
2. One topic per PR. Big PRs get rejected on principle.
3. Run a personal sanity check: are all links live? Any classified terms slipped in? Do quotes match the source?
4. Open PR with a one-paragraph summary of changes and the list of doctrinal sources cited.
5. Maintainer reviews. Approval requires at least one Raven Conspiracy maintainer.

## Style

- American English.
- Oxford comma, mandatory.
- Service terminology in their own pages (Army says "Information Collection," AF says "ISR" — don't normalize).
- Cross-walk explicitly when terms differ across services.
- No emojis in doctrinal sections. The Adeptus Administratum disapproves.
- Easter eggs from W40k, LOTR, and Cyberpunk 2077 lore in commentary headers and section openers are encouraged. Doctrine bodies stay clean.

## Security

If you believe content in this repo crosses a classification line, **do not open a public issue.** Email a Raven Conspiracy maintainer directly so we can review and remove before public discussion. Do not cite, share, or expand on the offending content in any public channel.

---

*By the Throne, contribute well.*
