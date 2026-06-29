# AI Infrastructure Research Framework

## Page 1: Power Constraint Thesis Validation

**Core validation question:** Is power availability a credible investment constraint for AI infrastructure over the next decade?

**Working conclusion:** Based on current evidence, power availability is a credible investment constraint for AI infrastructure, but severity is regional and scenario-dependent.

**Research positioning:** This page is not a stock recommendation. It is an evidence-weighted research framework for testing whether power availability should be treated as a gating variable in AI infrastructure analysis.

### Reliability Score

5 = primary source with official forecast or empirical dataset  
4 = authoritative research source with transparent scenarios or acknowledged uncertainty  
3 = credible policy or expert source, useful mainly for interpretation or counterargument

### Evidence Type

Forecast = forward-looking demand or capacity estimate  
Historical Dataset = measured historical electricity, load, or queue data  
Grid Operator = ISO/RTO or reliability planning source  
Policy / Government = public agency analysis or policy-relevant research  
Counterargument = uncertainty, downside, or methodological caution  
Industry Research = credible industry research with scenario assumptions

## Evidence Tracker

| Source | Year | Geography | Evidence Type | Metric | Base Case | High Case | Low Case | Time Horizon | Key Finding | Decision Use | Reliability Score | Link |
|---|---:|---|---|---|---|---|---|---|---|---|---:|---|
| IEA, *Energy and AI* | 2025 | Global; U.S., China, Europe detail | Forecast | Data center electricity consumption | Global data centers reach about 945 TWh by 2030 from 415 TWh in 2024; U.S. increase about 240 TWh | Lift-Off sensitivity: data center electricity consumption triples by 2030 | High-efficiency sensitivity: lower than base; exact regional low case not shown in accessible excerpt | 2030; 2035 | Data center electricity demand more than doubles globally by 2030; AI is the most important driver, but data centers remain under 3% of global electricity use. | Establishes the global demand-growth premise while preventing overstatement of systemwide impact. | 5 | [IEA Energy and AI](https://www.iea.org/reports/energy-and-ai/energy-demand-from-ai) |
| IEA, *Energy and AI* Executive Summary | 2025 | Global; U.S. | Forecast / Policy | Share of demand growth; grid bottlenecks | U.S. data centers account for nearly half of U.S. electricity demand growth to 2030 | Not framed as high/low in executive summary | Not framed as high/low in executive summary | 2030 | IEA estimates around 20% of planned data center projects could be at risk of delay if grid risks are not addressed; new transmission in advanced economies can take 4-8 years. | Turns demand growth into an execution-risk variable: schedule, interconnection, and site feasibility. | 5 | [IEA Executive Summary](https://www.iea.org/reports/energy-and-ai/executive-summary) |
| IEA, *Key Questions on Energy and AI* | 2026 | Global | Scenario Analysis | Scenario sensitivity | Base Case: data center consumption more than doubles by 2030 | Lift-Off case: triples by 2030 | High-efficiency case lower than base; driven by better model/chip efficiency | 2030 | IEA explicitly attributes the scenario range to uncertainty in AI uptake, economics, efficiency improvement, and resolution of energy bottlenecks. | Forces the model to evaluate base, upside, and efficiency cases instead of treating one forecast as truth. | 5 | [IEA Key Questions on Energy and AI PDF](https://iea.blob.core.windows.net/assets/3179f7f8-01f6-4dd6-bffa-c9f7b73f1dc9/KeyQuestionsonEnergyandAI.pdf) |
| DOE / LBNL, *2024 United States Data Center Energy Usage Report* | 2024 | United States | Historical Dataset / Forecast | U.S. data center electricity use and share of U.S. electricity | 176 TWh in 2023; 325-580 TWh by 2028; 6.7%-12% of U.S. electricity by 2028 | 580 TWh; 12% of U.S. electricity | 325 TWh; 6.7% of U.S. electricity | 2028 | U.S. data center power use rose from 58 TWh in 2014 to 176 TWh in 2023 and could roughly double or triple by 2028. | Anchors the thesis in measured historical growth before applying forward-looking scenarios. | 5 | [DOE release](https://www.energy.gov/articles/doe-releases-new-report-evaluating-increase-electricity-demand-data-centers) |
| EPRI, *Powering Intelligence 2026* | 2026 | United States; state-level | Industry Research / Scenario Analysis | U.S. data center share of electricity | Medium scenario within 9%-17% national range by 2030 | 17% of U.S. electricity by 2030; 132 GW nominal IT capacity | 9% of U.S. electricity by 2030; 56 GW nominal IT capacity | 2030 | EPRI projects U.S. data centers could consume 9%-17% of U.S. electricity by 2030, up from 4%-5% today; Virginia could rise to 39%-57%. | Stress-tests national and state-level exposure; useful for identifying regions where grid availability becomes a gating variable. | 4 | [EPRI PDF](https://restservice.epri.com/publicattachment/97025) |
| Grid Strategies, *Power Demand Forecasts Revised Up* | 2025 | United States | Forecast / Utility Planning | Utility load forecast growth; data center share | 166 GW of U.S. summer peak load growth by 2030 | Utility forecasts imply roughly 90 GW linked to data centers | Report flags likely overstatement of about 25 GW in data center utility forecasts | 2030 | Data centers account for about 55% of demand growth in utility load forecasts over the next five years. | Separates utility planning signals from realized demand; highlights the need to probability-weight announced load. | 4 | [Grid Strategies 2025 report](https://gridstrategiesllc.com/wp-content/uploads/Grid-Strategies-National-Load-Growth-Report-2025.pdf) |
| Grid Strategies, load-growth report page | 2025 | United States | Forecast Revision | Aggregate national load forecast | 166 GW projected load growth by 2030 | Not separately stated | Prior 2022 forecast was only 24 GW, showing forecast revisions rather than a low scenario | 2030 | The 2025 aggregate national load forecast is six times the 2022 forecast and equivalent to 15 times New York City peak load. | Flags forecast-vintage risk: research should track how fast assumptions are being revised. | 4 | [Grid Strategies summary](https://gridstrategiesllc.com/project/load-growth-forecast/) |
| EIA, *Fossil generation could rise with faster-than-expected growth in data center power demand* | 2026 | United States; PJM/ERCOT emphasis | Government Forecast | U.S. electricity demand growth | U.S. load forecast increases 1.9% in 2026 and 2.5% in 2027 in February STEO | Faster-than-expected data center demand scenario raises fossil generation need if capacity assumptions are unchanged | Historic low-growth comparison: 0.1% annual growth from 2005-2019 | 2026-2027 | U.S. electricity demand has shifted from flat growth to rising demand; EIA identifies data centers as a driver of near-term growth. | Tests whether the AI load thesis is visible in near-term official energy forecasting. | 5 | [EIA Today in Energy](https://www.eia.gov/todayinenergy/detail.php?id=67344) |
| NERC, *2025 Long-Term Reliability Assessment* | 2025 | North America | Reliability / Grid Operator | Resource adequacy and peak demand risk | Industry forecasts show materially higher demand growth and reliability risk | Summer peak demand forecast up 224 GW over 10 years; winter up 246 GW, per NERC release | Not framed as low case | 10 years | NERC warns resource adequacy risks are intensifying as demand growth surges, including AI data centers. | Converts load growth into reliability risk, which is the bridge from macro demand to investable grid constraints. | 5 | [NERC LTRA PDF](https://www.nerc.com/globalassets/our-work/assessments/nerc_ltra_2025.pdf) |
| DOE / LBNL, *Queued Up: 2025 Edition* | 2025 | United States | Historical Dataset / Grid Constraint | Interconnection queue backlog | 1,400 GW generation and 890 GW storage actively seeking interconnection at end-2024 | Over 2,060 GW total generation/storage seeking connection at end-2025 in updated dataset | Only 13% of capacity entering queues from 2000-2019 reached commercial operation by end-2024 | End-2024; end-2025 dataset | Interconnection queues remain large and slow; median time from request to commercial operation exceeded four years for projects built in 2018-2024. | Tests supply-side feasibility: new generation capacity is not useful unless it can connect on time. | 5 | [LBNL Queued Up](https://emp.lbl.gov/queues) |
| PJM, *2026 Load Forecast Report* | 2026 | PJM; Mid-Atlantic/Midwest | Grid Operator Forecast | Peak and energy load forecast | Summer peak grows 3.6% annually for 10 years; net energy grows 5.3% annually | 2046 summer peak reaches 253 GW; 2046 energy reaches 1,667 TWh | Zone-level growth varies widely; some zones near flat | 2036; 2046 | PJM forecasts a 65.7 GW summer peak increase over 10 years and 96.7 GW over 20 years, with data center-heavy zones driving regional divergence. | Identifies PJM as a priority region for deeper screening and secured-power diligence. | 5 | [PJM 2026 Load Forecast PDF](https://www.pjm.com/-/media/DotCom/library/reports-notices/load-forecast/2026-load-report.pdf) |
| EIA, Virginia / Dominion Zone analysis | 2026 | Virginia; PJM Dominion zone | Historical Dataset / Regional Bottleneck | Regional commercial load and peak demand | Dominion summer peak 23,905 MW in 2025; PJM expects 5.4% annual summer peak growth over next 10 years | Winter peak in 2025-26 was 45% above 2019-20 | PJM revised the 10-year Dominion summer growth rate down from 6.3% to 5.4% | 2025-2036 | Virginia commercial electricity sales increased nearly 30 million MWh from 2019 to 2025, largely driven by data centers. | Validates the regional-bottleneck lens: national adequacy does not eliminate local scarcity. | 5 | [EIA Virginia data center analysis](https://www.eia.gov/todayinenergy/detail.php?id=67664) |
| ERCOT, *Long-Term Load Forecast Update* | 2025 | Texas / ERCOT | Grid Operator Forecast / Counterargument | Large-load and data center forecast | TSP-provided forecast shows 77,965 MW of data center growth for 2030 | TSP forecast: 218 GW total demand by 2031 | ERCOT adjusted methodology reduces new data center demand to 49.8% of requested amount and delays ramps by 180 days | 2030-2031 | ERCOT says data centers are the major area of new growth, but its own methodology materially haircuts requested load based on observed project realization. | Distinguishes requested load from bankable load; project probability becomes a decision input. | 5 | [ERCOT forecast update PDF](https://www.ercot.com/files/docs/2025/04/07/8.1-Long-Term-Load-Forecast-Update-2025-2031-and-Methodology-Changes.pdf) |
| CAISO, Large Loads page | 2026 | California ISO | Grid Operator Forecast | Data center load forecast | CEC forecasts data center load in ISO grid to increase by 1.8 GW by 2030 | 4.9 GW increase by 2040 | Not framed as low case | 2030; 2040 | CAISO identifies data centers as the largest large-load use case, but California's quantified near-term data center growth is smaller than PJM/ERCOT hotspots. | Adds a regional control case showing that the constraint is not uniform across all power markets. | 5 | [CAISO Large Loads](https://www.caiso.com/generation-transmission/load/large-loads) |
| Bipartisan Policy Center / Koomey Analytics, *Electricity Demand Growth and Data Centers: A Guide for the Perplexed* | 2025 | United States | Counterargument | Forecast uncertainty | Data centers likely account for up to 25% of expected U.S. load growth through 2030 in BPC follow-up | High-growth claims should be tested against project probability and efficiency assumptions | AI adoption, service demand, and computing efficiency could lower realized demand | 2030 | BPC warns that data center electricity growth is deeply uncertain and that other sources of demand may be larger over the medium to long term. | Prevents thesis creep: high-confidence frameworks should include uncertainty, efficiency, and non-data-center load drivers. | 4 | [BPC report](https://bipartisanpolicy.org/report/electricity-demand-growth-and-data-centers/) |

## Investment-Style Thesis Validation Memo

### 1. Core Question

How should long-term capital evaluate power availability as a constraint on AI infrastructure growth over the next decade?

This page does not yet answer the full capital allocation question. It only tests whether the power-constraint premise is credible enough to anchor the next stage of research across generation, transmission, regulated utilities, data centers, cooling, and fiber.

### 2. Evidence Summary

The evidence supports a meaningful increase in data center electricity demand, especially in the United States. IEA estimates global data center electricity consumption rises from 415 TWh in 2024 to about 945 TWh by 2030 in its Base Case, with the U.S. and China driving nearly 80% of global growth. DOE/LBNL estimates U.S. data center electricity use rose from 58 TWh in 2014 to 176 TWh in 2023 and could reach 325-580 TWh by 2028. EPRI's 2026 scenarios are more aggressive, placing data centers at 9%-17% of U.S. electricity consumption by 2030.

The evidence also supports a grid-delivery constraint, not just a demand-growth story. IEA estimates roughly 20% of planned data center projects could be at risk of delay if grid risks are not addressed. LBNL's interconnection data show a large backlog of generation and storage projects, long queue timelines, and low historical completion rates. Grid Strategies finds that U.S. utility load forecasts now imply 166 GW of summer peak growth by 2030, with data centers linked to roughly 90 GW, or about 55% of forecast growth.

The constraint is regional. PJM, especially the Dominion/Virginia zone, has clear evidence of data center-driven load growth. EIA reports Dominion-zone winter peak load in 2025-26 was 45% above the 2019-20 winter season, while PJM expects 5.4% annual summer peak growth over the next 10 years. ERCOT also shows large data center-driven forecast revisions, but ERCOT's own adjustment methodology reduces requested data center load to 49.8% based on observed realization. CAISO, by contrast, forecasts more moderate ISO-grid data center load growth of 1.8 GW by 2030 and 4.9 GW by 2040.

### 3. What The Evidence Supports

Power availability is a credible investment constraint for AI infrastructure. Multiple authoritative forecasts show rapid data center electricity demand growth. The most important investment issue is not whether the U.S. has enough theoretical generation potential over decades; it is whether specific regions can deliver firm, interconnectable, affordable power on the timeline demanded by AI data center developers.

The evidence supports four underwriting assumptions:

1. Speed-to-power is becoming a competitive advantage for AI infrastructure sites.
2. Transmission, interconnection, transformers, substations, and local grid capacity can be gating factors.
3. Regulated utilities and grid equipment providers may become indirect AI infrastructure beneficiaries.
4. Regional analysis is essential; national averages can hide severe local bottlenecks.

### 4. What Remains Uncertain

Forecast severity remains uncertain. Data center load forecasts can double-count speculative projects, overstate requested capacity, or assume projects energize faster than they actually do. ERCOT's 49.8% realization adjustment is a useful warning that requested load is not the same as realized load.

Efficiency is another major uncertainty. AI chips, model architecture, inference optimization, cooling systems, and workload management can reduce energy per unit of compute. However, efficiency gains may be offset by higher total AI usage, larger model runs, and increased inference demand.

Regional policy and utility rules also remain unsettled. Large-load tariffs, cost allocation, behind-the-meter generation, clean-energy procurement, and interconnection reform could materially affect which projects proceed and which regions become investable.

### 5. Decision Framework

The power constraint should be treated as a research decision variable, not as a settled macro claim. The framework should move from evidence validation to a repeatable decision map:

```text
Question 1: Is power availability a credible constraint?
  If no: deprioritize power-led thesis; monitor demand revisions.
  If yes: continue.

Question 2: Is the region exposed to high load growth or grid bottlenecks?
  If no: classify as lower-priority region; monitor.
  If yes: continue.

Question 3: Is the evidence based on realized load, operator forecast, or speculative request?
  Realized load / operator forecast: higher confidence.
  Speculative request: probability-weight before using.

Question 4: Does the project or company have secured power, interconnection visibility, or utility support?
  If yes: potential research candidate.
  If no: execution-risk flag; avoid or require higher margin of safety.

Question 5: Which part of the value chain benefits from the constraint?
  Generation / transmission / grid equipment / utility capex / data center siting / cooling / fiber.
```

This shifts the project from "which stock should be bought?" to "how should evidence be classified, weighted, and mapped into research decisions?"

### 6. Final Thesis Validation Conclusion

Multiple authoritative forecasts indicate rapid electricity demand growth from AI and data centers. Because generation additions, transmission expansion, interconnection approvals, substations, transformers, and large-load utility processes require long lead times, power availability is a credible constraint for AI infrastructure investment over the next decade.

However, the constraint is not uniform nationally and should not be treated as deterministic. Severity depends on region, project execution, realized AI demand, efficiency improvements, utility planning, interconnection reform, and customer-cost allocation. The validated thesis is therefore:

**Power availability is a credible investment constraint for AI infrastructure, but the severity is regional and scenario-dependent. The next stage should use an evidence-weighted decision framework to evaluate which regions, assets, and value-chain segments have durable advantage from power access, grid deliverability, and speed-to-power.**

## Suggested Repository Structure

```text
AI-Infrastructure-Research/
  01_Thesis_Validation/
  02_Evidence_Database/
  03_Scenario_Analysis/
  04_Decision_Framework/
  05_Company_Screening/
  06_Watchlist/
  07_Weekly_Updates/
  08_Investment_Journal/
```

## Resume Positioning

Built an evidence-weighted research framework for AI infrastructure investing by integrating 15+ primary sources (IEA, DOE/LBNL, PJM, ERCOT, NERC) into a thesis-validation system with source reliability scoring, evidence-type classification, scenario analysis, and decision mapping.

## Research Transition

The thesis has been sufficiently validated to justify further analysis.

The next stage is no longer to determine whether power is a constraint.

Instead, the framework shifts toward identifying:

• where the constraint is concentrated;

• who controls the constrained assets;

• which infrastructure segments benefit;

• and how those observations may influence long-term capital allocation.
