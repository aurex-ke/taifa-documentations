# Step 4, part 1: blind relevance scoring (written before comparison with baseline)

Status: draft. Phase 3-4 of the brief. Sources: AR = Energy & Petroleum Statistics
Report (yr to 30 Jun 2026); BR = Biannual report (Jul-Dec 2025).
Evidence IDs refer to knowledge-base/evidence_register.md (D / C / I).
Rows marked "new" are proposed in Block 3 (D-070 to D-074, C-030 to C-035,
I-008 to I-012) and are not yet in the register.

**Independence note.** The baseline text was in the chat context at the start.
Scores were written from register IDs only and fixed before comparison.
Agreement with the baseline is weak evidence; differences are informative.

**Scale** (methodology section 4): High = material issue that monitoring,
forecasting, optimisation or control could plausibly address, with a stated
causal link. Medium = may help, but evidence, magnitude, feasibility or
attribution is incomplete. Low = indirect, small or weakly supported.
None = no meaningful EMS contribution or another intervention clearly fits.
**"Not scorable"** is an extension used where evidence is insufficient to place
an item on the four-level scale. It is flagged for user approval (see Waiting on).
Confidence in brackets is confidence in the score, not in the problem.

## A. Scored items

| ID | Item | Evidence | Class and magnitude | Root cause: reported / not reported | Better addressed by | EMS role | Score | Sensitivity |
|---|---|---|---|---|---|---|---|---|
| S-01 | Network losses | D-026, D-027, C-008, C-009, I-003, C-030 (new) | Problem. 21.38% vs 16.5% allowance (4.88 pp); above allowance in all five years. 1 pp = 156.0 GWh. Pool above allowance 581.9-761.3 GWh (recomputed vs reported loss rate) | **Reported:** technical plus commercial (unread, unmetered, tampered, illegal connections). **Not reported:** split, location, formula | Conductor and transformer upgrades, meter replacement, enforcement, billing | Feeder or transformer energy balance to locate losses. The commercial part is partly a metering and visibility issue, but the remedy is likely AMI or revenue protection, at the edge of the EMS definition | **Medium** (Low) | Low if scope excludes distribution analytics. High only if a split shows locatable commercial loss |
| S-02 | Reliability | D-028, D-029, D-030, D-069, C-029, C-034 (new) | Problem. FY25/26 SAIDI 13.16 h vs 1.5; CAIDI 3.23 vs 1.36; SAIFI 3.91 vs 1.10. Five-year worst for SAIDI and CAIDI. SAIDI Mar-Jun mean 21.49 h vs 8.99 h Jul-Feb | **Reported:** none. **Not reported:** outage causes, planned vs unplanned, index basis. Flag 25: AR text says CAIDI "complied" 2021/22-2023/24 but Fig 2.20 shows 2.76, 2.25, 2.53 h vs 1.36 h | Maintenance, reinforcement, crews and spares, protection | Outage detection, fault location, restoration (distribution automation, EMS-adjacent) | **Medium** (Low) | High if cause codes show restoration delay is a visibility problem. Low if planned works or asset failure dominate |
| S-03 | Curtailment | D-014, D-015, D-016, D-065, D-070, D-071 (new), C-003, C-004, C-032 (new), I-004, I-008 (new) | Problem, shrinking; residual opportunity. 403.94 GWh = 2.57% of generation; geothermal curtailment = 5.76% of potential. Down 39.6%, all of the fall in FY-H1; FY-H2 flat y/y (+1.0%) | **Reported:** low night demand (0000-0500), plant availability, import quantum at low demand, wind contract thresholds; the fall is attributed to higher night demand (1,152 to >1,400 MW). **Not reported:** hourly profile, contract and deemed-energy terms, who bears cost, energy price | Night-load creation (tariffs), contract terms, storage hardware, regional export | Forecast and schedule flexible load, storage dispatch, dispatch and import co-optimisation. Operator control exists (D-065); tools unknown | **Medium** (Low) | High needs hourly overlap of night surplus with evening thermal or import use, plus a price. Low if cost sits in contracts and flexibility is limited |
| S-04 | Peak adequacy | D-017, D-018, D-001, D-059, C-005 | Risk. Peak +198 MW vs interconnected capacity +71 MW (derived, C-005). Outlook +200 MW | **Reported:** organic growth and connectivity. Load-shedding and unserved-energy records are not in the reports (a gap, not evidence of none) | Firm capacity, imports, transmission (pipeline in D-059) | Peak shaving or demand response. None reported; ToU is an off-peak incentive | **Low** (Low) | Medium if unserved-energy records show a shortfall and demand-response potential is shown |
| S-05 | Thermal dispatch and fuel cost | D-010, D-032, D-046, D-073 (new), D-038, C-012, C-033 (new) | Problem (cost), minor. 1,309.42 GWh (8.34%) in Ch2 vs 1,399.54 in Ch4 (C-012). FEC 2.99-3.81 KSh/kWh | **Reported:** thermal meets demand, gives peaking and voltage support; higher Aug-Feb output attributed to lower hydro and wind. Monthly thermal vs hydro+wind r = -0.58 (n=12, one year). **Not reported:** must-run share | Cheaper firm evening supply, storage, reactive support | Forecasting and economic dispatch for the displaceable part | **Low** (Low) | Medium if the displaceable share is shown |
| S-06 | Imports | D-010, D-011, D-045, D-059, D-070 (new), C-012 | Risk and scale. 1,913.66 GWh (12.19%), +24.76%; Ethiopia link 82.45%; next phase 400 MW | **Reported:** demand outpacing local generation. **Not reported:** contract terms, cost | Contracts, diversification, firm domestic capacity | The interaction with curtailment is scored under S-03 | **Low** (Low) | Medium only if contract flexibility is shown |
| S-07 | Wind and hydro variability | D-013, D-072 (new), D-046, C-033 (new) | Observation. Monthly range about 103 GWh each (hydro 247.53-350.35; wind 113.70-216.39). Hydro half-year series 1,114.78-1,843.57 GWh | Monthly data only. No forecast error, reserve or balancing cost | n/a | Forecasting is an EMS-type function, but no magnitude is shown | **Not scorable** | Medium if forecast error or reserve cost is shown |
| S-08 | Captive solar | D-002, D-003, D-004, D-043, D-044, I-006 | Opportunity with a visibility gap. 373.30 MW; +72.8 MW (+24.22%) = 49.7% of national additions. Output, sites, exports unreported. Six C&I PPAs, 0.64-3 MW each | **Reported:** supplement grid supply, manage cost, resilience, policy. **Not reported:** output, exports, PPA prices, storage | Reporting and licensing returns; Open Access Regulations (D-059) | Site monitoring and optimisation of solar, grid, genset, storage; system-level forecasting of embedded output | **Medium** (Low) | High needs output and export data plus evidence that sites are unmanaged. Low if owners already run monitoring (unreported) |
| S-09 | Mini-grids | D-006, D-007, D-010, D-047, D-048, C-031 (new), I-012 (new) | Observation. 91.79 GWh (0.58% of generation), +4.36%; 93.05% thermal capacity; average load 10.48 MW = 22.7% of 46.24 MW (22.0% of 47.58 MW) | **Reported:** grid tariffs charged; some stations have solar. **Not reported:** fuel use, unit cost, outages | Right-sizing, hybridisation, grid extension | Hybrid controller and forecasting to cut diesel | **Low, borderline Medium** (Low) | Medium if diesel cost per kWh is high and solar share low. 22% utilisation may reflect standby capacity (external, unverified) |
| S-10 | ToU tariff | D-031, D-034, D-035, D-036, C-017, I-007, C-035 (new) | Opportunity, partly realised. 267.6 GWh (2.15% of sales); KSh 1.88 bn savings (VAT inclusive; 7.02 KSh/kWh); about 2,614 average beneficiaries (sum of D-035 FY25/26 column). Eligible population unknown | **Reported:** 50% off-peak discount, aimed at flattening demand. **Not reported:** non-uptake reasons, thresholds, Dec-25 and Feb-26 anomalies | Tariff design, outreach, thresholds | Customer-side load scheduling and measurement to capture the discount | **Medium** (Low) | High if scheduling difficulty is shown to leave discount unclaimed. Low if uptake is limited by thresholds or awareness |
| S-11 | Audits and measurement and verification | D-049, D-050, D-051, D-052, D-053, D-054, C-021, C-035 (new), I-002 | Opportunity, realisation unknown. 156 audits identify 65.53 GWh/yr (0.53% of sales, 0.42% of generation). Rules require at least 50% of projected savings | **Reported:** audits every 4 years, manager, committee. **Not reported:** implementation rate, designated-facility count, any software or metering mandate | Finance, ESCOs, enforcement, equipment | Sub-metering and M&V to track the 50% duty | **Medium** (Low) | Low if the savings are mainly equipment or process capital measures |
| S-12 | Household demand | D-021, C-009, C-022, D-031 | Observation. Domestic +686.75 GWh (+18.87%), 34.77% share; 99.4 kWh per customer-month (all categories pooled) | **Reported:** per-capita use and customer growth. Domestic is not listed as ToU-eligible (inference from AR p.26) | Tariff design, efficiency standards | No time-varying price signal to optimise against | **Low** (Low). Household load as grid resource: **Not scorable** | Medium if a time-varying household tariff exists |
| S-13 | E-mobility | D-060, D-021, D-031 | Opportunity, early. 12.25 GWh (average load about 1.4 MW), +143%; tariff customers 115 to 543 | Fast growth from a tiny base; vehicle and charger counts unreported | Tariff (cap removed 1 Jul 2026), regulation | Managed charging | **Low** (Low) | Medium if counts and charging profiles appear |
| S-14 | Disputes | D-057 | Problem, small. 187 disputes, KPLC 88.2%; billing 72, disconnection 50 | Causes beyond category not reported | Billing and customer service | Indirect, via metering and data quality | **Low** (Low) | |
| S-15 | Storage and net metering | I-005, D-044 | Cannot classify. No storage capacity or net-metering data | n/a | n/a | n/a | **Not scorable** | |
| S-16 | County and institutional or public buildings | D-022 | Cannot classify. Data are by KPLC region only; no institutional consumption | n/a | n/a | n/a | **Not scorable** | |
| S-17 | Electrical accident causes | D-058 | 129 accidents, 82 fatalities; causes not reported | Not reported | n/a | n/a | **Not scorable** | |

## B. Items scored None

| ID | Item | Evidence | Reason |
|---|---|---|---|
| S-18 | Pass-through volatility | D-032, D-033, C-019 | FERFA follows FX and foreign-currency obligations; FEC follows thermal dispatch (overlaps S-05) |
| S-19 | Petroleum price and supply | D-061, C-023, C-028 | Driven by world prices and import dependence |
| S-20 | Pipeline and LPG logistics | D-062, C-027, D-064 | Physical capacity; the only smart-meter reference is an LPG licence category |
| S-21 | Petroleum and LPG accidents | D-058 | Driver and human error 46.3% |
| S-22 | Biomass and energy balance | D-056 | About 95% of indigenous production is biomass; not addressable by this EMS definition |
| S-23 | Network build-out and connection growth | D-019, D-025, D-059 | Capital programme |

## C. Context items, not scored

Open Access Regulations 2026 and Energy Management Regulations 2025 (D-049, D-059) are enabling conditions. Report-quality flags (loss-rate reproduction C-008, H2 sales C-009, street-lighting ratio C-025, pump-price differences C-026) lower confidence in S-01 and S-02 but are not EMS items.

## D. Tally (blind)

| Score | Count | Items |
|---|---|---|
| High | 0 | none |
| Medium | 6 | S-01, S-02, S-03, S-08, S-10, S-11 |
| Low | 7 | S-04, S-05, S-06, S-09 (borderline Medium), S-12, S-13, S-14 |
| None | 6 | S-18 to S-23 |
| Not scorable | 5 | S-07, S-12 (household load as grid resource), S-15, S-16, S-17 |

No item reaches High. Each Medium has a named missing link: S-01 split and location; S-02 cause; S-03 hourly data and contract terms; S-08 output and exports; S-10 eligible population and barrier; S-11 implementation rate.
