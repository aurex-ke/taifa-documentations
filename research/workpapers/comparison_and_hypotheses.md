# Step 4, part 2: comparison with baseline; hypothesis tests

Status: draft. Commit after part 1. No verdict and no recommendation here
(Phase 6 onward needs user instruction).

## A. Score comparison (baseline: 7 Medium, 6 Low, 4 None, 4 Not scorable)

| Item | Baseline | Blind re-test | Difference and driver |
|---|---|---|---|
| Losses, reliability, curtailment, captive solar, ToU, audits | Medium | Medium | Same. Confidence Low in both |
| Mini-grids | Medium | Low (borderline Medium) | **Differs.** 0.58% of generation (D-010); no fuel or cost data; 22% utilisation has an alternative explanation (standby capacity, external, unverified, I-012). Methodology puts "small or weakly supported" at Low. If the user prefers the Medium definition ("magnitude incomplete") the score reverts |
| Peak adequacy, thermal, concentration and imports, e-mobility, household, disputes | Low | Low | Same. I merged supply concentration and imports into S-06 |
| Pass-through, petroleum price and supply, pipeline and LPG, petroleum accidents | None | None | Same. I added biomass and network build-out as None |
| Variability, storage and net metering, household load as grid resource, electrical accident causes | Not scorable | Not scorable | Same, plus county and institutional listed as one item |

The substance agrees except for mini-grids. Given the independence limit above, this is weak confirmation.

## B. Where I read the evidence differently (more important than the scores)

| # | Baseline reading | Re-test reading | Basis |
|---|---|---|---|
| 1 | Curtailment "rose every month Feb to Jun" counts for H1 (E5) | Weak evidence of worsening. Monthly curtailment as a share of monthly generation: Jul 4.90%, Aug 3.76%, Feb 0.73%, Jun 3.65%. June is below Jul and Aug-25. FY-H2 total is +1.0% y/y (C-003). No prior-year monthly series, so seasonality cannot be separated from trend | C-032 (new), C-003, D-016, I-008 (new) |
| 2 | "Curtailment and ToU improved with no EMS reported" counts for H0 (E4) | Absence of reporting is not evidence (methodology section 2; I-005). What is reported: EPRA attributes the curtailment fall to higher night demand (D-014, D-015), a reported demand-side cause. The reports are silent on any EMS contribution | I-009 (new) |
| 3 | Reliability worsened in H2 | Sharper: SAIDI Mar-Jun mean 21.49 h vs Jul-Feb 8.99 h; the deterioration sits in four months. Flag 25 weakens the trend narrative: the AR's "complied" text conflicts with its own Fig 2.20 | C-034 (new), D-069, I-010 (new) |
| 4 | Row counts across levels favour C&I | Reports hold programme data for C&I-linked instruments (ToU, audits, captive capacity) and none for feeder or hourly behaviour. More rows at a level reflects what is reported, not necessarily greater need | I-011 (new) |
| 5 | H1 and H2 evidence rows treated as separate | AR repeats BR for Jul-Dec 2025 (I-001), so the BR/AR agreement is not independent confirmation | I-001 |
| 6 | Baseline H3(c) "an EMS would depend on data and flexibility rather than replace it" | This is a design claim ("follows from what an EMS is"), not a data finding. Under diagnosis-before-solutions I do not carry it forward as a hypothesis | Brief, ground rules |

## C. Hypotheses

**Operational meaning of "significant" (H1):** (i) a measured magnitude in the reports; (ii) a stated plausible causal link to monitoring, forecasting, optimisation or control; (iii) no evidence the need is already met. Evidence is "supporting" or "contradicting" only if it speaks to the hypothesis; missing data is listed separately and is not counted against anything. H0 and H1 are mutually exclusive; the others can co-hold.

| Hypothesis | Supporting | Contradicting | Missing / caveats | Confidence and rationale |
|---|---|---|---|---|
| **H0** Challenges do not require an EMS | Largest measured problems have reported non-EMS causes: losses physical and commercial (D-026), peak margin capacity (D-017, C-005). Petroleum, LPG and pass-through items have no EMS role (S-18 to S-21). Curtailment fall is attributed to demand (D-014, D-015). No item scores High | Reliability has no reported cause (D-028, D-029). Six items have a plausible mechanism (Medium). Captive solar growth is unobserved in the published data (D-004, I-006). H0 is a claim of absence, and the reports cannot see within-day, feeder or site behaviour | Hourly, feeder, site, captive-output data. Existing-system status (I-005) | **Low.** Partly supported for the largest network and capacity items; not established for flexibility and visibility items |
| **H1** Significant EMS need at one or more levels | Mechanism fit at several levels (S-03, S-08, S-10, S-11). Captive solar about half of national additions with no output data (D-004). New duties (M&V, wheeling, energy accounting) imply measurement (D-049, D-059). Reliability deterioration is mostly longer outages (C-029) | No item reaches High. No money or hourly value can be put on an EMS-addressable share. No adoption barrier that software would remove is shown. Curtailment fall is attributed to demand (I-009). Audit pool is 0.53% of sales | Share of any pool capturable by an EMS. Hourly profile. Eligible-customer counts. Implementation rates | **Low.** Plausible at several levels; criterion (ii) and (iii) are not met for any item, and the missing data is exactly what would size it. Not rejected |
| **H2a** Need exists but is already adequately served | Operator controls plant output in real time (D-065, I-004). ToU billing implies time-differentiated metering (I). Mini-grid site metering (D-047) | Loss and reliability targets unmet (D-026, D-028); this does not show an EMS is the missing piece | Whether SCADA, DMS, AMI, vendor tools exist (I-005) | **Not testable from the two reports.** If forced: Low |
| **H2b** Need exists but is better addressed another way | Losses: upgrades, meters, enforcement (D-026). Peak margin: capacity pipeline (D-059, C-005). Curtailment: night demand growth and tariff (D-014, D-015, D-034). Petroleum and LPG: logistics and policy | Reliability: cause unreported, so an alternative cannot be shown. Flexibility cluster: no alternative shown to be sufficient | Cause codes, contract terms | **Medium** for losses, peak margin, petroleum and LPG. **Low** for curtailment. **Not testable** for reliability |
| **H3** (new, evidence-limited) The published statistics cannot confirm or reject a need at most levels | Absence of hourly, feeder, site, captive-output, storage, price and existing-system data (I-005, I-006, S-15, S-16). Unresolved report conflicts on loss basis and H2 sales (C-008, C-009, I-003) | Some programme data exist for C&I instruments (D-034, D-035, D-051) | This describes the reports, not Kenya; it is near-certain as description and uninformative about need | **High** as a description of the reports. It sets the ceiling on every other confidence |
| **H4** (new, locus) Evidence for need is stronger at site or C&I level than at grid or utility level | Captive solar growth (D-004), ToU uptake (D-035), audits (D-051), PPAs for C&I solar (D-044), duties (D-049). Grid-level problems have reported non-EMS causes (H2b) | Reporting-availability bias (I-011). No adoption barrier shown at site level. Vendor tools unknown (H2a). ToU improved, audit pool small | Captive output, eligible counts, implementation rate, existing tools | **Low.** Consistent with the evidence, but partly produced by what the reports happen to measure |

## D. What this re-test does and does not change

- It confirms that no item can be scored High from the reports.
- It weakens two baseline evidence rows (curtailment trend, "improved without an EMS"), and drops baseline H3(c) as untestable.
- It lowers mini-grids to Low (borderline).
- It adds H3 and H4 and proposes new register rows (Block 3).
- It does not state a verdict. Verdict, ranking and recommendations remain for Phase 6 onward on your instruction.
