# Templates and Formats

_Templates › Index_

---

Reusable templates for the artifacts a collection manager produces. All templates are markdown-first so they version cleanly in Git. Convert to spreadsheet/PowerPoint/Word as your unit's SOP requires.

## Available Templates

### Requirements
- [PIR Worksheet](pir-worksheet.md) — author and validate a PIR
- [EEI Worksheet](eei-worksheet.md) — decompose a SIR into EEIs
- [SOR Template](sor-template.md) — Specific Orders & Requests, ready to push to a COM cell

### Plans
- [Collection Plan Template](collection-plan-template.md) — the master plan, row-by-row
- [IC Matrix Template](ic-matrix-template.md) — Army-style Information Collection Matrix (ATP 2-01)
- [ISR Sync Matrix Template](isr-sync-matrix-template.md) — Joint/AF-style ISR Synchronization Matrix

### Requests
- [RFI Template](rfi-template.md) — outbound Request for Information
- [RFI Disposition Template](rfi-disposition-template.md) — inbound RFI disposition record

### Assessment
- [Collection Assessment Template](collection-assessment-template.md) — did the EEI get answered?

## Usage Convention

Each template includes:
1. **Header block** — IDs, timestamps, classification, originator
2. **Body** — the actual content with placeholder text in `[brackets]`
3. **Footer** — distribution, references, version control

Replace `[bracketed]` placeholders before use. Do not commit a template instance with classified content into this public repo.
