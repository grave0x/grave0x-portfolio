# grave0x — portfolio

Services page + quote template for the software development business.
Live: https://grave0x.github.io/grave0x-portfolio/

## What's here

- `index.html` — services/portfolio page (single file, no build step)
- `quote-template.html` — print-ready quote with letterhead (A4; print to PDF)

## Evidence mapping

Artifacts for ABN commencement evidence (reapply with records of genuine
commencement activities):

| Checklist item | Artifact | Evidence to keep |
|---|---|---|
| 1. Website / portfolio | `index.html` — this repo, live URL above | URL + screenshot + creation date: 2026-10-07 |
| 3. Issued quote | `quote-template.html` — fill a copy, send to a client | the sent quote PDF + send record |
| 5. Stationery | the quote template's letterhead | the template file itself |

Creation date: **2026-10-07** (first commit). Keep records 5 years.

## Usage

- **Quote:** copy `quote-template.html`, fill the bracketed slots (client,
  work items, amounts, ABN once granted), print to PDF, send. The quote
  header doubles as the letterhead.
- **ABN:** once granted, add the ABN to the footer in `index.html` (a
  comment marks the slot) and the letterhead in `quote-template.html`.

## Verify

Open the live URL, or locally: `firefox file://$PWD/index.html`.
