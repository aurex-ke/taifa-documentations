# Research methodology

This document operationalizes the requirements in
[`research_brief.md`](./research_brief.md). It is a working protocol, not a
source of evidence or a conclusion about whether Kenya needs an EMS.

## 1. Source control and inventory

1. Preserve original reports in `data/raw/`; do not edit or replace them.
2. Record each source in `data/source_register.csv`.
3. Verify report title, publisher, publication date, reporting period, edition,
   and document pagination from the report itself. A filename or this brief is
   not sufficient verification.
4. Record extraction date, method, and relevant limitations for processed
   files. Store derived data in `data/processed/` and link each value to its
   report locator.
5. If a PDF page label differs from the PDF viewer's page number, record both.

## 2. Evidence capture

For each potentially relevant fact, record:

- A stable evidence ID
- The source ID and exact title
- Report page (printed and/or PDF page), section, table, and row/column where
  available
- A concise statement faithful to the source
- The original unit, time period, geography, and population/category
- Evidence type: DATA, CALCULATION, or INTERPRETATION
- Any caveat, definition, or comparability issue

Prefer the report's own tables and definitions. Do not treat an absence of
reporting as proof that an activity or capability does not exist.

## 3. Calculations and comparisons

- Show the formula, inputs, units, and source locator for every calculation.
- Preserve source precision; do not imply more precision than the inputs
  support.
- Compare periods only after checking whether definitions, coverage,
  measurement, and reporting methods are comparable.
- Explain treatment of rounding, missing values, revisions, and conflicting
  figures.
- Do not combine data across different time periods or populations without
  explaining the basis and limitation.

## 4. Analysis sequence

Complete the stages in order: inventory and limitations; broad observations;
problem/opportunity assessment; root-cause and EMS solution-fit test;
hypothesis testing; verdict; and only then, if warranted, EMS recommendations
and follow-on deliverables.

An observation is not automatically a problem. An identified problem is not
automatically an EMS problem. Consider non-EMS causes and solutions, evidence
of existing capabilities, contradictory evidence, and the possibility that
the reports do not support a conclusion.

Use the relevance scale consistently:

- **High:** Report evidence identifies a material issue that monitoring,
  forecasting, optimization, or control could plausibly address; explain the
  causal link and limitations.
- **Medium:** An EMS capability may help, but evidence, magnitude, feasibility,
  or causal attribution is incomplete.
- **Low:** The connection is indirect, small, or weakly supported.
- **None:** The evidence does not support a meaningful EMS contribution, or a
  different intervention is clearly more relevant.

These are analytical judgments, not measurements. Justify each score.

## 5. Hypotheses, confidence, and uncertainty

For each hypothesis, list supporting evidence, contradicting evidence, missing
evidence, and a confidence level with a brief rationale. Do not equate lack of
data with evidence against a hypothesis. Distinguish national-level evidence
from evidence about a specific user group or deployment level.

Maintain a data-gap and inconsistency list. State what additional evidence
could change the verdict. If evidence is insufficient, use an inconclusive
verdict rather than filling gaps with assumptions.

## 6. External information

The core verdict must be grounded in the EPRA reports. If external sources are
needed for context, label each use **external, unverified** until its source,
date, and claims are independently checked. Clearly separate it from report
evidence and do not use it to silently fill a report-data gap.

## 7. Review before publication

- Check every quantitative claim against its source and calculation.
- Check every finding for a citation and evidence-type label.
- Check that claims, caveats, and report periods are internally consistent.
- Check that contradictory evidence and data limitations are visible.
- Check that the executive summary matches the body and stays within 250
  words.
- Check that EMS recommendations appear only if the verdict is positive or
  partially positive.
- End with the strongest evidence for and against the conclusion.