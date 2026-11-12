# Taifa Energy Management System

This repository contains the sources, research notes, and deliverables for an
evidence-led study of whether Kenya needs an Energy Management System (EMS),
and at what level or in what form.

## Repository map

- [`data/raw/`](data/raw/) — original source documents; preserve these unchanged.
- [`data/processed/`](data/processed/) — extracted or transformed data, with
  traceability to the original source.
- [`data/source_register.csv`](data/source_register.csv) — source inventory and
  metadata verification status.
- [`knowledge-base/source-notes/`](knowledge-base/source-notes/) — source-level
  notes and extraction references.
- [`knowledge-base/`](knowledge-base/) — reusable definitions and cited
  evidence extracted from sources.
- [`research/`](research/) — the research brief, methodology, and analysis
  workpapers in [`research/workpapers/`](research/workpapers/).
- [`output/`](output/) — reviewed reports and other deliverables, including
  [`output/evidence-tables/`](output/evidence-tables/) and
  [`output/follow-up/`](output/follow-up/).

## Start here

1. Read [`research/research_brief.md`](research/research_brief.md) for the
   question, scope, analysis phases, and required report format.
2. Verify each source and its coverage in
   [`data/source_register.csv`](data/source_register.csv).
3. Follow [`research/methodology.md`](research/methodology.md) while extracting
   and analyzing evidence.
4. Record terms and source-backed statements in
   [`knowledge-base/definitions.md`](knowledge-base/definitions.md) and
   [`knowledge-base/evidence_register.md`](knowledge-base/evidence_register.md).
5. Draft the final study in [`output/research_report.md`](output/research_report.md).

## Evidence and change rules

- Keep original reports unchanged. Record page, section, table, and other
  locators for extracted claims whenever available.
- Label claims as **DATA**, **CALCULATION**, or **INTERPRETATION**.
- Separate report evidence from external information; label external material
  **external, unverified** until independently verified.
- Do not infer a need for an EMS in advance. Record contradictory evidence,
  data gaps, and uncertainty.
- Do not publish a verdict or recommendations until the diagnostic and
  hypothesis-testing stages are complete.
- Treat energy-use and customer data as potentially sensitive; avoid adding
  personal or site-identifiable data unless necessary and appropriately
  protected.

## Current status

The two EPRA reports named in the research brief are stored under
[`data/raw/epra/`](data/raw/epra/). Their report metadata and exact coverage
periods still need to be verified against the documents before analysis.
