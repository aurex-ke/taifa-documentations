# Assessing Kenya’s Need for an Energy Management System

*Prepared November 2026.*

**Sources:** EPRA Energy & Petroleum Statistics Report for the year ended 30 June 2026 `(AR)` and EPRA Biannual Energy & Petroleum Statistics Report, July–December 2025 `(BR)`.

**Labels:** `D = reported`, `C = my calculation`, `I = my interpretation`. `H1 = Jul–Dec 2025`. `H2 = Jan–Jun 2026 (AR minus BR)`.

## 1. Executive summary

**Question.** Based on two EPRA reports (annual FY2025/26 and biannual Jul–Dec 2025), is there a real, evidence-backed need for an Energy Management System (EMS) in Kenya, and at what level and in what form?

**Verdict: need partially confirmed, at a narrow level. Confidence: low.**

**Key reasons**

- Large problems are measured but mostly not shown to be EMS problems. SAIDI was 13.16 h/month against a 1.5 h target, and losses were 21.38% against a 16.5% allowance. The reported loss causes are physical and commercial, and the reliability cause is unreported.
- A fast-growing part of supply is invisible. Captive solar grew 72.8 MW (+24.2%), about half of national capacity additions, with no output or export data.
- Curtailment fell 39.6% and Time-of-Use (ToU) savings reached KSh 1.88 bn with no EMS reported, yet curtailment rose every month from February to June.
- No item scores High, none can be sized in money or hours, and the reports cannot show which systems already exist.
- Petroleum, LPG, pass-through costs, households and e-mobility show no evidenced EMS need.

**Where to start.** Validate first with data requests and a scan of existing tools, then run a read-only monitoring pilot at commercial and industrial (C&I) sites. Stopping after validation is a legitimate outcome.

## 2. Data inventory and limitations

### 2.1 Sources and conventions

The AR covers the year ended 30 June 2026. The BR covers July–December 2025 and was published in March 2026. Both are statistical summaries by EPRA. The AR mixes bases: most series are financial year (Jul–Jun), but LPG consumption, the energy balance and GDP are calendar 2025.

### 2.2 What the reports cover

| Domain | What exists | Resolution | Source |
| --- | --- | --- | --- |
| Capacity | By technology: interconnected, effective, captive, off-grid | Point in time (Dec-25, Jun-26) | AR T2.1, BR T2.1 |
| Generation and mix | By source | Monthly, annual, 5-year | AR 2.1.2–2.1.3, Ch3–4; BR 2.1.2, Ch3 |
| Peak demand | Monthly and annual peak MW | No load curves | AR 2.1.4 |
| Curtailment | Geothermal vs wind | Monthly, 5-year | AR 2.1.8; BR 2.1.7 |
| Consumption | By customer category and KPLC region | FY and H1 | AR 2.1.6–2.1.7; BR 2.1.5–2.1.6 |
| Networks | Line km by voltage, commissioned projects | Annual | AR 2.1.9–2.1.10 |
| Mini-grids | Generation per site (BR), capacity split (AR) | Monthly | BR 2.1.8; AR 2.1.11 |
| Losses and reliability | National only | Monthly, 5-year | AR 2.1.12–2.1.13; BR 2.1.10–2.1.11 |
| Tariffs | Base, pass-through, retail, ToU | Monthly | AR 2.2; BR 2.2 |
| Market structure | Share by producer, HHI | Annual | AR 2.2.6–2.2.7 |
| Emissions | Grid emission factor | Half-year, annual | AR 2.3; BR 2.4 |
| Petroleum and LPG | Imports, demand, throughput, prices, storage, OMCs | Monthly, 5-year | AR Ch6; BR Ch5 |
| Energy balance | Supply, production, final consumption | 2025 aggregate; Sankey chart has no numbers | AR Ch7 |
| Efficiency and consumer protection | Audits, appliance registrations, licences, disputes, accidents | Annual and H1 | AR Ch5, Ch8; BR Ch4, Ch6 |

### 2.3 Key figures (all D unless marked)

**Installed capacity (MW)**

| Technology | Dec-25 total (BR) | Jun-26 total (AR) | Jun-26 interconnected (installed / effective) | Captive | Off-grid |
| --- | --- | --- | --- | --- | --- |
| Geothermal | 943.7 | 1,013.68 | 1,009.98 / 876.10 | 3.70 | – |
| Hydro | 872.5 | 872.57 | 839.47 / 809.68 | 33.00 | 0.10 |
| Thermal | 628.1 | 630.15 | 565.82 / 558.42 | 21.30 | 43.03 |
| Solar | 540.9 | 587.45 | 210.25 / 210.30 | 373.30 | 3.90 |
| Wind | 436.1 | 436.05 | 435.50 / 425.50 | – | 0.55 |
| Bioenergy | 163.8 | 163.80 | 2.00 / 2.00 | 161.80 | – |
| Waste heat recovery | 83.5 | 83.50 | – | 83.50 | – |
| Imports (Ethiopia HVDC) | 200.0 | 200.00 | 200 / 200 | – | – |
| **Total** | **3,868.6** | **3,987.20** | **3,263.02 / 3,082.00** | **676.60** | **47.58** |

Captive solar rose from 300.5 to 373.3 MW (+72.8 MW). The BR reports 26.24 MW added in H1, so H2 added about 46.6 MW (C).

**Generation by source (GWh)**

| Source | FY25/26 | Share | FY24/25 | y/y | H1 (BR) | H2 (C) |
| --- | --- | --- | --- | --- | --- | --- |
| Geothermal | 6,420.51 | 40.91% | 5,718.15 | +12.28% | 3,127.76 | 3,292.75 |
| Hydro | 3,554.31 | 22.65% | 3,503.47 | +1.45% | 1,745.68 | 1,808.63 |
| Wind | 1,931.72 | 12.31% | 1,907.57 | +1.27% | 1,013.43 | 918.29 |
| Imports | 1,913.66 | 12.19% | 1,533.85 | +24.76% (C) | 939.23 | 974.43 |
| Thermal (interconnected) | 1,309.42 | 8.34% | 1,247.93 | +4.93% (C) | 706.9 | 602.52 |
| Utility solar | 471.40 | 3.00% | 473.32 | −0.40% | 227.67 | 243.73 |
| Off-grid | 91.79 | 0.58% | 87.96 | +4.36% | 46.40 | 45.39 |
| **Total** | **15,692.81** |  | **14,472.00** | **+8.44%** | **7,807.07** | **7,885.74** |

Imports in FY25/26: Ethiopia 1,577.66 GWh (82.45%), Uganda 322.06, Tanzania 6.53, Moyale 7.41.

**Five-year system indicators (AR)**

| Indicator | 21/22 | 22/23 | 23/24 | 24/25 | 25/26 |
| --- | --- | --- | --- | --- | --- |
| Generation (GWh) | 12,652.74 | 13,289.75 | 13,684.36 | 14,472.00 | 15,692.81 |
| Peak demand (MW) | 2,057 | 2,149 | 2,177 | 2,316 | 2,514 |
| Curtailment (GWh) | 285.51 | 495.43 | 812.8 | 668.7 | 403.94 |
| System losses | 22.84% | 23.40% | 23.21% | 23.36% | 21.38% |
| Loss allowance (EPRA) | 19.5% | 19.5% | 18.5% | 17.5% | 16.5% |
| CAIDI (h) | 2.76 | 2.25 | 2.53 | 2.57 | 3.23 |
| SAIDI (h) | 8.71 | 8.37 | 10.14 | 9.42 | 13.16 |
| SAIFI | 3.18 | 3.74 | 3.96 | 3.67 | 3.91 |
| Imports (GWh) | 337.50 | 644.07 | 1,199.80 | 1,533.85 | 1,913.66 |
| Transmission (km) | 7,433 | 8,885 | 9,585 | 9,824 | 10,100 |
| Distribution (km) | 282,260 | 302,256 | 311,625 | 322,668 | 334,157 |
| Off-grid generation (GWh) | 71.08 | 74.67 | 85.02 | 87.96 | 91.79 |
| Petroleum imports (m³) | 8,592,196 | 9,243,089 | 9,059,597 | 9,756,761 | 10,880,927 |
| Domestic petroleum demand (m³) | 5,738,654 | 5,577,691 | 5,460,437 | 5,839,465 | 6,330,508 |

Other anchors: cumulative customers 10,432,707 and new connections 411,710 (AR 2.1.5); peak 2,514.28 MW on 29 June 2026; ToU savings KSh 1,878 m on 267.6 GWh (AR 2.2.5); consumption 12,444.71 GWh, of which large C&I 47.57%, domestic 34.77%, small commercial 16.17% (AR T2.2).

### 2.4 Tie-out checks (C)

- Monthly generation by source sums to monthly totals (spot-checked Jul, Sep, Jan, Jun) to within 0.02 GWh.
- H1 plus H2 reproduces FY totals, by source.
- Monthly ToU savings and sales reproduce the annual totals (KSh 1,878.3 m; 267.6 GWh).
- Monthly SAIDI, SAIFI and CAIDI reproduce the annual means, and SAIDI = SAIFI × CAIDI within 0.02 h in all 12 months.
- Category and region consumption sums to the totals, except the Coast share printed in the AR.

### 2.5 Inconsistencies and flags

| # | Issue | Matters for the EMS question? |
| --- | --- | --- |
| 1 | Loss rates can't be reproduced from reported volumes. AR reports 21.38% but 1 − 12,444.71/15,601.02 = 20.2% (C). BR reports 22.07% but 1 − 5,938.14/7,760.66 = 23.5% (C). Basis unexplained. | High |
| 2 | H1 and H2 consumption don't line up. Implied H2 sales are 6,506.6 GWh (+9.6% on H1) while generation rose 1.0% (C). Implied H2 domestic growth is +24% y/y against +13% in H1. | High |
| 3 | Customer baseline differs by about 13,760 between the AR and BR (C). | Medium |
| 4 | AR compares distribution length (334,157 km) with a 2023/24 figure (311,625 km). Against 322,668 km, growth is +3.56%, not +7.23% (C). | Low–Medium |
| 5 | Thermal is 1,309.42 GWh in Ch2 and 1,399.54 in Ch4 (the latter includes off-grid thermal). Imports are 1,913.66 in Ch2 but 1,931.72 in Ch4 text. | Medium |
| 6 | Renewable share has several definitions: 81.13% (Foreword, not reproducible), 79.46% and 91.65% (Ch3, the latter counting imports as renewable), 78.79% (BR). Capacity shares exclude 200 MW imports from the denominator. | Medium |
| 7 | Effective geothermal capacity (876.10 MW) is unchanged although installed rose about 70 MW. | Medium |
| 8 | Import attribution is inconsistent: FY24/25 'Ethiopia' equals total imports, and the BR net export to Tanzania (136.55 GWh) sits against 6.53 GWh of Tanzanian imports in the AR. | Low–Medium |
| 9 | In BR T2.5, base + pass-through + taxes exceeds the total by 0.07–0.20 KSh/kWh each month. Fig 2.18 shares sum to 100.51% (C). C&I 33 kV Sep-25 (20.31) looks like a typo. | Medium |
| 10 | Oct–Dec 2025 pump prices differ between the reports. | Medium (petroleum) |
| 11 | LPG headline 475,943 t is calendar 2025, not FY. FY25/26 from monthly data is about 500.1 kt (+12.7%) (C). LPG imports and demand don't reconcile for Jan–Jun 2026. | Medium |
| 12 | Pipeline monthly values sum to about 9.51 m m³ against an annual 9,411,290. | Low |
| 13 | Final consumption exceeds total energy supply in both 2025 and 2024 in the energy balance. | Medium |
| 14 | Curtailment text and units are inconsistent (BR says 245.35 GWh geothermal, but 234.07 is geothermal and 11.28 wind). AR charts label GWh as MWh. | Low |
| 15 | Reliability text has errors (lowest SAIFI attributed to June but it is July; FY24/25 SAIDI 9.24 in text vs 9.42 in chart). Index basis (planned outages, major events) is not stated. | Medium |
| 16 | Renewable target year is 2030 in one place and 2035 in others. | Low–Medium |
| 17 | Peripheral count mismatches (fuel tests, solar technician licences, LPG tanker inspections, contractor licences, FX range). | Low |
| 18 | ToU Dec-25 savings per kWh (4.53) is an outlier against 7.2–8.0 in all other months. | Medium |
| 19 | Pipeline Line 5: printed flow rate 1,300 m³/h, but the annual maximum implies 1,200. | Low |
| 20 | Declared local imports are 12–14% below domestic demand. | Medium |
| 21 | BR lists 24 generation and retail licences for H1 alone; the AR lists 20 for the full year. | Low |
| 22 | Street lighting: implied H2 consumption is about 2.4× H1 in FY24/25 and FY25/26, suggesting a billing or classification change. | Low–Medium |
| 23 | The loss gap (reported minus computed) also appears in FY24/25: 23.36% reported vs 21.2% computed. | High |
| 24 | Captive solar share is 55.17% of total captive capacity in Ch2 but 65.28% of renewable captive capacity in Ch3. The 104.82 MW gap equals captive thermal (21.30) plus waste heat recovery (83.50) to within 0.02 MW (C). | Low |

### 2.6 What is missing from both reports

- **Load shape:** no hourly or daily load curves, minimum demand or load factor by period.
- **Network detail:** no feeder or transformer loading, outage causes, planned vs unplanned split, or SAIDI by region.
- **Metering and control:** no mention of EMS, SCADA, DMS, electricity AMI, demand response, virtual power plants or load forecasting. The only 'smart meter' reference is an LPG licence category. This is a finding from my reading of two statistical reports, not proof such systems are absent.
- **Embedded generation:** captive energy output, site counts, grid export, net metering and storage capacity. The one PPA listing a battery quotes 7,500 MWh, probably a unit error.
- **EVs:** no vehicle or charger counts, only 543 e-mobility tariff customers.
- **Mini-grids:** no diesel use or unit cost; private mini-grids unquantified.
- **Costs and money:** no PPA prices, generation costs, cost of curtailment or losses, or utility financials.
- **Sectors and geography:** no public-building or institutional consumption, no county data, no household access or affordability.
- **Efficiency:** no count of designated facilities (the denominator for the 156 audits) and no implementation rate for audit recommendations.
- **Methods:** loss calculation, emission factor and reliability index bases are not documented.
- **Time:** nothing after 30 June 2026.

### 2.7 What this data can and cannot show

It can show national and regional trends, the supply mix and its monthly variability, curtailment, service-quality trajectory, tariff structure and where demand is growing fastest. It cannot show within-day behaviour, where on the network losses and outages occur, who the potential EMS users are, what their energy costs are, or whether any EMS-type capability is already deployed. Findings about specific user levels therefore rest on inference.

## 3. Key observations

Observations are reported as patterns, not yet as problems. Capacity factors (CF) use GWh ÷ (MW × 8.76). Items marked (flag n) rest on a flag in section 2.5.

### 3.1 Demand, peak load and capacity

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 1 | Energy and peak grew at similar rates. Electricity growth ran about 1.8× real GDP growth (mixed periods). | AR T3, Ch1 | D+C | Generation +8.44% (+1,220.8 GWh); peak +8.55% (+198 MW). Four-year: generation +24.0%, peak +22.2%. GDP +4.6%. |
| 2 | System load factor has been flat for five years. | AR T3 | C | 70.2%, 70.6%, 71.8%, 71.3%, 71.2% |
| 3 | The annual peak was a one-month spike, cause not reported. | AR 2.1.4 | D+C | Jun 2,514 MW vs May 2,433 (+81) and Jan 2,444 |
| 4 | Night demand grew faster than peak. | BR 2.1.3, 2.1.7 | D+C | Night 1,152 → ≥1,400 MW (≥+21.5%); Dec peak +6.6% |
| 5 | Daily generation run-rate rose through the year. | AR 2.1.2 | C | Aug 41.84 → Feb 44.51 GWh/day (+6.4%) |
| 6 | The reserve margin at peak depends on what counts as firm (solar is nil at the 1900–2100 peak). | AR T2.1, 2.1.4 | C+I | Installed margin 29.8%, effective 22.6%. Effective excluding wind and solar: 2,446.2 MW = 97.3% of peak; 102.6% if stale geothermal effective figure is updated (flag 7) |
| 7 | The outlook points to continued growth. | AR Ch9 | D+C | Peak \~2,700 MW (+7.4%), generation >17,000 GWh (+8.3%), capacity >4,000 MW |

### 3.2 Supply mix, variability and curtailment

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 8 | Supply growth came mostly from geothermal and imports. | AR 2.1.3, T2 | C | Of +1,220.6 GWh: geothermal +702.4 (57.5%), imports +379.8 (31.1%); together 88.7% |
| 9 | Capacity factors differ widely; wind and hydro vary month to month. | AR T2.1, Ch3–4 | C | Geothermal 77.7–83.7%; hydro 48.3%; wind 50.6%; solar 25.6%; thermal 26.4%; Ethiopia link 90.0%. Monthly hydro 247.5–350.4 GWh |
| 10 | Thermal is 17.3% of interconnected capacity but 8.34% of energy; dispatch swung between halves. | AR 4.2, BR 2.1.2 | D+C | H1 +24.3% y/y; H2 −11.3%; Apr–Jun were the three lowest months |
| 11 | Curtailment fell 39.6%, all of it in H1. It rose every month from February to June. | AR 2.1.8, BR 2.1.7 | D+C | FY 403.94 GWh (2.6% of generation) vs 668.70. H1 −266.4 GWh; H2 flat (157.0 → 158.6). Feb 9.1 → Jun 48.6 GWh. Geothermal curtailed 392.36 GWh = 5.8% of its potential |
| 12 | Lower curtailment and the new Menengai plants explain at most about 57% of geothermal growth. | BR Fig 3.3, AR 3.2.1, T2.8 | C+I | Curtailment reduction ≤264.8 GWh (≤37.7% of +702.4); Kaishan and Globeleq output 136.47 GWh (≈19%); at least 301 GWh (43%) is not accounted for in either report |
| 13 | Night surplus and evening shortfall are separated in time; the reports can't test whether they overlap. | BR 2.1.7, AR 2.1.4, 4.2 | D+I | For scale only: curtailed energy = 31% of thermal and 21% of imports |

### 3.3 Imports and emissions

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 14 | Imports rose 5.7× in four years, with growth slowing. Nearly flat month to month; one link dominates. Next Ethiopia phase is 400 MW. Contract terms are not reported. | AR T3, 2.1.3, 4.1, Ch9 | D+C | 337.5 → 1,913.66 GWh; share 2.68% → 12.19%; y/y +91%, +86%, +28%, +25%; Ethiopia = 82.45% of imports |
| 15 | Emissions track thermal dispatch. | AR 2.3, BR 2.4 | D+C | FY emissions +6.0%, FY factor −2.3% (0.0547 → 0.0534 t/MWh). H1 factor 0.0579 (+17.6%), H2 implied 0.0490 |

### 3.4 Losses and reliability

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 16 | Losses were flat for four years while the allowance tightened, then fell. No breakdown by network level. Reported rate can't be reproduced (flag 1). | AR 2.1.12, BR 2.1.10 | D+C | Reported 21.38% vs 16.5% allowance (4.9 pp gap). Computed 20.2%. Energy above allowance 582–761 GWh |
| 17 | All three reliability indices are far from targets and worsened in H2. Causes not reported. | AR 2.1.13, BR 2.1.11 | D+C | SAIDI 13.16 h (8.8× target), CAIDI 3.23 h (2.4×), SAIFI 3.91 (3.6×). H1 → H2 SAIDI 8.39 → 17.93 h. May SAIDI 27.33 h. Five-year worst for SAIDI and CAIDI |
| 18 | The network and customer base grew in the same year. | AR 2.1.5, 2.1.9–2.1.10 | D+C | Transmission +276 km (+2.81%); distribution +11,489 km (+3.56%); new connections 411,710 (+4.1%) |
| 19 | Demand rose fastest in a region where the network was recently strengthened. | AR 2.1.7 | D+I | South Nyanza +17.93% after the Sondu–Ndhiwa line |

### 3.5 Distributed generation, mini-grids, storage and e-mobility

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 20 | Captive capacity is growing faster than the grid; captive solar was half of national additions. | AR 2.1.1, T2.1 | D+C | Captive 676.6 MW (16.97% of total), +72.8 MW (+12.05%), all solar (+24.2%); 49.7% of national additions (72.8/146.4) |
| 21 | Captive solar is 1.8× utility solar; its output, sites and exports are unreported. Estimate is illustrative only. | AR T2.1 | C+I | 373.3 vs 210.25 MW. At CF 18% (external, unverified) to 25.6%: about 0.6–0.8 TWh/yr, 3.8–5.3% of grid generation |
| 22 | Licensing and PPA pattern looks like third-party on-site solar for C&I users, in small sites. | BR T6.3, 2.2.1, AR 3.2.4 | D+I | 19 of 24 BR licences solar-only, 0.04–4 MW; 9 held by BE Africa C&I |
| 23 | Storage and net metering are absent from every table. | AR T2.1, 3.2.4 | D (absence) | n/a |
| 24 | Off-grid generation is small, thermal-dominated and growing slowly. Customers pay grid tariffs. Fuel use and unit cost not reported. | AR 2.1.11, BR 2.1.8 | D+C | 91.79 GWh (0.58%), +4.36%; 46.24 MW, 93.05% thermal; average load 10.5 MW = 22.7% of capacity; Mandera + Lodwar + Wajir = 58.8% |
| 25 | E-mobility is growing fast from a very small base. No vehicle or charger counts. | AR 2.1.6, Ch8 message | D+C | 12.25 GWh (0.10% of sales; ≈1.4 MW average load), +143%; customers 115 → 543 |

### 3.6 Consumption patterns

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 26 | Domestic is the largest source of sales growth; implied H2 growth is much higher than H1 (flag 2). | AR 2.1.6, BR 2.1.6 | D+C | Sales +9.84% (+1,114.95 GWh). Domestic +686.75 GWh (61.6% of growth), +18.87%. Large C&I +299.35 GWh (26.8%), +5.33% |
| 27 | Per-customer sales are rising; the average customer is small. | AR 2.1.5–2.1.6 | C | About 99 kWh per customer-month; per customer ≈ +5.5% |
| 28 | All regions grew, with a wide spread; data is by KPLC region only. | AR 2.1.7, BR 2.1.5 | D+C | Nairobi 43.92% share; Coast +3.86% (slowest); South Nyanza +17.93% (fastest) |

### 3.7 Tariffs, pass-through costs and Time-of-Use

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 29 | Base energy tariffs were lower in Dec-25 than Jun-25 for most bands. The tariff control period ended 30 Jun 2026; no successor is described. | BR T2.3, T2.5, AR T2.5 | D+C | DC >100 kWh 19.08 → 18.57 (−2.7%). Pass-through 4.37–5.68 KSh/kWh (30% swing) |
| 30 | FERFA swung 2.6× while the exchange rate moved 0.5%. FEC stayed low in May–Jun while crude rose 75.6%. No lag mechanism is described. | AR T2.5, 1.1, 6.3 | D+C | FERFA 0.6809–1.7853; FX 129.20–129.89; FEC 3.06 and 3.14 in May–Jun |
| 31 | ToU is the only demand-side programme with outcome data. Eligible customer count not reported. | AR 2.2.5, T2.6–2.7 | D+C | 267.6 GWh at off-peak rate (2.15% of sales); savings KSh 1,878.3 m (+30.6%); about 2,614 average beneficiaries ≈ KSh 0.72 m each |
| 32 | ToU monthly data has two unexplained anomalies. | AR T2.6 | C | Dec savings per kWh 4.53 vs 7.2–8.0 elsewhere. Feb volume −70% vs Jan (shorter month explains ≈10%) |

### 3.8 Petroleum and LPG

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 33 | Petroleum volumes are growing; no sustained fall after the price spike. | AR 6.2 | D+C | Imports +11.52% (10.88 m m³); domestic +8.41% (6.33 m m³); pipeline +6.84% |
| 34 | Pump prices rose sharply in Apr–May 2026. AGO went above PMS in May–Jun. | AR 6.3 | D+C | Murban $63.06 (Feb) → $110.75 (May), +75.6%. Mar → May: AGO +39.8%, PMS +20.2%, IK +25.3% |
| 35 | Supply is concentrated by origin and port. Stocks not reported. | AR 6.2.1, 6.3 | D+C | 74.8% of G2G imports from the Middle East; 100% via Mombasa; storage 1.13 m m³ ≈ 38 days of imports (capacity, not stocks) |
| 36 | Declared local import volumes are below domestic demand. | AR 6.2.1, 6.2.2 | C | FY gap 784,128 m³ (12.4%) |
| 37 | Pipeline utilisation is high on a rough basis. | AR T6.3, 6.2.2 | C+I | 94.2% of Line 5 annual maximum (87% if printed flow rate is right; flag 19) |
| 38 | LPG demand is growing, with infrastructure expansion planned. | AR 6.4, Ch9 | D+C | 475,943 t (calendar 2025, +14.72%); 8.9 kg per capita; receiving and storage ≈ 34 days of demand; +≈60,000 t planned |

### 3.9 Final energy, efficiency, consumer protection and policy

| # | Observation | Source | Type | Magnitude |
| --- | --- | --- | --- | --- |
| 39 | Electricity is a minority of final energy; biomass underpins household use. | AR Ch1, Ch7 | D+C | Electricity ≈5.1% of 21,002.71 ktoe (uses 11.63 MWh/toe, external, unverified); biomass ≈95% of indigenous production |
| 40 | Audits identified savings; implementation and the number of designated facilities are not reported. Registered appliances cluster at low star ratings. | AR Ch5, 8.1 | D+C | 156 audits → 65.53 GWh/yr (0.53% of sales; ≈1.1% of large C&I). 230 of 239 refrigerator models ≤3 stars |
| 41 | Disputes concentrate on billing and disconnection. Electrical accidents are down 8.5%, causes unreported. | AR 8.4–8.5 | D+C | 187 disputes, 88.2% involve KPLC; billing + disconnection 65.2%. 129 electrical accidents, 82 fatalities |
| 42 | A regulatory pipeline is creating data, metering and audit obligations. | AR Ch5, Ch9 | D+I | Energy Management Regulations 2025 (facilities ≥180 MWh/yr); Open Access Regulations 2026 (wheeling, metering, energy accounting); e-mobility regulations in development |

**Checked, no notable EMS-relevant pattern:** annual hydro (+1.45%), wind (+1.27%) and utility solar (−0.40%); electricity HHI (0.421 → 0.357, above the 0.1 benchmark); petroleum HHI 0.0891; fuel quality compliance 99.36% of 4,199 sites.

## 4. Problems and opportunities, with EMS-relevance scoring

This section classifies each significant observation, sizes it, tests its root cause and scores how directly better monitoring, forecasting, optimisation or control would address it.

**Classes.** Problem = measured shortfall against a target or benchmark, or a cost or harm. Risk = exposure shown by the data, no harm recorded. Opportunity = unused or growing potential. Cannot classify = data insufficient.

**Evidence grades.** A = reported and consistent. B = reported but flagged or unexplained. C = mostly my inference.

**EMS relevance** (High / Medium / Low / None) is judged only from what the reports show. **Not scorable** means the data is insufficient; I did not default these to None or Medium. Money figures are illustrative because the reports give no costs, and each assumption is stated.

**Two refinements.** (1) The system operator reduces plant output to manage frequency (AR 2.1.8, BR 2.1.7), which is operational control, though no system or software is named. (2) The only smart-meter reference is an LPG licence category (BR T6.1, AR T8.1), not electricity.

### 4.1 Network performance

| Item | Class and magnitude | Root cause: reported vs not reported | Better addressed by | EMS role | Score |
| --- | --- | --- | --- | --- | --- |
| **O16 Losses** | Problem (grade B). Reported 21.38% vs 16.5% allowance; computed 20.2% (flag 1). About 3.16 TWh lost (C: 15,601.02 − 12,444.71), 1.65× total imports. Above allowance: 582–761 GWh, about KSh 6–14 bn at KSh 10–18.57/kWh (illustrative). Utility bears the cost above allowance (D). Flat for four years, then −1.98 pp. | **Reported (D):** technical and commercial losses (illegal or unmetered connections, unread meters, tampering), no split; LV lines are 72.79% of 334,157 km. **Not reported:** the split, location, and how the rate was calculated. | Technical: conductor, transformer and voltage upgrades. Commercial: meter replacement, enforcement, billing correction. | Feeder or transformer energy balance to locate losses. This is distribution analytics, at the edge of the study's EMS definition (I). Each 1 pp of loss ≈ 156 GWh ≈ KSh 1.6–2.9 bn (C). | **Medium** (confidence Low) |
| **O17–18 Reliability** | Problem (grade B). SAIDI 13.16 h/month vs 1.5; CAIDI 3.23 h vs 1.36; SAIFI 3.91 vs 1.10. All 10.43 M customers. No economic cost reported. Worst in five years for SAIDI and CAIDI. H1 → H2 SAIDI 8.39 → 17.93 h, peaking at 27.33 h in May. | **Not reported.** Candidates (I, untested): planned works (five transmission facilities commissioned), asset condition, weather, crews and spares, generation or transmission events, a change in index basis (flag 15). Of the H1→H2 SAIDI rise, about 73% is longer outages and 27% more frequent ones (C, log split of the product of means). | Maintenance, reinforcement, crews and spares, protection, vegetation control. First, a diagnosis of causes. | Outage detection, fault location and restoration tools (distribution level); customer-side backup or hybrid supply. Indices are measured monthly (D); no automation is reported. | **Medium** (confidence Low) |

The reliability score would rise to High only if diagnosis shows restoration delay is mainly a visibility problem, and fall to Low if planned works or asset failure dominate.

### 4.2 Supply side

| Item | Class and magnitude | Root cause | Better addressed by | EMS role | Score |
| --- | --- | --- | --- | --- | --- |
| **O6 Peak adequacy** | Risk (grade C). Interconnected capacity rose about 71 MW (C) while peak rose 198 MW, so the firm margin narrowed about 127 MW. No load shedding or unserved energy is reported. | **Reported:** organic growth and connectivity (AR 2.1.4). **Not reported:** firm capacity, hourly margin. | New firm capacity, storage, imports. Pipeline (D, AR Ch9): Olkaria I rehabilitation, Ethiopian import doubling to 400 MW, four 132 kV lines. | Peak shaving by demand response. None reported; ToU is off-peak only. A 5% peak cut ≈ 126 MW (C), achievability unknown. | **Low** (Medium) |
| **O8, O14 Concentrated supply and imports** | Risk (B). Ethiopia link 200 MW (7.95% of peak) carried 1,577.66 GWh. Contract terms, cost and outage history not reported. | Import growth attributed to demand outpacing local generation (AR 4.1). | Diversification, contract design, domestic firm capacity. | Concentration risk is not an EMS matter. | **Low** (Medium) |
| **O10, O15 Thermal dispatch** | Problem (cost), minor (emissions) (B). 1,309 GWh. If FEC averages KSh 3.34/kWh on all sales, fuel recovery ≈ KSh 41.6 bn (assumption: FEC covers only thermal fuel and is charged on all sales). 100 GWh displaced ≈ KSh 3.0–3.2 bn and 64 kt CO₂ (C, at 0.64 t/MWh implied thermal factor). | **Reported:** thermal rose to meet demand and give peak and voltage support (AR 2.1.3, 4.2), so part is must-run. | Cheaper firm evening supply or storage; reactive support equipment. | Forecasting (hydro, wind, load) and economic dispatch for the displaceable part. Size unknown. | **Low** (Low) |
| **O4, O11–13 Curtailment** | Problem (shrinking) with an opportunity in the residual (B). 403.94 GWh (2.6% of generation, 5.8% of geothermal potential), −39.6%, but rising every month Feb→Jun. Value not computed: no energy price reported, and surplus (0000–0500) and shortfall (evening) may not match. ToU volume rose 87.5 GWh, 33% of the curtailment fall (co-movement, not proven cause). | **Reported:** low night demand, plant availability, import quantum at low demand, wind curtailed at contracted energy thresholds (AR 2.1.8), frequency management. **Not reported:** deemed-energy terms, who bears the cost, hourly profile. | Night-load creation (tariffs, industrial shifts), contract flexibility, storage hardware, regional export (net 136.55 GWh to Tanzania in H1). | Forecasting and scheduling of flexible loads, storage dispatch, price-responsive control, grid-level co-optimisation. Operator control exists (D). Imports stayed within −11% and +8% of the monthly mean (C), suggesting low observed flexibility (I). | **Medium** (Low) |
| **O9 Variability** | Neither at this resolution (A). Wind and hydro each swung about 100 GWh between best and worst months. | Monthly data only; hourly and forecast error not reported. | n/a | n/a | **Not scorable** |

### 4.3 Distributed supply and demand side

| Item | Class and magnitude | Root cause | Better addressed by | EMS role | Score |
| --- | --- | --- | --- | --- | --- |
| **O20–21 Captive solar** | Opportunity with a visibility gap (B/C). 373.3 MW; +72.8 MW ≈ half of national additions. Illustrative output 0.6–0.8 TWh/yr (3.8–5.3% of grid generation). | **Reported:** growth attributed to supplementing grid supply, managing cost, resilience, supportive policy (AR 3.2.4). **Not reported:** output, sites, exports, PPA prices (vs C&I retail KSh 17.3–26.1/kWh), storage. | Visibility is a reporting and licensing question; grid interaction falls under the Open Access Regulations 2026. | Site: monitoring and optimisation of solar, grid and any genset or storage. System: forecasting of embedded output. Third-party owners (BE Africa C&I, GridX) probably run their own monitoring (I, unreported). | **Medium** (Low) |
| **O23 Storage, net metering** | Cannot classify. Absent from all tables. | n/a | n/a | n/a | **Not scorable** |
| **O24 Mini-grids** | Cannot classify; possible opportunity (B). 91.79 GWh (0.58%), 93.05% thermal, average load 22.7% of capacity. | **Reported:** customers pay grid tariffs; some stations have solar. **Not reported:** fuel use, unit cost, outages, who funds the gap. | Right-sizing, fuel procurement, grid extension, hybridisation (capital). | Hybrid controller with forecasting to cut diesel; site monitoring. Need undemonstrated. | **Medium** (Low) |
| **O25 E-mobility** | Opportunity, early (A). 12.25 GWh, ≈1.4 MW average load; customers 115 → 543. Tenfold would be about 14 MW, 0.6% of peak (C). | Fast growth from tiny base. | Tariffs (cap removed 1 Jul 2026), charging infrastructure, regulation. | Managed charging; not a measurable grid issue at this scale. | **Low** (Medium) |
| **O26–27 Household demand** | Neither on its own (B). Domestic +686.75 GWh (61.6% of growth). About 99 kWh per customer-month across all categories. | **Reported:** per-capita use and customer growth. Domestic customers aren't eligible for ToU, so there is no time-varying price signal. | Tariff design, supply, efficiency labelling (230 of 239 refrigerator models ≤3 stars). | No price signal to optimise against. | **Low** at household level (Medium). Household load as a grid resource: **Not scorable** |
| **O31–32 ToU tariff** | Opportunity, partly realised (B). KSh 1,878.3 m saved (VAT inclusive) on 267.6 GWh; about 2,614 average beneficiaries at KSh 0.72 m each. About 60 MW average added off-peak demand. Eligible population unreported. | **Reported:** 50% off-peak discount; volume +48% with no reported EMS. **Not reported:** reasons for non-uptake; Dec-25 and Feb-26 anomalies. | Tariff design, outreach, thresholds. | Load scheduling and measurement so customers capture more of the discount. No evidence of an adoption barrier that software would remove. | **Medium** (Low) |
| **O40 Efficiency and audits** | Opportunity, realisation unknown (B). 65.53 GWh/yr identified, KSh 1.1–1.7 bn at C&I retail rates. The 180,000 kWh/yr threshold equals the 15,000 kWh/month C&I class boundary (C). | **Reported:** audits every four years; at least 50% of projected savings to be implemented; licensed manager and committee. **Not reported:** implementation, designated-facility count, any metering or software mandate. | Financing (ESCOs are mentioned), enforcement, technical assistance, equipment. | Sub-metering and monitoring-and-verification to track the 50% requirement; baselines and benchmarking. | **Medium** (Low) |

### 4.4 Prices, fuels, safety and regulation

| Item | Class and magnitude | Root cause | EMS role | Score |
| --- | --- | --- | --- | --- |
| **O30 Pass-through** | Problem (volatility), modest (B). About KSh 5.0/kWh, 16.5–19.7% of DC3 retail; about KSh 62 bn/yr if charged on all sales (C: FEC 41.6 + FERFA 14.9 + inflation 5.6 + WRA 0.2). | FEC follows thermal dispatch; FERFA follows FX and foreign-currency obligations. No lag mechanism described. | None. The thermal part is covered under O10. | **None** (Medium) |
| **O33–35 Petroleum price and supply** | Problem (price), risk (supply) (A/B). Murban +75.6%; AGO +39.8% Mar→May. Each KSh 10/L ≈ KSh 63 bn/yr (upper bound). | Middle East conflict and Hormuz disruption (AR 6.3.1); import dependence. | None directly. | **None** (Medium) |
| **O37–38 Pipeline and LPG** | Risk, unverified / neither (B/C). | Physical capacity, with expansion under way. | None. | **None** (Medium) |
| **O41 Disputes** | Problem, small scale (A). 187 disputes, about 1.8 per 100,000 customers; billing 72, disconnection 50. | Billing accuracy, meter reading, customer service. | Indirect, through metering and data quality; overlaps with losses. | **Low** (Low) |
| **O41 Accidents** | Safety harm (A). Petroleum and LPG: 121 accidents, 22 deaths; driver error 46.3%. Electrical: 129 accidents, 82 deaths, causes unreported. | Driver and operator safety (petroleum and LPG). | None for petroleum and LPG. | **None**; electrical causes **Not scorable** |
| **O42 Regulatory pipeline** | Context (A). | Energy Management Regulations 2025; Open Access Regulations 2026. | Enabling condition, not a problem. | Not scored |

### 4.5 Is an EMS-type capability already present or being deployed?

| Evidence | Source | What it implies | What it does not show |
| --- | --- | --- | --- |
| Operator reduces plant output for frequency management | AR 2.1.8, BR 2.1.7 | Real-time dispatch control exists | Tools, forecasting, automation |
| Monthly national series for losses, SAIDI, SAIFI, CAIDI | AR, BR | Aggregate measurement exists; indices internally consistent (C) | Feeder-level data; index basis |
| ToU billing for about 2,614 average beneficiaries | AR T2.6–2.7 (source Kenya Power) | Time-differentiated metering for those customers (I) | Wider metering coverage |
| Site-level monthly generation at KPLC mini-grids | BR Fig 2.8–2.9 | Site metering | Control or optimisation |
| Solar at some off-grid stations; one solar-plus-battery PPA (Mwingi) | AR 2.1.11, 3.2.4 | Hybrids exist, at least one with storage | Controllers; the Mwingi storage figure may be a unit error |
| Energy Management Regulations 2025 | AR Ch5, BR Ch4 | Organisational energy management | Any software or metering requirement |
| Open Access Regulations 2026 | AR Ch9 | Metering and energy accounting for wheeling | Operational status |
| Cross-border exchange accounting | BR 2.1.2 | Energy accounting with Ethiopia and Tanzania | System used |

The reports never mention SCADA, EMS, DMS, electricity AMI, demand response, virtual power plants, load forecasting or storage capacity. They are statistical reports, so this does not show such systems are absent.

### 4.6 Scores at a glance

| Score | Items |
| --- | --- |
| **High** | None |
| **Medium** | Losses, reliability, curtailment, captive solar, mini-grids, ToU, audits |
| **Low** | Peak adequacy, supply concentration, thermal dispatch, e-mobility, household level, disputes |
| **None** | Pass-through, petroleum price and supply, pipeline and LPG, petroleum and LPG accidents |
| **Not scorable** | Variability, storage and net metering, household load as a grid resource, electrical accident causes |

**Interpretation (I):**

1. **No item reaches High.** Each Medium has a missing link: an unreported cause (reliability, loss split), unreported contract terms (curtailment), missing size or cost data (captive solar, mini-grids), or no evidence of an adoption barrier (ToU, audits).
2. **The Mediums form two groups with different users and tools:** network visibility at utility level (losses, reliability), and flexibility and optimisation at site, customer or mini-grid level (curtailment, captive solar, ToU, audits, mini-grids).
3. **Losses and peak margin are mainly not EMS problems** on their reported causes (physical, commercial, capacity). **Reliability is undetermined**, because no cause is reported.
4. **Where the mechanism fits best, the size evidence is thinnest.** The flexibility cluster has no cost, hourly or eligibility data to size it.

### 4.7 What would move a score

| Missing data | Items it would move |
| --- | --- |
| Feeder or transformer loss split; outage cause codes by region | Losses, reliability (to High or Low) |
| Hourly load, curtailment and dispatch profile; import and PPA terms | Curtailment, thermal, peak adequacy |
| Captive output, site counts, PPA prices, grid exports | Captive solar |
| Eligible ToU customers and reasons for non-uptake | ToU |
| Audit implementation rate and number of designated facilities | Audits |
| Mini-grid fuel use and cost per kWh | Mini-grids |

## 5. Hypothesis testing

Matrix symbols: **+** supports, **(+)** weakly supports, **−** contradicts, **(−)** weakly contradicts, **0** no bearing or untestable. Two cautions: the Phase 4 scores are my judgement, and H3 was derived from them, so testing H3 on the same material is partly circular. Open-source suitability is not considered here.

### 5.1 Hypotheses tested

| ID | Statement | Note |
| --- | --- | --- |
| H0 | Kenya's energy challenges do not require an EMS; they are mainly supply, infrastructure, financing or policy issues. | Tested as stated ('do not require'), a strong claim |
| H1 | A significant need for an EMS exists at one or more levels. | 'Significant' = a sizeable, evidenced problem that an EMS would address |
| H2a | A need exists but is already adequately served. | Requires evidence about existing systems |
| H2b | A need exists but is better addressed another way. | Split from H2 because the evidence differs |
| H3 | The binding need is data and metering infrastructure plus market and contract flexibility, which an EMS would depend on rather than replace. | Derived from the Phase 4 scores; tested in three parts |

These overlap: H3 and H2b can both hold alongside a conditional form of H1. Only H0 and H1 are mutually exclusive.

### 5.2 Evidence matrix

| # | Evidence | Source | H0 | H1 | H2a | H2b | H3 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| E1 | No item scores High. The 7 Medium items all carry Low confidence. | Section 4 | (+) | (−) | 0 | 0 | (+) |
| E2 | Reported cause of losses is physical and commercial; no split, location or reproducible rate (flag 1). | AR 2.1.12 | + | 0 | 0 | + | + |
| E3 | Reliability cause not reported. About 73% of the H1→H2 SAIDI rise is longer outages (C). | AR 2.1.13 | 0 | (+) | 0 | 0 | + |
| E4 | Curtailment fell 39.6% and ToU sales rose 48.5% (KSh 1,878 m saved) with no EMS reported. | AR 2.1.8, 2.2.5 | + | (−) | (+) | + | 0 |
| E5 | Curtailment rose every month from Feb (9.1 GWh) to Jun (48.6 GWh); H2 flat y/y. | AR 2.1.8, BR 2.1.7 | 0 | (+) | (−) | 0 | 0 |
| E6 | Night surplus and evening thermal and import dispatch can't be tested without hourly data. | BR 2.1.7, AR 2.1.4 | 0 | 0 | 0 | 0 | + |
| E7 | Captive solar was about half of national capacity additions; output, sites and exports unreported. | AR 2.1.1, 3.2.4 | 0 | + | 0 | 0 | + |
| E8 | No mention of SCADA, EMS, DMS, AMI, demand response, forecasting or storage capacity (statistical reports). | Both | 0 | 0 | 0 | 0 | 0 |
| E9 | 24 unresolved inconsistencies, including on losses, H2 sales and reliability basis. | Section 2.5 | 0 | 0 | 0 | 0 | + |
| E10 | National monthly indices internally consistent; ToU and mini-grid site metering exist; operator controls curtailment. | AR 2.1.13, 2.2.5; BR 2.1.8 | 0 | 0 | (+) | 0 | − |
| E11 | Interconnected capacity +71 MW vs peak +198 MW (margin narrowed \~127 MW); no load shedding reported; additions in the pipeline. | AR T2.1, Ch9 | (+) | 0 | 0 | + | 0 |
| E12 | Open Access Regulations 2026 and Energy Management Regulations 2025 create duties; operational status unknown. | AR Ch5, Ch9 | 0 | (+) | 0 | (+) | + |
| E13 | Pass-through volatility, petroleum price and supply, pipeline, LPG logistics and petroleum accidents have no EMS role. | AR Ch6, Ch8 | + | 0 | 0 | 0 | 0 |
| E14 | Mini-grids 93% thermal at \~23% average utilisation; no fuel, cost or customer data. | AR 2.1.11, BR 2.1.8 | 0 | (+) | 0 | 0 | + |

Row counts are not evidence weight. E7, E10 and E12 do most of the work.

### 5.3 Test of each hypothesis

**H0: no EMS required.**

- *Supporting:* the largest measured problems have reported causes that are capital, operations or enforcement (E2, E11); petroleum, LPG and pass-through items have no EMS role (E13); curtailment and ToU improved without a reported EMS (E4); no item scores High (E1).
- *Contradicting:* seven items have a Medium-fit mechanism (E1); curtailment has risen since February (E5); captive solar has grown outside system visibility (E7); reliability has no reported cause (E3). H0 is a claim of absence, and the reports can't see within-day behaviour, feeders or sites.
- *Confidence in H0 as stated:* **Low.** Partly supported for the largest network and capacity problems; not established for the flexibility cluster.

**H1: significant EMS need.**

- *Supporting:* mechanism fit for the flexibility cluster and network monitoring; captive solar growth is fast and unobserved (E7); residual curtailment is rising (E5); reliability deterioration is dominated by longer outages (E3); new regulatory duties need metering and accounting (E12).
- *Contradicting:* no High score; no money or hourly value can be put on any EMS-addressable portion; no adoption barrier that software would remove has been shown; curtailment and ToU improved without an EMS (E4).
- *Confidence:* **Low.** Plausible at several levels, not demonstrated as 'significant', and not rejected, because the data that would size it is the data that is missing.

**H2a: already adequately served.**

- *Supporting:* operator controls dispatch in real time; monthly national indices exist (E10); third-party solar owners probably run their own monitoring (I, unreported).
- *Contradicting:* losses have exceeded their allowance for five years and all reliability indices exceed targets, so whatever exists isn't adequate for those outcomes (this doesn't show an EMS is the missing piece); curtailment is rising since February (E5).
- *Confidence:* **cannot be tested** (E8). Inconclusive.

**H2b: better addressed another way.**

- *Supporting:* losses (physical and commercial causes), peak margin (new firm capacity, imports, transmission in the pipeline), curtailment and night demand (tariffs and contracts appear to be doing the work), petroleum and LPG (logistics and policy).
- *Contradicting:* for reliability the cause is unreported, so 'better addressed another way' can't be shown; in the flexibility cluster no alternative has been shown to be sufficient.
- *Confidence:* **Medium** for losses, peak margin and petroleum and LPG. **Low** for reliability. **Not scorable** for the flexibility cluster.

**H3: data, metering and market flexibility first.**

| Part | Evidence | Confidence |
| --- | --- | --- |
| (a) The published record lacks the data to size or place any EMS opportunity. | No hourly, feeder, site or captive-output data; 24 flags (E6, E7, E9, E14). | **High**, but this is a fact about the reports, not about what KPLC or KETRACO hold internally. |
| (b) Contract and market flexibility is a binding constraint on the largest opportunity (curtailment). | Wind curtailed at contracted energy thresholds (D); import terms unreported (E5); Open Access Regulations meant to enable wheeling (E12). No deemed-energy or take-or-pay terms reported. | **Low–Medium** |
| (c) An EMS would depend on that data and flexibility rather than replace it. | Follows from what an EMS is (I); a design dependency, not an empirical finding. | Not tested against data; affects sequencing |

**Overall for H3: Low–Medium.** It is the hypothesis most consistent with the evidence, largely because the evidence is thin. If H3 is right, the EMS need is conditional on data and contract fixes, which is a partial form of H1.

### 5.4 Sizing check for 'significant' (H1)

| Pool | Size (C, illustrative) | Basis |
| --- | --- | --- |
| Losses above the allowance | 582–761 GWh, about KSh 6–14 bn | 21.38% vs 16.5%; KSh 10–18.57/kWh |
| Each 1 pp of loss | about 156 GWh, KSh 1.6–2.9 bn | 1% of 15,601 GWh |
| Audit-identified savings | 65.53 GWh/yr, KSh 1.1–1.7 bn | AR Ch5; C&I rates KSh 17.3–26.1/kWh |
| ToU savings realised | KSh 1.88 bn | AR 2.2.5 (VAT inclusive) |
| Curtailment | 404 GWh, value not computed | No energy price reported; surplus and shortfall may not match |
| Thermal fuel recovery | about KSh 41.6 bn | FEC × all sales, assumptions as in 4.2 |

The reports give no figure for the fraction of any pool that monitoring, forecasting or control could capture, and I assume none. These totals show the scale of the pools a tool might touch, not the size of an EMS benefit, and are not enough to establish 'significant'.

### 5.5 Reading across

| Statement | Confidence |
| --- | --- |
| The published reports lack the data to size or locate an EMS opportunity. | High |
| Petroleum, LPG and pass-through items are not EMS problems on this evidence. | Medium |
| For losses and peak adequacy, the reported root causes point mainly to capital, enforcement and capacity. | Medium |
| A cluster of site- and system-level flexibility opportunities has a fitting mechanism but is not sized. | Low–Medium |
| Reliability deterioration is substantial; its cause, and any EMS role, is undetermined. | Low |
| H0 as stated (no EMS required) is true. | Low |
| H1 as stated (significant EMS need) is demonstrated. | Low |

No hypothesis reaches Medium confidence in its full form; only the narrower statements do. The strongest items for H1 (E7, E5) and against it (E4, E11) are observations from the reports and independent of my scoring. E8 means a central question (H2a) can't be answered.

### 5.6 What would change these conclusions

| If we found | It would shift |
| --- | --- |
| Hourly data showing night surplus overlapping evening thermal or import use | H1 up for curtailment; H3(b) |
| Feeder-level losses and outage cause codes showing locatable, recoverable losses or restoration delay | H1 up (network), or H2b up if causes are mainly capital or physical |
| Captive output, site counts and PPA terms showing material unobserved or exported energy | H1 up at C&I level |
| Evidence that KPLC or KETRACO already run SCADA, DMS or AMI covering the use cases | H2a up |
| ToU eligible customers and non-uptake reasons showing a software-fixable barrier | H1 up for ToU |
| Mini-grid diesel cost per kWh showing diesel is a large cost | H1 up for mini-grids |
| Load-shedding or unserved-energy records showing a capacity shortfall | H2b up at national level |

## 6. Verdict and confidence

### 6.1 Verdict

**Need partially confirmed, at a narrow level, with low confidence.**

This sits at the boundary with 'Inconclusive'. I chose 'partially confirmed' because of the asymmetry below, not to enable the recommendation section.

|  | What the evidence establishes | Basis |
| --- | --- | --- |
| **Confirmed** | Large, measured problems exist at network level: reliability is the worst in five years and 2.4–8.8× off target, and losses are above the allowance in all five years (AR 2.1.12–2.1.13, D). | A/B grade |
| **Confirmed** | A fast-growing part of supply cannot be seen in the published data: captive solar was about half of national capacity additions (+72.8 MW of 146.4 MW), with output, sites and exports unreported (AR 2.1.1, 3.2.4, D+C). | B grade |
| **Plausible, not demonstrated** | A fitting EMS mechanism exists for a cluster of flexibility and visibility items (curtailment, captive solar, ToU, audits, mini-grids, network monitoring). No item reaches High and none can be sized in money or hours. | Low confidence |
| **Not confirmed** | That the benefit is 'significant' (H1 as stated). The reports give no figure for the share of any pool that monitoring, forecasting or control could capture. | Low confidence |
| **Not testable** | That the need is unmet. The reports cannot show what systems KPLC, KETRACO or the system operator already run (H2a). | n/a |

**Why partial and not inconclusive:** H0 reached only Low confidence. For the flexibility and visibility items, nothing in the reports contradicts a need, and nothing shows it is already met. The missing evidence is about size and existing systems, not evidence against need.

**Why not confirmed:** the strongest problems have reported causes that are not EMS-type (losses: physical and commercial; peak margin: capacity). Where the mechanism fits best, the size data is thinnest. Curtailment and ToU also improved with no reported EMS.

### 6.2 Provisional verdict by level

| Level | Verdict | Confidence | Why |
| --- | --- | --- | --- |
| National / grid (system operator) | Partially confirmed, for curtailment and dispatch only | Low | Curtailment 404 GWh, down 39.6% but rising Feb→Jun (D). Contract terms and hourly data missing. Real-time control already exists (AR 2.1.8). |
| Utility (distribution network) | Partially confirmed, for visibility only | Low | Reliability and losses are large, but causes are unreported or mainly physical and commercial. The EMS role is feeder-level monitoring, at the edge of the study's definition (I). |
| County | Not testable | n/a | Data is by KPLC region only. |
| Mini-grid | Inconclusive | Low | 93% thermal and about 23% utilised (C), but 0.58% of generation with no fuel or cost data. |
| C&I (including captive solar) | Partially confirmed | Low | Most observations in its favour: captive solar growth, about 2,614 average ToU beneficiaries, 156 audits identifying 65.53 GWh/yr, new audit-and-verify duties. No software-removable adoption barrier shown; vendor tools may already serve it (H2a). |
| Institutional / public buildings | Not testable | n/a | No institutional consumption reported. |
| Household | Not confirmed | Medium | No time-varying price signal; about 99 kWh per customer-month across all categories (C). |
| E-mobility | Not confirmed (watch item) | Medium | 12.25 GWh, about 1.4 MW average load (C). |
| Petroleum, LPG, pass-through costs | Not confirmed | Medium | No EMS role on this evidence. |

### 6.3 Confidence

**Overall confidence in the verdict: low.** Four reasons:

1. The verdict rests on Section 4 scores that are my judgement, and on H3, which I derived from them.
2. The 24 data flags include ones on losses, H2 sales and the reliability index basis. If the index basis changed in 2026, the reliability trend weakens.
3. The reports are annual and half-yearly statistics; the behaviour an EMS acts on (hourly, feeder, site) is invisible in them.
4. The reports are silent on existing systems, which limits what any verdict can say.

**Narrower statements with higher confidence:** the reports lack the data to size or place any EMS opportunity (high); petroleum, LPG and pass-through items are not EMS problems (medium); losses and peak adequacy are mainly capital, enforcement and capacity questions on the reported causes (medium).

### 6.4 What would change the verdict

| Finding | Moves the verdict to |
| --- | --- |
| Hourly data showing night curtailment overlapping evening thermal or import dispatch, large enough in energy and cost to matter | Confirmed for national/grid |
| Feeder-level or cause-coded data showing restoration delay or locatable losses | Confirmed (utility) if visibility-driven; Not confirmed if capital or asset-driven |
| Captive-solar output, exports and PPA terms showing material unobserved or exported energy | Confirmed (C&I) |
| Evidence that SCADA, DMS, AMI or customer EMS tools already cover these use cases | Need already served (H2a): a negative verdict for new build |
| A low audit implementation rate traced to measurement or tracking problems | Confirmed (C&I, efficiency) |
| Load-shedding or unserved-energy records showing a capacity shortfall | National-level need becomes a capacity question (H2b) |
| Mini-grid diesel cost per kWh | Confirmed or Not confirmed (mini-grid) |

The verdict would fall to Not confirmed or Inconclusive if the missing data shows existing systems already serve the C&I and system-operator needs, or if the flexibility pools turn out to be small in money terms.

### 6.5 Strongest evidence for and against

- **For:** captive solar grew +72.8 MW (+24.2%), about half of all national additions, and the reports give no output, site count or grid-export figure for it (AR 2.1.1, 3.2.4).
- **Against:** curtailment fell 39.6% and ToU low-rate sales rose 48.5% (KSh 1,878 m saved) with no reported EMS (AR 2.1.8, 2.2.5). The improvements came from demand and tariff changes, though unreported existing systems could also be a factor, and the reports can't tell.

## 7. EMS type and level recommendation

**Status.** The verdict was partially confirmed with low confidence, so everything below is conditional. The ranking is the best-supported order given what the reports show, not a demonstrated need. Ratings are ordinal judgements, not weighted scores, because weights would have to be invented. Open-source suitability (7.3) did not affect the ranking.

### 7.1 Level-by-level assessment

| Criterion | C&I (with captive solar, efficiency, ToU) | System-level flexibility (operator) | Distribution visibility (adjacent to EMS definition) | Mini-grids |
| --- | --- | --- | --- | --- |
| **Size** | **Medium.** ToU savings KSh 1,878 m realised; audits identified 65.53 GWh/yr (about KSh 1.1–1.7 bn); captive 676.6 MW incl. 373.3 MW solar, output unreported; large C&I = 47.57% of sales. | **Potentially largest, unquantified.** Curtailment 403.94 GWh; thermal 1,309 GWh; imports 1,913.66 GWh. No energy price reported, so not valued. | **Largest measured.** About 3.16 TWh lost, 582–761 GWh above allowance; SAIDI 13.16 h vs 1.5 h for 10.43 M customers. | **Inconclusive.** 91.79 GWh (0.58%); 46.24 MW, 93.05% thermal; average load 22.7% of capacity. No fuel or cost data. |
| **Users and adoption** | **Unknown size.** About 2,614 average ToU beneficiaries; 156 facilities audited. Designated-facility and captive-operator counts unreported. Average ToU saving about KSh 0.72 m per beneficiary (C) is a financial motive (I). | **One institution.** Depends on operator and its contracts. | **One main utility** (KPLC), plus KETRACO for transmission. | **Small.** At least 8 named stations; Mandera, Lodwar, Wajir = 58.8% of output. KPLC operates them. |
| **Data and feasibility** | **Medium–High, unevidenced in the reports.** Site metering is under the customer's control (I, general engineering knowledge). | **Low for an outside developer.** Hourly data probably held internally (I), none published. | **Low.** Feeder data unpublished; loss rate not reproducible (flag 1); reliability basis unclear (flag 15). | **Medium.** Site-level monthly generation already metered; some solar present. |
| **Regulatory fit** | **Good.** Energy Management Regulations 2025 (audits every 4 years, at least 50% of savings implemented, manager, committee); Open Access Regulations 2026; ToU established. Barriers: no software or metering mandate reported; post-2025/26 tariff period undescribed. | **Neutral.** Real-time control exists; contract terms unreported. | **Strong pull.** Regulator sets loss and reliability targets; utility bears losses above allowance. | **Unclear.** Private mini-grids unquantified. |
| **Impact** | **Cost saved: medium. Reliability: customer-side only. Emissions: small.** Audit pool ≈ 3.5 kt CO₂ at the grid average factor and ≈ 42 kt at the thermal-implied factor, both ceilings at full implementation (C). | **Potentially energy, cost and emissions.** Each 100 GWh of thermal displaced ≈ KSh 3.0–3.2 bn and 64 kt CO₂ (C, illustrative). | **Potentially high but conditional.** Loss causes are physical and commercial; reliability cause unreported. | **Unknown.** A diesel-saving hybrid controller would fit (I); no cost data shows the saving is material. |
| **Fit to EMS definition** | Good (generation plus consumption). | Good. | **Edge.** Feeder-level metering and analytics (I). | Good. |
| **Evidence confidence** | Low | Low | Low | Low |

**Other levels**

| Level | Status | Reason |
| --- | --- | --- |
| County | Unranked: no evidence | Data is by KPLC region only. |
| Institutional / public buildings | Unranked: no evidence | No institutional consumption reported. |
| Household | Not recommended now | No time-varying price signal; household load as a grid resource not scorable. |
| E-mobility | Watch item | About 1.4 MW average load; tenfold would be about 0.6% of peak. |
| Petroleum, LPG, pass-through | No EMS role | Section 4. |
| Statistical data quality (24 flags) | Not an EMS | Better handled as a data-strategy item (Section 8). |

### 7.2 Ranking

| Rank | Level | Why this position | Main dependency |
| --- | --- | --- | --- |
| **1** | **C&I (with captive solar, ToU, monitoring and verification)** | Most independent observations in its favour (captive solar growth, ToU uptake, audit duties). Fits the EMS definition. Can start without utility data. | Vendor tools may already serve it (H2a). No adoption barrier is evidenced. |
| **2** | **System-level flexibility** | Best mechanism fit, potentially large; curtailment rising since February. | Hourly data, contract terms, operator access. |
| **3** | **Distribution visibility (adjacent)** | Largest measured problems, but reported causes are mainly non-EMS and it sits at the edge of the definition. | Feeder and cause-coded data; resolving flags 1 and 15. |
| **4** | **Mini-grids** | Mechanism fits, but no size evidence. | Fuel use and cost per kWh. |

Ranks 2 and 3 are close to a tie. I put system-level flexibility ahead because it fits the EMS definition better, even though the distribution problems are larger and better measured. Ranks 2 to 4 each depend on data or access that an outside developer does not currently have, which is why they are not starting points.

### 7.3 Open-source suitability (separate; not used in the ranking)

| Level | Suitability | Reasoning | Risks |
| --- | --- | --- | --- |
| C&I | **High** | Customer-side deployment. Open metering and messaging protocols (Modbus, MQTT) are widely used (external, unverified). | Inverter and meter vendor lock-in at device level; integrators may resist. |
| Mini-grid | **Medium–High** | Small sites suit open controllers; data already exists. | Hardware control raises safety and warranty issues. |
| System-level | **Low–Medium** | Operator systems are likely proprietary (I, unverified). Open tools suit study and forecasting more than operations. | Integration with proprietary SCADA. |
| Distribution | **Medium** | Analytics layers could be open. | Utility data isn't open, and open source doesn't solve data access. |

Existing open-source energy-management projects such as OpenEMS and Emoncms are known to me but are **external and unverified**; check their current status, licences and fit before relying on them. Open source does not remove dependence on utility data, tariffs or contracts.

**Separate social-impact note.** The mini-grids serve communities in the north (Mandera, Lodwar, Wajir), and North Eastern region consumption grew 14.61% (AR 2.1.7). A mission-weighted view might add a mini-grid pilot as a second track. That is a values decision, not an evidential one, because the data on mini-grid need is inconclusive, and it did not change the ranking.

### 7.4 Where to start

**A staged, monitoring-first C&I pilot, preceded by a data-validation step that costs little and involves no build.**

| Stage | What | What it tests | Stop or pivot if |
| --- | --- | --- | --- |
| **0. Validate (no build)** | Ask EPRA or KPLC for eligible ToU customer counts and non-uptake reasons, the number of designated facilities and audit implementation rate, and captive solar output and export data where licensing captures it. Survey existing C&I vendor tools. | H2a; size of pools | Vendor tools already serve the segment, or the pools are small |
| **1. Monitor** | Read-only metering at a small set of willing C&I sites (solar, grid, any genset). | Visibility gap (E7); baseline for verification | Customers see no value in data alone |
| **2. Optimise, in order of evidence** | ToU load scheduling, then solar self-consumption, then verification of audit measures. | ToU capture; audit-measure tracking | Savings are not measurable against baselines |
| **3. Reassess** | Use pilot data to re-score levels 2–4. | Whether the system or mini-grid level is worth pursuing | n/a |

**Why not start at rank 2 or 3:** they need data and institutional access an outside developer does not have today (I). **Why not mini-grids:** there is no cost evidence, and a control deployment would raise safety and licensing needs without a demonstrated benefit.

**Safety and compliance.** Read-only metering carries the lowest risk. Any control of inverters, gensets, storage or loads, and any work on installations, must follow local electrical codes and EPRA licensing (solar PV and electrical worker or contractor licences, BR 6.1.2, AR 8.1.2) and be verified by a qualified professional. Energy-use data is personal or commercially sensitive, so collection needs consent and security from the start.

### 7.5 What would change this recommendation

| Finding | Effect |
| --- | --- |
| Stage 0 shows vendor tools already serve C&I | Drop the build; consider a niche or interoperability role |
| Hourly data shows large evening thermal or import use alongside night curtailment | Move system-level flexibility to rank 1; plan research or partnership, not a build |
| Feeder data shows restoration delay is a visibility problem | Move distribution visibility up |
| Mini-grid diesel cost per kWh is high | Move mini-grids up |
| Captive output is small or fully self-consumed | Weaken the C&I solar rationale; rest the case on ToU and audits only |

**Confidence in this recommendation: low.** It is a hypothesis to test, built on the Section 6 verdict.

## 8. Recommended deliverables

Because the verdict was partially confirmed with low confidence, these deliverables mostly test the need before anyone builds anything. The order is: validate, then design a small pilot, then scale the work.

### 8.1 Priority 1: do first, low cost, no build

| # | Deliverable | Purpose | Evidence that justifies it |
| --- | --- | --- | --- |
| 1 | **Data request and validation brief** | Ask EPRA and KPLC for the figures that decide the verdict: eligible ToU customers and non-uptake reasons; number of designated facilities and audit implementation rate; captive solar output and exports; hourly curtailment and dispatch (if shareable); load-shedding or unserved-energy records. Route via statistics@epra.go.ke (D, both reports). | No hourly, feeder, site or captive-output data (Section 2). Every score-changing item in 4.7, 5.6 and 6.4 depends on these. |
| 2 | **Existing-tools scan (H2a test)** | Map what C&I customers can already buy or use in Kenya for energy monitoring, solar optimisation and verification, proprietary and open source. The only way to test 'already adequately served'. | The reports cannot show what systems exist (E8). Findings are external research and must be labelled external and unverified until checked. |
| 3 | **Narrow problem statement** | Fix the scope in writing: C&I visibility and flexibility first, conditional on deliverables 1 and 2. State what is not claimed (that losses, reliability or petroleum are EMS problems). | Section 6 verdict and levels. The same text works for a funder or partner without overstating the case. |
| 4 | **Data-quality note for EPRA** | A short, neutral list of inconsistencies for correction in the next edition, e.g. the loss rate (flag 1), the reliability basis (flag 15), the Coast share. | 24 flags (Section 2.5). Useful regardless of any EMS, and builds the relationship needed for deliverable 1. |

### 8.2 Priority 2: after Priority 1 shows the need survives

| # | Deliverable | Purpose | Evidence that justifies it |
| --- | --- | --- | --- |
| 5 | **Stakeholder map** | Identify who holds the data, who is affected and who can block: EPRA, KPLC, KETRACO, KenGen, third-party solar owners (BE Africa C&I, GridX and others in BR T6.3 and AR 3.2.4), licensed energy auditors, audit firms and managers (17, 7 and 50 licensed in FY25/26), and REREC for mini-grids. | The reports name these actors (D), but who holds hourly data and who runs the system operator function is not stated. |
| 6 | **Monitor-first C&I pilot design** | Define sites, hypotheses, success metrics, a stop-or-pivot rule at each stage (7.4), and consent and data-handling terms. Stage 1 is read-only metering. | Rank 1 level (7.2). Captive solar growth is the strongest observation for the need (E7). |
| 7 | **Data strategy and privacy plan** | Ownership, consent, retention, access control and anonymisation for customer energy data, settled before any collection. | Needed from the start for any pilot; also sets terms for sharing data with EPRA or KPLC. |
| 8 | **Baseline and M&V method note** | Show how pilot savings will be measured against baselines so results are credible. | The Energy Management Regulations 2025 require at least 50% of projected savings to be implemented (AR Ch5, D), but no tracking method is reported. |

### 8.3 Priority 3: only if the pilot shows value

| # | Deliverable | Purpose | Evidence that justifies it |
| --- | --- | --- | --- |
| 9 | **Requirements specification and architecture outline** | A minimal, open-protocol, read-only-first design, with architecture decision records for build vs integrate vs adopt an existing open-source project. | Premature before deliverables 1 and 2. If the scan finds the need served, this may not be needed at all. |
| 10 | **Funding and partnership approach** | Frame as a validation grant or partnership, not a scale-up. Likely partners: an audit or ESCO firm, a third-party solar owner, a university. Funder names and terms would be external, unverified. | The evidence supports a test, not a scale-up. |
| 11 | **Impact measurement plan** | Define success: kWh saved, KSh saved, ToU capture, solar self-consumption. Avoid emissions claims beyond the ceilings in 7.1. | Audit pool of 65.53 GWh/yr, about KSh 1.1–1.7 bn and 3.5–42 kt CO₂ (C, ceilings at full implementation). |

**Optional second track (a values decision for the study's owner).** A mini-grid study (Mandera, Lodwar, Wajir), starting with fuel use and cost per kWh before any control design. The evidence is inconclusive, so this is a research task, not a build, and I did not rank it above the C&I track.

### 8.4 What I am not recommending

| Item | Reason |
| --- | --- |
| Household EMS product | No time-varying price signal; household load as a grid resource is not scorable. |
| E-mobility managed charging | About 1.4 MW average load (C). Revisit when e-mobility regulations and counts exist. |
| Any EMS for petroleum, LPG or pass-through costs | No EMS role (Section 4). |
| County or institutional EMS | No data in the reports; request data first (deliverable 1). |
| A utility or system-operator build | Needs data and access an outside developer lacks. Better pursued as research or partnership after Stage 0. |

### 8.5 Suggested sequence

| Step | Deliverables | Decision at the end |
| --- | --- | --- |
| Weeks 1–4 (indicative) | 1, 2, 3, 4 | Continue, narrow or stop. A stop is a valid outcome. |
| Next | 5, 6, 7, 8 | Run a small read-only pilot, or not. |
| Only if justified | 9, 10, 11 | Build, integrate or partner. |

The time estimate is my planning judgement, not something the reports support.

## 9. Data gaps and suggested follow-up research

| Gap | Why it matters | Deliverable |
| --- | --- | --- |
| Hourly load, curtailment and dispatch | Decides the system-level rank | 1 |
| Feeder-level losses and outage cause codes | Decides whether network problems are visibility problems | 1 |
| Captive output, sites, exports and PPA terms | Decides the C&I solar case | 1 |
| ToU eligible customers and non-uptake reasons | Decides whether software could help | 1 |
| Audit implementation rate and designated-facility count | Decides the monitoring-and-verification case | 1 |
| Existing EMS, SCADA, AMI and vendor tools | Decides H2a | 2 |
| Load-shedding or unserved-energy records | Tests the peak-margin risk | 1 |
| Resolution of flags 1, 2 and 15 (loss rate, H2 sales, reliability basis) | Affects the size of the largest problems | 4 |
| Mini-grid fuel use and unit cost | Decides the optional track | Optional |
| Energy cost data (PPA prices, cost of curtailment and losses) | Lets any pool be valued in money | 1 |
| Data after 30 June 2026 (e.g. whether first oil on 1 Dec 2026 and the next tariff period have taken effect) | The reports end at June 2026 | 1 |

## Closing: strongest evidence for and against

- **Strongest for:** captive solar grew +72.8 MW (+24.2%), about half of all national capacity additions, and neither report gives its output, site count or grid exports (AR 2.1.1, 3.2.4). A fast-growing part of supply is invisible in the published data.
- **Strongest against:** curtailment fell 39.6% and ToU low-rate sales rose 48.5% (KSh 1,878 m saved) with no EMS reported (AR 2.1.8, 2.2.5). The improvements came from demand and tariff changes, though unreported existing systems could also be at work, and the reports can't tell.

**Overall conclusion:** need partially confirmed at a narrow level, with low confidence. It is a case for a cheap validation step, not for a build.
