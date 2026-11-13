# Step 6: Phases 7-9 for an Inconclusive verdict

Status: draft. Built on verdict.md (accepted by the user as "Inconclusive").
Evidence IDs refer to knowledge-base/evidence_register.md (highest D-074,
C-035, I-012). AR = Energy & Petroleum Statistics Report (yr to 30 Jun 2026);
BR = Biannual report (Jul-Dec 2025).

## 1. Phase 7 (EMS type and level)

**Not applicable.** The Phase 6 verdict is Inconclusive, not positive or
partially positive (brief Phase 7; methodology section 7). No EMS type, level
ranking, "where to start" or open-source suitability assessment is made.
Report section 7 should state this in one or two sentences.

## 2. Phase 8: recommended deliverables

**Principle (INTERPRETATION).** Where the verdict is Inconclusive, the
deliverables that follow should reduce the uncertainty. They should not assume
a need. Each is tied to the missing evidence that blocks the verdict (verdict
section 5). Priority = order in which the deliverable should come, not
importance of an EMS.

| # | Deliverable | Purpose | Priority | Evidence that justifies it | What it could change |
|---|---|---|---|---|---|
| 1 | Data request and validation brief | Request the figures the two reports lack: hourly load, curtailment and dispatch plus an energy price; feeder-level losses and outage cause codes; captive solar output, sites, exports and PPA terms; ToU eligible-customer counts and non-uptake reasons; audit implementation rates and designated-facility count; mini-grid fuel use and cost per kWh; load-shedding or unserved-energy records; prior-year monthly curtailment | 1 | I-005 (no hourly, feeder, site, storage data); I-006 (captive output unreported); D-016 and I-008 (no prior-year monthly curtailment); I-007 (ToU eligible count undefined); D-051 (audit implementation unreported); C-031 and I-012 (mini-grid) | Every "toward Partially confirmed / Not confirmed" row in verdict section 5 |
| 2 | Existing-capability scan (tests H2a) | Find out what monitoring, forecasting and control tools already exist or are in use at system operator, utility and C&I level. This is the only way to test "need already met". Findings are external research: label **external, unverified** until sources are checked | 1 | I-005 and verdict section 2 criterion (iii): "not already met" is Unknown for every item; I-004 and D-065 (operator control exists, tools unnamed) | Toward Need not confirmed for a new build, if existing tools cover the uses |
| 3 | Decision-rule note (pre-set criteria) | Write down, before the data arrive, what result would move each level to Partially confirmed or Not confirmed, using the three criteria for "significant" (measured magnitude; plausible causal link; not already met). Guards against reading new data to fit a preferred answer | 2 | Verdict sections 2 and 5; step 4 part 2 section C | Keeps the re-test neutral |
| 4 | Narrow problem statement | A diagnostic statement of what is measured (losses, reliability, curtailment, captive solar growth), what is not shown to be an EMS problem, and what is unknown. States no solution | 2 | Verdict sections 1-4; D-026, D-028, D-004 | Gives funders or partners an honest basis; avoids overstating |
| 5 | Data-quality note for EPRA | A short, neutral list of report conflicts for correction in a later edition. Each item must be re-checked in the PDF before it is sent | 2 | C-008 (loss rate not reproducible); C-009 (H2 sales); D-069 (CAIDI "complied" text vs Fig 2.20); D-053 vs D-054 (solar technician rows); C-012 and D-066 (imports, thermal text vs figures); C-016 (Coast share); D-006 vs D-007 (off-grid capacity); D-029 (lowest SAIFI month) | Better loss and reliability baselines; may resolve I-003 |
| 6 | Stakeholder and data-holder map | Identify who holds each missing dataset (EPRA, KPLC, KETRACO, system operator, captive owners, auditors, REREC) and who must consent | 3 (after 1 shows data exist) | AR names these actors (D-025, D-044, D-053, D-057); who holds hourly data is not stated (I-006) | Routes deliverable 1 |
| 7 | Data-handling and privacy plan | Only if site or customer-level data are obtained: consent, retention, access, anonymisation (README rule on sensitive data) | 3, conditional | README "Evidence and change rules"; AGENTS.md | Needed before any site-level collection |

### Not recommended at this stage

| Item | Reason |
|---|---|
| Requirements specification, architecture outline, pilot design | These assume a need. The verdict does not support one (verdict section 3) |
| Funding or partnership approach | Same reason. A validation-only framing could come after deliverables 1 and 2 |
| Open-source assessment (external projects) | Premature and outside the diagnosis. Would be external, unverified |
| Any EMS work on petroleum, LPG, pass-through, household, e-mobility | Verdict section 4: Need not confirmed; no EMS-addressable cause or size shown |
| County or institutional analysis | No data in either report (D-022); covered by deliverable 1 |

### Suggested order (no time estimates; the reports support none)

| Step | Deliverables | Decision at end |
|---|---|---|
| A | 1, 2, 3 | Does any missing evidence change a level's label? |
| B | 4, 5 (and 6 if A found data holders) | Share the problem statement and data note |
| C | 7, only if site or customer data are obtained | Collect data under agreed terms |

If step A shows existing tools already serve the uses, or pools are small in
money terms, stopping is a valid outcome.

## 3. Phase 9: data gaps and follow-up research

| # | Gap or uncertainty | Why it matters | Follow-up | How it could affect the verdict |
|---|---|---|---|---|
| G1 | Hourly load, curtailment, dispatch; energy price (I-005, D-016) | Cannot test whether night surplus overlaps evening thermal or import use, or value curtailment (S-03) | Data request (deliverable 1) | Toward Partially confirmed (national/grid) if overlap and value are large |
| G2 | Prior-year monthly curtailment (I-008) | Cannot separate trend from seasonality in the Feb-Jun rise | Data request | Resolves whether curtailment is worsening |
| G3 | Feeder or transformer losses; technical vs commercial split; loss formula (D-026, C-008, I-003) | Loss rate not reproducible (20.23% vs 21.38% AR; 23.48% vs 22.07% BR); causes and location unknown | Data request; data-quality note | Toward Partially confirmed (utility) if locatable and visibility-driven; toward Not confirmed if capital or physical |
| G4 | Outage cause codes, planned vs unplanned, index basis (D-028, D-029, D-069, I-010) | Reliability is the largest unexplained deterioration; deterioration sits in Mar-Jun (C-034) | Data request | Same logic as G3 |
| G5 | Captive solar output, sites, exports, PPA prices, storage (D-003, D-044, I-006) | The "visibility gap" may be only a gap in published data | Data request; regulator licensing returns | Toward Partially confirmed (C&I) if material energy is unmanaged or exported |
| G6 | ToU eligible customers and non-uptake reasons; meaning of "Customers in Tariff" (I-007) | Cannot tell whether a scheduling barrier exists | Data request; ask EPRA what the column means | Toward Partially confirmed (ToU) if a scheduling barrier is shown |
| G7 | Audit implementation rate; number of designated facilities (D-049, D-051) | Pool is 0.53% of sales (C-021); realisation unknown | Data request | Either direction |
| G8 | Mini-grid fuel use, unit cost, outages; private mini-grids (D-006, D-007, D-047, C-031, I-012) | 0.58% of generation; 22% utilisation may reflect standby capacity (external, unverified) | Data request; REREC and KPLC | Either direction |
| G9 | Existing EMS, SCADA, DMS, AMI, vendor tools (I-005, I-004) | H2a cannot be tested from the reports | Capability scan (deliverable 2) | Toward Need not confirmed for a new build |
| G10 | Load-shedding or unserved-energy records (C-005, D-059) | Peak margin narrowed by about 127 MW (C-005) but no shortfall is reported | Data request | Toward a capacity question (H2b) |
| G11 | Storage capacity and net metering (I-005, D-044) | Absent from every table; one PPA storage figure ("7,500MWh") looks implausible (D-044) | Data request; check the PPA | Cannot classify now |
| G12 | County and institutional or public-building consumption (D-022) | No data at these levels | Data request | Currently unscoreable |
| G13 | E-mobility vehicle and charger counts, charging profiles (D-060) | Only 543 tariff customers and 12.25 GWh reported | Data request; watch the e-mobility regulations in development (D-060) | Could move e-mobility from Not confirmed |
| G14 | Wind and hydro forecast error, reserve or balancing cost (D-072) | Monthly swing of about 103 GWh is known; forecast value is not | Data request | Could make variability scorable |
| G15 | Independent source for Jul-Dec 2025 (I-001) | AR repeats BR, so agreement is not confirmation | Obtain a source not derived from these reports | Raises confidence in all figures |
| G16 | Data after 30 June 2026 (reports end then) | First oil, next tariff period, open-access operation are forward-looking (D-059) | Later EPRA releases | Possible context change |
| G17 | AR publication date not stated | Metadata completeness | Leave as "Not stated" (user decision) | None |
| G18 | Fig 7.2 energy balance (AR p.61) has no numeric values; final consumption exceeds supply (C-024) | Energy balance cannot be reconciled | Ask EPRA for the table | Low effect on EMS question |
| G19 | Unresolved report conflicts (C-008, C-009, D-069, D-053, C-012, C-016, D-006/D-007) | Lower confidence in the sizes used | Data-quality note | Could shift sizes in G3 and G4 |

### Claims needing external work (all external, unverified until checked)

| Claim | Where it appears | Needed check |
|---|---|---|
| Weather or long-rains link to the Mar-Jun reliability dip | I-010 | Outage cause data or an independent source |
| Standby capacity explains mini-grid utilisation | I-012 | Station records |
| Vendor-tool landscape for C&I monitoring | verdict section 4 | Capability scan (deliverable 2) |

## 4. Consequence for the report

- Section 7: "Not applicable: the verdict is Inconclusive."
- Section 8: use the Phase 8 table above (deliverables 1-7, with the "not
  recommended" list).
- Section 9: use the Phase 9 table.
- The report must end with the strongest evidence for and against, as in
  verdict.md section 6.
  