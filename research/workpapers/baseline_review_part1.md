# Step 3: baseline report review, part 1 (exec summary, §2, §3)

Status: draft. Baseline = "Does Kenya Need an EMS..." study (not evidence).
Sources: AR = Energy & Petroleum Statistics Report, year ended 30 Jun 2026.
BR = Biannual report, Jul-Dec 2025. Printed page = PDF page in both.
Verdicts: Confirmed / Corrected / Unverifiable / Conflicts between reports.
Rechecks were run by script from the report values (CALCULATION).

## A. Executive summary

| ID | Claim (baseline) | Source locator | Verdict | Note |
|---|---|---|---|---|
| B-01 | SAIDI 13.16 h/month vs 1.5 target; losses 21.38% vs 16.5% allowance | AR p.24 §2.1.13; p.22 §2.1.12 | Confirmed | 13.16 = mean of the 12 monthly values (C). AR p.24 does not say "per month"; BR p.19 does. |
| B-02 | Captive solar +72.8 MW (+24.2%), about half of national additions | AR p.13 §2.1.1, T2.1 | Confirmed | 72.8 / 146.4 = 49.7% (C) |
| B-03 | Curtailment -39.6%; ToU savings KSh 1.88 bn; curtailment rose each month Feb-Jun | AR p.18; p.28; p.19 Fig 2.10 | Confirmed | Feb-Jun: 9.1, 11.6, 28.7, 36.8, 48.6 GWh |
| B-04 | No EMS-type system named in either report | Both (I-005) | Confirmed as an absence | Data gap, not proof of absence |

## B. §2.1-2.3 inventory and key figures

| ID | Claim | Source locator | Verdict | Note |
|---|---|---|---|---|
| B-05 | Dates and bases: BR published Mar 2026; AR mixes FY and calendar 2025 | BR p.48; AR p.11, p.56, p.60 | Confirmed | AR publication date still not stated |
| B-06 | §2.2 coverage table | AR/BR as cited | Confirmed | Fig 7.2 Sankey has no numeric values (verified on page image, AR p.61) |
| B-07 | Capacity table, all rows and totals (Dec-25, Jun-26) | BR p.11 T2.1; AR p.13 T2.1 | Confirmed | Columns sum: 3,263.02 / 3,082.00 / 676.60 / 47.58 / 3,987.20 (C). New minor flag: AR solar effective 210.30 > installed 210.25 |
| B-08 | Captive solar H2 add about 46.6 MW | BR p.11; AR p.13 | Confirmed | 72.8 - 26.24 = 46.56 (C) |
| B-09 | Generation by source: FY, shares, FY24/25, y/y, H1 (BR), H2 | AR p.15, p.22, p.34-36; BR pp.12-13 | Confirmed | FY sources sum to 15,692.81; H1 to 7,807.07. Prior-year geothermal 5,718.16 (p.15) vs 5,718.15 (p.34) |
| B-10 | Imports split (Ethiopia 1,577.66 = 82.45%, Uganda 322.06, Tanzania 6.53, Moyale 7.41) | AR p.15 | Confirmed | |
| B-11 | Five-year indicator table (all rows) | AR Figs 2.1, 2.4-2.5, 2.9, 2.11, 2.14, 2.17, 2.18, 2.20, 2.22, 2.24, 4.2, 6.5, 6.9 | Confirmed | Distribution series: 2023/24 = 311,625; 2024/25 = 322,668 (AR Fig 2.14) |
| B-12 | Other anchors (10,432,707 customers; 411,710 new; 2,514.28 MW on 29 Jun; ToU; 12,444.71 GWh) | AR pp.16-17, 28 | Confirmed | Categories sum to 12,444.72 |
| B-13 | §2.4 "H1 + H2 reproduces FY by source" | n/a | Corrected | Circular as worded: H2 is FY minus H1. The independent check passes: summed AR monthly Jan-Jun equals derived H2 (geothermal 3,292.75; thermal 602.52; imports 974.43; hydro 1,808.61 vs 1,808.63) |
| B-14 | §2.4 monthly source sums match monthly totals (4 spot checks, within 0.02) | AR Figs 2.2, 3.2-3.8, 4.1, 4.3, 2.16 | Confirmed | All 12 months within 0.06 GWh (AR totals are 1 dp) |
| B-15 | §2.4 SAIDI = SAIFI x CAIDI within 0.02 h in all 12 months | AR Figs 2.19, 2.21, 2.23 | Confirmed | Max difference 0.02 |
| B-16 | §2.4 ToU monthly sums = annual | AR T2.6 | Confirmed | 1,878.30 KSh m; 267.57 GWh |
| B-17 | §2.4 regions sum to total except Coast share | AR p.18 | Confirmed | Coast 2,087.62 / 12,444.71 = 16.78% vs 17.74% printed |

## C. §2.5 flags (24)

| Flag | Verdict | Note |
|---|---|---|
| 1 loss rate not reproducible | Confirmed | AR 20.23%; BR 23.48% (C). BR denominator is "energy purchased" (7,760.66) |
| 2 H2 sales vs generation | Confirmed | Implied H2 sales 6,506.57 (+9.57% on H1); generation +1.01% |
| 3 customer baseline | Confirmed | 13,760 difference |
| 4 distribution growth | Confirmed | +3.56% (322,668 base) vs +7.23% printed |
| 5 thermal / imports text vs chapter | Confirmed, plus new detail | AR p.39 also gives monthly imports 106.01-146.02 GWh, but Fig 4.1 shows 142.36-172.33 |
| 6 renewable share definitions | Confirmed | 81.13 / 79.46 / 91.65 (AR); 78.79 (BR). 81.13% not reproducible |
| 7 effective geothermal unchanged | Confirmed | 876.10 MW at Dec-25 and Jun-26 |
| 8 import attribution | Confirmed | FY24/25 "Ethiopia" 1,534 = total imports |
| 9 BR T2.5 components exceed totals; 33 kV Sep-25 | Confirmed | Excess 0.16, 0.20, 0.09, 0.07, 0.11, 0.14; Fig 2.18 sums to 100.51%. The 20.31 anomaly is INTERPRETATION |
| 10 pump prices differ between reports | Corrected | Wider than "Oct-Dec": see B-20 |
| 11 LPG basis and reconciliation | Confirmed | FY monthly sum 500.13 kt; FY24/25 443,933 t; +12.66%. H2 imports 391.7 kt vs H2 demand 248.7 kt |
| 12 pipeline monthly sum | Confirmed | 9,511.54k vs 9,411,290 m3 |
| 13 final consumption > supply | Confirmed | +655.49 ktoe (2025); +554.19 (2024) |
| 14 curtailment text / units | Confirmed | |
| 15 reliability text errors | Confirmed | Lowest SAIFI is July (2.82); June is 4.11. FY24/25 SAIDI 9.24 (text) vs 9.42 (Fig 2.22) |
| 16 renewable target year | Confirmed | 2030 (AR p.33) vs 2035 (AR p.31, BR p.25) |
| 17 peripheral mismatches | Confirmed, with specifics | See B-21 |
| 18 ToU Dec-25 savings per kWh | Confirmed | 4.53 vs 7.2-8.0 |
| 19 Line 5 flow rate | Confirmed | 1,200 m3/h implied; printed 1,300 |
| 20 local imports below demand | Confirmed | 784,128 m3 (12.39%). Caveat: compares G2G local volume only |
| 21 licence counts | Confirmed | BR lists 24 for H1; AR lists 20 for the year (11 generation, 8 distribution/retail supply, 1 import/export) |
| 22 street lighting H2/H1 | Corrected | See B-19 |
| 23 loss gap in FY24/25 | Confirmed | 21.23% computed vs 23.36% |
| 24 captive solar share denominators | Confirmed | 104.82 MW gap = 21.30 + 83.50 (within 0.02) |

## D. §3 observations (O1-O42)

| ID | Baseline obs. | Verdict | Note |
|---|---|---|---|
| B-18 | O1-O7 | Confirmed | Growth 8.44% vs real GDP 4.6% is 1.83x (FY generation vs calendar GDP). Load factor 71.25% (C; baseline 71.2%). Margins 29.8% and 22.6% (interconnected capacity incl. 200 MW import line). Firm margin: 2,446.2 MW = 97.3% of peak |
| B-19 | Flag 22 / O-street lighting: H2 about 2.4x H1 "in FY24/25 and FY25/26" | **Corrected** | FY24/25: (150.43-44.48)/44.48 = 2.38x. FY25/26: (173.17-66.41)/66.41 = 1.61x, not 2.4x. A billing or classification change is still possible, but the FY25/26 anomaly is smaller |
| B-20 | Flag 10: pump prices differ "Oct-Dec 2025" | **Corrected** | BR Fig 5.10 vs AR Fig 6.13: IK differs in all six months (e.g. Jul 156.58 vs 156.14). AGO differs in five (Aug 173.95 vs 171.58; Oct 172.10 vs 171.47; Nov 178.05 vs 171.47). PMS differs Aug (0.01), Oct (184.60 vs 184.52), Nov (181.30 vs 184.52), Dec (180.67 vs 184.52) |
| B-21 | Flag 17 detail | Confirmed with specifics | BR T6.8 tanker total 161 vs monthly sum 336, and AR FY 833. AR text 684 contractor licences vs Table 8.4 total 648. AR FY fuel tests 10,354 < BR H1 10,598. AR T8.5 T2 = 35 < BR H1 T2 = 110. AR T8.5 V2 = T3 = 248 (possible duplicate). D-053 confirmed as printed (not an extraction error) |
| B-22 | O8: "Of +1,220.6 GWh ... together 88.7%" | **Corrected** | Growth is +1,220.81 (AR p.14 states 1,220.82). Geothermal 57.5% and imports 31.1% stand. Together 88.6% |
| B-23 | O9: geothermal CF "77.7-83.7%" | **Corrected** | Range omits 72.6% on AR's own 1,009.98 MW installed. The three values are 72.6 / 77.7 / 83.7 (denominator choice; Menengai commissioning dates not reported). Hydro 48.3, wind 50.6, solar 25.6, thermal 26.4, Ethiopia 90.0 confirmed |
| B-24 | O10-O11 | Confirmed | Thermal H1 +24.3%, H2 -11.3%; Apr-Jun are the three lowest months. Curtailment 2.57% of generation; geothermal 5.76% of potential; H1 -266.35; H2 156.99 -> 158.59 |
| B-25 | O12: Menengai 136.47 GWh; "at least 301 GWh (43%) unaccounted" | Confirmed (arithmetic), qualified | 702.36 - 264.76 - 136.47 = 301.13. The 136.47 sums AR T2.8 rows labelled "ORPOWER 22 (KAISHAN)" 116.34 and "GLOBELEQ MENENGAI" 20.13; mapping to the AR text plants is INTERPRETATION and commissioning dates are not reported. Curtailment reduction includes wind |
| B-26 | O13 | Confirmed | 30.8% of thermal; 21.1% of imports (scale only) |
| B-27 | O14-O15 | Confirmed | Imports 5.67x; y/y +90.8, +86.3, +27.8, +24.8%; monthly range -10.7% / +8.1% of mean. FY factor: AR reports 0.053 and no prior-year factor. 0.0547 -> 0.0534 uses the AR T2.8 total as denominator (C) |
| B-28 | O16 | Confirmed | 3,156.31 GWh = 1.65x imports. Above allowance 581.9-761.3 GWh; KSh 5.8-14.1 bn (illustrative) |
| B-29 | O17 | Confirmed | 8.8x, 2.4x, 3.6x targets. SAIDI H1 8.39 -> H2 17.93 |
| B-30 | O18-O19 | Confirmed | Transmission +276 km (+2.81%); distribution +11,489 km (+3.56%). The Sondu-Ndhiwa attribution is AR's own (p.18); commissioning date not reported |
| B-31 | O20-O22 | Confirmed | 49.7%; captive solar 1.78x utility. Illustrative output 589-837 GWh (3.8-5.3%) rests on an external, unverified 18% CF. BR T6.3: 19 of 24 solar-only, 9 BE Africa C&I |
| B-32 | O23 | Confirmed as an absence | |
| B-33 | O24 | Confirmed, basis noted | Average load 10.48 MW = 22.7% of 46.24 MW (22.0% of 47.58 MW): off-grid capacity basis conflicts (D-006/D-007). Top 3 = 58.84% |
| B-34 | O25 | Confirmed; locator corrected | 12.25 GWh, about 1.4 MW; customers 115 -> 543. Baseline source "Ch8 message" is wrong: the e-mobility cap removal is in the Director ER&P message, AR p.8; customer counts are AR p.17 |
| B-35 | O26-O28 | Confirmed | Sales +9.84% (+1,114.95 GWh); domestic 61.6% of growth, C&I 26.8%; 99.4 kWh per customer-month; per customer +5.5% |
| B-36 | O29-O30 | Confirmed | Pass-through 4.37 (Jun-26) to 5.68 (Oct-25) = +30%. FERFA 2.62x; FX range 129.20-129.89 (0.5%) |
| B-37 | O31-O32 | Confirmed; one item open | 267.6 GWh = 2.15% of sales; KSh 1,878.3 m (+30.6%); 2,614 average beneficiaries = sum of AR T2.7 FY25/26 column; KSh 0.718 m each. "Eligible customer count not reported": AR T2.7 has a separate "Customers in Tariff" column (e.g. SC3 1,393; EM 30; CI-1 805) that the baseline does not mention. Its meaning is undefined and it is below beneficiaries for EM, CI-1, CI-2, CI-4 (I-007 stays open) |
| B-38 | O33 "no sustained fall after the price spike" | Qualified | Monthly demand Apr, May, Jun is -3.9%, -4.8%, -3.1% vs March (541.13k m3) (C). No monthly prior-year series, so no demand response can be shown or excluded. Annual +8.41% confirmed |
| B-39 | O34-O36 | Confirmed | Murban +75.6%; AGO +39.8%, PMS +20.2%, IK +25.3% (Mar->May). Middle East 74.79%, Europe 10.79% of G2G. Storage 37.9 days of imports (capacity, not stocks) |
| B-40 | O37 | Confirmed | 94.2% (9,411,290 / 9,986,400); 87.0% on printed flow. Total throughput vs Line 5 only: rough |
| B-41 | O38 | Confirmed, basis noted | "About 34 days" = receiving 37,335 t + hinterland 6,994 t over calendar-2025 demand. Receiving only = 28.6 days; with FY demand 500.1 kt = 32.4 days |
| B-42 | O39-O42 | Confirmed | Electricity about 5.1% of final energy uses an external, unverified 11.63 MWh/toe and mixes FY sales (12,444.71 GWh) with calendar-2025 final consumption. Audits: 0.53% / 1.11%. 230 of 239 refrigerator models <= 3 stars. Disputes 1.79 per 100,000 customers; billing + disconnection 65.2%. Accidents -8.51% |
| B-43 | Locators "AR T3", "AR T2" in §3 | Corrected | These point to the baseline's own tables, not AR tables (the AR has no Table 3 and its Table 2.x numbering differs). Replace with AR sections, figures and page numbers |

## E. Open knowledge-base items

| Item | Result |
|---|---|
| I-007 "Customers in Tariff" | Read on page image (AR p.29): separate column, meaning undefined. Do not treat as an eligible-customer count. Remains open |
| D-053 solar technician rows | Confirmed as printed (AR p.66). The conflict with BR T6.5 is real |
| Fig 7.2 Sankey | No numeric values on the page (AR p.61). Remains a data gap |
| Page offset | Zero offset (BR 48 pp.; AR 74 pp.) |

## F. §4-§9 numerics spot-checked (not yet reviewed as judgments)

Confirmed by script: reserve margins; interconnected capacity +71.02 MW vs
peak +198.06 MW (margin narrowed about 127 MW); Ethiopia link = 7.95% of
peak; outlook peak +7.4% and generation +8.3%; pass-through KSh bn
(FEC 41.6, FERFA 14.9, inflation 5.6, WRA 0.17); thermal-implied factor.
Unreviewed in this step: relevance scores, hypotheses, verdict, EMS
recommendation, deliverables.
