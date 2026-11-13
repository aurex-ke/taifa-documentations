# Step 3: baseline report review, part 2 (§4-§9)

Status: draft. Scope: facts, calculations and citations only. Relevance scores,
hypothesis confidence, verdict and ranking are judgments (Step 4+).
AR = Energy & Petroleum Statistics Report (yr to 30 Jun 2026); BR = Biannual
report (Jul-Dec 2025). Verdicts: Confirmed / Corrected / Unverifiable /
Conflicts between reports. Calculations rerun by script.

## A. §4 Problems and opportunities: facts and numbers

| ID | Baseline location | Claim | Source locator | Verdict | Note |
|---|---|---|---|---|---|
| P2-01 | §4.1 Losses | 3.16 TWh lost; 1.65x imports; 582-761 GWh above allowance; KSh 6-14 bn; each 1 pp = 156 GWh = KSh 1.6-2.9 bn | AR p.22 §2.1.12 | Confirmed (C) | 3,156.31 GWh; 5.8-14.1 bn; 1.56-2.90 bn. Valuation at KSh 10 to 18.57/kWh uses base energy charges, not utility purchase cost: illustrative, as labelled |
| P2-02 | §4.1 | LV lines 72.79% of 334,157 km; utility bears loss above allowance | AR p.20 §2.1.10; p.22 | Confirmed | |
| P2-03 | §4.1 Reliability | About 73% of H1->H2 SAIDI rise is longer outages, 27% more frequent | BR p.18 T2.2; AR p.24-25 | Confirmed, method noted | Log split of means: duration 71.0%, frequency 26.0%, residual 3% (mean of monthly products differs from product of means). Baseline normalises to 73/27. H1 means are BR; H2 means are the mean of AR Jan-Jun months |
| P2-04 | §4.1 | Five transmission facilities commissioned | AR p.20 | Confirmed | |
| P2-05 | §4.2 Peak | Interconnected +71 MW vs peak +198 MW; margin narrowed about 127 MW; 5% peak cut = 126 MW | AR p.13, p.16 | Confirmed (C) | 71.02; 198.06; 125.7. Jun-25 split derived, not reported (C-005) |
| P2-06 | §4.2 | Pipeline: Olkaria I rehab, Ethiopia to 400 MW, four 132 kV lines | AR p.71 Ch9; p.26 PPA 7 | Confirmed | |
| P2-07 | §4.2 Thermal | FEC mean KSh 3.34/kWh; recovery about KSh 41.6 bn; 100 GWh = KSh 3.0-3.2 bn and 64 kt CO2 | AR p.27 T2.5; p.31 | Confirmed (C), assumptions stated | FEC mean 3.344; 41.6 bn assumes FEC covers only thermal fuel and is charged on all sales. Implied KSh 31.8 per thermal kWh. 0.637 t/MWh assumes all grid CO2 is thermal. "So part is must-run" is INTERPRETATION, though placed in the "reported" column |
| P2-08 | §4.2 Curtailment | ToU volume +87.5 GWh = 33% of curtailment fall; imports within -11% / +8% of monthly mean; wind curtailed at contracted thresholds | AR p.29 T2.7; p.18-19 | Confirmed | 33.0%; -10.7% / +8.1% |
| P2-09 | §4.2 Variability | Wind and hydro swing about 100 GWh best to worst month | AR pp.34-35 Figs 3.4, 3.6 | Confirmed | Wind 102.69; hydro 102.82 |
| P2-10 | §4.3 Captive | PPA prices not reported; C&I retail KSh 17.3-26.1 | BR p.21 T2.4; AR p.36-37 | Confirmed | Range is Jul-Dec 2025 only (BR). AR shows the series only as a chart (Fig 2.26) |
| P2-11 | §4.3 Household | Domestic customers not eligible for ToU | AR p.26 §2.2.2 | Confirmed (inferred) | AR lists eligible categories (small commercial > 100 kWh, e-mobility, C&I); domestic is not listed |
| P2-12 | §4.3 ToU | About 60 MW average added off-peak demand | AR p.28 T2.6 | Confirmed (C), caveat | Mean of the "Increase in demand" column = 60.32 MW. The column is not defined in the report, so "added off-peak demand" is INTERPRETATION |
| P2-13 | §4.3 Audits | KSh 1.1-1.7 bn; 180,000 kWh/yr = 15,000 kWh/month | AR p.43; BR p.21 | Confirmed (C) | 1.13-1.71 bn (C&I rate range from BR T2.4); 180,000 / 12 = 15,000 |
| P2-14 | §4.4 Pass-through | About KSh 5.0/kWh = 16.5-19.7% of DC3 retail; about KSh 62 bn/yr | BR p.23 T2.5; AR p.27 | Confirmed (C) | Mean 5.00; 16.46% (Dec) and 19.71% (Oct). 62.3 bn assumes all components on all FY sales |
| P2-15 | §4.4 Petroleum | KSh 10/L = KSh 63 bn/yr (upper bound) | AR p.51 | Confirmed (C) | 6,330.5 m litres x 10 = 63.3 bn; includes Jet A1 so an upper bound |
| P2-16 | §4.4 Disputes and accidents | 187 disputes; 1.8 per 100,000 customers; 121 petroleum/LPG accidents, 22 deaths, 46.3% driver error; 129 electrical, 82 deaths | AR pp.67-69 | Confirmed | 1.79 per 100,000 |
| P2-17 | §4.5 | ToU billing for about 2,614 beneficiaries "(AR T2.6-2.7, source Kenya Power)" | AR p.28-29; BR p.23 | Corrected (locator) | The "Source: Kenya Power" note is under BR Table 2.6 (p.23), not in the AR |
| P2-18 | §4.5 | Site-level mini-grid generation; Mwingi solar-plus-battery PPA | BR pp.16-17; AR p.37 | Confirmed | |
| P2-19 | §4.5, §2.6 | Reports never mention SCADA, EMS, DMS, AMI, demand response, forecasting, load shedding, software | Both (text search) | Confirmed as absence | Zero hits for these terms in both reports. Hits: "battery" 1 (AR p.37), "metering" 1 (AR p.71), "dispatch" 1 (BR p.20, thermal power dispatch), "dispatchable" (AR p.40). "Storage" has 37 + 11 hits, almost all fuel storage; the claim that electricity storage is absent rests on reading, not on the search. Figures and images not searched |
| P2-20 | §4.6 | 7 Medium, 6 Low, 4 None, 4 Not scorable; all 7 Medium carry Low confidence | §4.1-4.5 | Confirmed (internal) | Counts match the tables |

## B. §5-§6 facts inside the hypothesis and verdict text

| ID | Baseline location | Claim | Source locator | Verdict | Note |
|---|---|---|---|---|---|
| P2-21 | §5.3 H2a | "All reliability indices exceed targets" | AR pp.23-25 | Qualified | True for FY2025/26 (CAIDI 3.23 vs 1.36; SAIDI 13.16 vs 1.50; SAIFI 3.91 vs 1.10). Scope the statement to FY2025/26 |
| P2-22 | §5.3 H2a, §6.1 | Losses above allowance for five years | AR p.22-23 | Confirmed | 22.84, 23.40, 23.21, 23.36, 21.38 vs 19.5, 19.5, 18.5, 17.5, 16.5 |
| P2-23 | §5.2 E4, §6.5 | ToU low-rate sales +48.5% | AR p.28 | Confirmed | Report text 48.47%; recompute 48.58% (180.1) or 48.42% (180.3) |
| P2-24 | §5.4 | Pool sizes (losses, audits, ToU, thermal fuel) | AR as above | Confirmed (C) | See P2-01, P2-07, P2-13. The baseline says no capture share is assumed |
| P2-25 | §5.2-6.4 | "24 flags" | §2.5 | Corrected | Now 26 flags (see section D). The count appears in §5.2 E9, §5.3 H3(a), §6.3, §7.1 and §8.1 |
| P2-26 | Exec summary | Max 250 words; matches body | n/a | Confirmed | 209 words (word count of the section). Verdict, "no item scores High" and "start with validation then read-only C&I pilot" match §4.6, §6, §7.4 |

## C. §7-§9 facts and citations

| ID | Baseline location | Claim | Source locator | Verdict | Note |
|---|---|---|---|---|---|
| P2-27 | §7.1 | Large C&I 47.57%; captive 676.6 MW incl. 373.3 solar; 156 audits; 65.53 GWh | AR p.13, p.17, p.43 | Confirmed | |
| P2-28 | §7.1 | Audit pool = 3.5 kt CO2 (grid average) and 42 kt (thermal-implied), ceilings | AR p.31, p.43 | Confirmed (C) | 3.50 and 41.7 kt. Rules require only 50% of projected savings, so "ceiling at full implementation" is accurate |
| P2-29 | §7.1 | At least 8 named mini-grid stations; top three 58.8%; KPLC operates | BR p.17 Fig 2.9; AR p.21 | Confirmed | |
| P2-30 | §7.1, §7.4 | Energy Management Regs: audits every 4 years, >= 50% savings, manager, committee, ESCO licensing | AR p.43; BR p.31 | Confirmed | Manager and committee appear only in BR (p.31); benchmarks and ESCO licensing only in AR |
| P2-31 | §7.1, §7.3 | Open Access Regs 2026 (wheeling, metering, energy accounting); North Eastern +14.61% | AR p.71; p.18 | Confirmed | Operational status not reported |
| P2-32 | §7.4, §8 | Licensing duties (BR 6.1.2, AR 8.1.2); 17 auditors, 7 firms, 50 managers; statistics@epra.go.ke | AR p.66 T8.5; BR p.44; p.2 | Confirmed | |
| P2-33 | §8.1 | Named solar owners (BE Africa C&I, GridX); REREC for mini-grids | BR p.43; AR pp.36-37, p.21 | Confirmed | |
| P2-34 | §9 | First oil 1 Dec 2026; tariff period ended 30 Jun 2026, no successor described | AR p.7; p.26 | Confirmed | |

## D. New report conflicts found in this part

| Flag | Issue | Locator | Matters for EMS question? |
|---|---|---|---|
| 25 | AR says the utility "complied" with the CAIDI target in 2021/22-2023/24, but Fig 2.20 shows CAIDI of 2.76, 2.25, 2.53 h against the 1.36 h benchmark. Earlier-year targets are not reported | AR p.23 | Medium (reliability trend and target basis, see flag 15) |
| 26 | Interconnected solar effective capacity (210.30 MW) exceeds installed (210.25 MW) | AR p.13 T2.1 | Low |

## E. Unverifiable claims in §4-§9 (all labelled by the baseline as inference or external)

| Claim | Baseline location | Status |
|---|---|---|
| Third-party solar owners probably run their own monitoring | §4.3, §5.3 | Unverifiable from the reports (INTERPRETATION) |
| Vendor tools may already serve C&I | §6.2, §7.2 | Unverifiable (H2a untestable from the reports) |
| Hourly data probably held internally by the operator | §7.1 | Unverifiable (INTERPRETATION) |
| Operator systems are likely proprietary | §7.3 | Unverifiable (INTERPRETATION) |
| Utility likely uses time-differentiated metering for ToU customers | §4.5 | Unverifiable (INTERPRETATION) |
| CF 18% for captive solar | §3 O21 | External, unverified (labelled) |
| 11.63 MWh/toe | §3 O39 | External, unverified (labelled) |
| Modbus, MQTT; OpenEMS, Emoncms | §7.3 | External, unverified (labelled); check status and licences before use |

## F. Step 3 summary

| Result | Count / items |
|---|---|
| Headline numbers changed | None. Executive-summary figures all confirmed |
| Corrections | B-13, B-19, B-20, B-22, B-23, B-34, B-43 (part 1); P2-17, P2-25 (part 2) |
| Qualified claims | B-25, B-38 (part 1); P2-21, P2-03 (part 2) |
| Open items | I-007; AR publication date; "Customers in Tariff" meaning |
