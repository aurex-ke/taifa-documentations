# Step 5: Phase 6 verdict (independent re-test)

Status: draft. Built on step4_part1_blind_scoring.md and
step4_part2_comparison_and_hypotheses.md. "Not scorable" accepted by the user as
a valid, flagged extension of the four-level scale. Evidence IDs refer to
knowledge-base/evidence_register.md (highest: D-074, C-035, I-012).

**Independence note.** The baseline text was in the chat context throughout.
The verdict was reasoned from my own scores and hypothesis tests, but I knew
the baseline's label ("partially confirmed, low confidence"). My label differs;
the reason is in section 3.

## 1. Verdict

**Inconclusive.**

The two EPRA reports show large, measured problems. They do not show that any
of those problems is one that monitoring, forecasting, optimisation or control
would address. They also cannot show whether such capability already exists
(I-005). Absence of data is a data gap, not evidence against need.

**Confidence.**
- That "Inconclusive" is the right label on these two reports: **Medium**.
- In any statement about the need itself (present or absent): **Low**.

## 2. Test of each scored item against the three criteria for "significant"

Criteria (from step4 part 2): (i) measured magnitude in the reports; (ii) a
stated, plausible causal link to monitoring, forecasting, optimisation or
control; (iii) no evidence the need is already met.

| Item (score) | (i) Magnitude | (ii) Causal link | (iii) Not already met | Evidence |
|---|---|---|---|---|
| Losses (Medium) | Met: 21.38% vs 16.5% allowance; pool 582-761 GWh | Partial: only the metering and visibility share; split and location unreported; remedy may be AMI or enforcement | Unknown | D-026, C-008, C-030, I-003 |
| Reliability (Medium) | Met: SAIDI 13.16 h vs 1.5; worst in five years | Not met: causes unreported | Unknown | D-028, D-029, C-034, I-010 |
| Curtailment (Medium) | Met: 403.94 GWh, 2.57% of generation | Partial: mechanism plausible; hourly profile, contract terms, price missing | Unknown; operator control exists (D-065) | D-014, D-015, D-070, D-071, C-032, I-008 |
| Captive solar (Medium) | Partial: capacity growth shown, output not | Partial | Unknown | D-004, D-043, I-006 |
| ToU (Medium) | Partial: realised savings known; unclaimed potential not | Partial | Unknown | D-034, D-035, I-007, C-035 |
| Audits and M&V (Medium) | Partial: 65.53 GWh identified (0.53% of sales); implementation unknown | Partial | Unknown | D-049, D-051, C-021 |

No item meets all three criteria. Every row has at least one "Unknown" or
"Not met" that the two reports cannot resolve.

## 3. Why Inconclusive and not the neighbouring labels

| Label | Why not |
|---|---|
| Need confirmed | No item scores High (step4 part 1). No criterion set is fully met for any item |
| Need partially confirmed | Would rest on mechanism fit plus a visibility gap (captive solar). Methodology section 5: "If evidence is insufficient, use an inconclusive verdict rather than filling gaps." A visibility gap in published statistics (I-006) is not evidence of an unmet need; utility or regulator records may hold the data. The baseline reached "partially confirmed" at the boundary; this is a judgment call, not a finding that the baseline is wrong |
| Need not confirmed | Would require positive evidence of no need. The reports cannot see within-day, feeder or site behaviour (I-005, I-011), and H0 reached only Low confidence |

## 4. Verdict by level

| Level | Label | Confidence | Basis |
|---|---|---|---|
| National / grid (operator) | Inconclusive | Low | Curtailment and thermal dispatch have a fitting mechanism; hourly data, contract terms and price are missing; real-time control exists in some form (D-065, I-004) |
| Utility (distribution) | Inconclusive | Low | Largest measured problems, but causes are unreported (reliability) or mainly physical and commercial (losses). Feeder analytics sits at the edge of the EMS definition |
| County | Inconclusive (no data) | n/a | Data are by KPLC region only (D-022) |
| Mini-grid | Inconclusive | Low | 0.58% of generation; no fuel or cost data; 22% utilisation has an alternative explanation (C-031, I-012) |
| C&I (including captive solar, ToU, audits) | Inconclusive; the level with the most supporting observations | Low | Observation counts partly reflect what the reports measure (I-011). No software-removable barrier shown. Existing vendor tools unknown (H2a) |
| Institutional / public buildings | Inconclusive (no data) | n/a | No institutional consumption reported |
| Household | Need not confirmed | Low | No time-varying domestic price signal (inference from AR p.26); about 99 kWh per customer-month, all categories pooled (C-022) |
| E-mobility | Need not confirmed (watch item) | Low | About 1.4 MW average load (C-031); 543 customers (D-060) |
| Petroleum, LPG, pass-through costs | Need not confirmed | Medium | Reported causes are world prices, FX, logistics and driver error (D-061, D-032, D-058), not EMS-addressable |

## 5. What would change the verdict

| Additional evidence | Direction |
|---|---|
| Hourly load, curtailment and dispatch data showing night surplus overlapping evening thermal or import use, plus an energy price | Toward Partially confirmed (national/grid) |
| Captive solar output, site counts, exports and PPA terms showing material unmanaged or exported energy | Toward Partially confirmed (C&I) |
| Feeder-level losses and outage cause codes showing locatable losses or restoration delay | Toward Partially confirmed (utility) if visibility-driven; toward Not confirmed if capital or asset-driven |
| ToU eligible-customer counts and non-uptake reasons showing a scheduling barrier | Toward Partially confirmed (ToU) |
| Audit implementation rates and designated-facility counts | Either direction (audits and M&V) |
| Mini-grid fuel use and cost per kWh | Either direction (mini-grids) |
| Evidence that SCADA, DMS, AMI or customer EMS tools already cover these uses | Toward Need not confirmed for a new build (H2a) |
| Load-shedding or unserved-energy records showing a capacity shortfall | Toward a capacity question (H2b) at national level |
| Prior-year monthly curtailment series | Resolves whether the Feb-Jun rise is trend or seasonality (I-008) |

## 6. Strongest evidence for and against

- **For (supporting a need):** captive solar capacity grew by 72.8 MW (+24.22%), about 49.7% of national capacity additions, and the reports give no output, site count or export figure for it (D-004, I-006). Caveat: this is a gap in published data, not shown to be an operational gap.
- **Against (contradicting a need):** the largest measured problem, losses of 21.38% against a 16.5% allowance, has reported physical and commercial causes (D-026), and the peak-margin pressure has capacity and transmission projects in train (C-005, D-059). Caveat: the loss split and rate basis are unreported (C-008, I-003).

## 7. Consequence for the brief's output contract

The verdict is not positive or partially positive, so Phase 7 (EMS type and
level recommendation) is **not applicable**. Report section 7 would state that.
Phase 8 (deliverables) and Phase 9 (data gaps and follow-up research) still
apply, tailored to an inconclusive finding.

## 8. Limits

- Two statistical summaries, one year of data, nothing after 30 Jun 2026.
- AR repeats BR for Jul-Dec 2025, so the sources are not independent (I-001).
- Score and hypothesis confidences are analytical judgments, not measurements.
- Unresolved report conflicts (loss rate basis, H2 sales, reliability index basis, flag 25) reduce confidence in the sizes used.