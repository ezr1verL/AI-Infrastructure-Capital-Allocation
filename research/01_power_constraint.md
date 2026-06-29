# AI Infrastructure Capital Allocation Research Framework

## Module 1: Power Constraint Thesis Validation

**Investment research question:** How should long-term investors evaluate capital allocation across the AI infrastructure value chain if power availability becomes a binding constraint on deployment?

**Validation question:** Is the power-constraint thesis sufficiently supported by current evidence to justify further investment research?

**Working conclusion:** Current evidence suggests that power availability should be treated as a credible investment constraint for AI infrastructure. However, the severity of that constraint is regional, scenario-dependent, and subject to meaningful execution uncertainty.

**Research positioning:** This module is not intended to provide investment recommendations. Instead, it evaluates whether the underlying thesis is sufficiently supported to justify further research into regional power markets, infrastructure value chains, and long-term capital allocation.

### Reliability Score

**5** = Primary source with official forecasts, empirical datasets, or grid-operator planning documents

**4** = Authoritative research with transparent methodology, scenario assumptions, or acknowledged uncertainty

**3** = Credible policy, industry, or expert analysis used primarily for interpretation, context, or counterarguments

### Evidence Type

**Forecast** — Forward-looking demand, capacity, or planning projections.

**Historical Dataset** — Measured electricity, load, generation, or interconnection data.

**Grid Operator** — ISO/RTO planning, reliability, or operational publications.

**Policy / Government** — Public agency research or policy-related analysis.

**Counterargument** — Evidence highlighting uncertainty, downside scenarios, or methodological limitations.

**Industry Research** — Credible third-party research with transparent assumptions.


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

## Research Note

### 1. Investment Research Question

**How should long-term capital allocation across the AI infrastructure value chain change if power availability becomes a binding deployment constraint?**

This module does not attempt to answer that question directly. Instead, it evaluates whether the underlying power-constraint thesis is sufficiently supported to justify further investment research.

If the thesis is validated, subsequent modules examine where constraints emerge, why they differ across regions, which infrastructure segments are most exposed, and how those findings may influence long-term capital allocation.

---

### 2. Evidence Summary

Across the available evidence, one pattern appears consistently. Electricity demand associated with AI infrastructure is expected to increase materially over the remainder of the decade, even though individual forecasts differ in pace, timing, and ultimate scale.

The strongest evidence comes from IEA, DOE/LBNL, EPRI, and NERC. Together, these sources suggest that U.S. data center electricity consumption is likely to increase materially over the remainder of the decade, although the magnitude varies across scenarios. Rather than relying on a single forecast, this framework treats multiple scenario ranges as inputs to the investment thesis.

More importantly, the investment debate is gradually shifting away from electricity demand itself. The more relevant question is whether reliable power can be delivered where and when new AI infrastructure is being built.

Regional differences are becoming increasingly important. The evidence consistently points to regional variation. PJM currently shows the strongest concentration of AI-related electricity demand, particularly in Northern Virginia. ERCOT exhibits rapid projected load growth but applies significant adjustments to requested large-load additions based on observed project realization. CAISO presents a useful comparison because its planning framework incorporates large-load growth differently and currently projects more moderate near-term demand.

Taken together, the evidence supports continued investigation into regional power constraints rather than a single national conclusion.

---

### 3. What the Evidence Supports

Several observations emerge consistently from the available evidence.

**First**, speed-to-power is becoming an increasingly important competitive factor for AI infrastructure deployment.

**Second**, transmission availability, interconnection timelines, substations, transformers, and local grid capacity may become binding constraints even where aggregate generation appears sufficient.

**Third**, if power availability increasingly determines where AI infrastructure can be deployed, assets that enable faster access to reliable power may deserve greater research attention than assets that simply benefit from higher compute demand.

**Finally**, national electricity forecasts provide useful context, but investment analysis is more likely to depend on regional conditions, utility practices, and localized infrastructure constraints than on national averages alone.

### 4. What Remains Uncertain

Although the overall thesis is supported, several sources of uncertainty remain and are likely to influence future investment implications.

First, the ultimate scale of electricity demand remains uncertain. Forecasts may overstate realized demand by including speculative projects, double-counting announced developments, or assuming faster project execution than ultimately occurs. ERCOT's adjustment methodology—reducing requested large-load demand based on observed realization rates—illustrates why announced capacity should not automatically be treated as firm demand.

Second, improvements in AI efficiency could materially alter long-term electricity consumption. Advances in semiconductor design, model architecture, inference optimization, cooling technologies, and workload management may reduce energy intensity. At the same time, those efficiency gains could be offset by broader AI adoption, larger models, and higher inference volumes. The net effect remains uncertain.

Finally, regional policy and utility practices continue to evolve. Large-load tariffs, interconnection reform, cost-allocation rules, behind-the-meter generation, and utility planning processes may significantly influence where new AI infrastructure can be deployed and which regions ultimately attract investment.

These uncertainties do not invalidate the thesis. Instead, they reinforce why regional analysis and continuous evidence updates remain central to the research framework.

---

### 5. Research Decision Framework

At this stage, power availability should be treated as a research variable rather than an established investment conclusion.

The purpose of this module is not to determine which companies or assets should outperform. Instead, it establishes a repeatable process for evaluating whether power availability is likely to become a meaningful driver of infrastructure investment.

```text
Validate Thesis
        ↓
Assess Regional Constraints
        ↓
Identify Constraint Drivers
        ↓
Map Value Chain Exposure
        ↓
Evaluate Public Equity Exposure
        ↓
Develop Capital Allocation Framework
```

This framework shifts the research process from validating a macro thesis toward evaluating where evidence is strongest, how constraints propagate through the infrastructure value chain, and how those observations may eventually influence long-term capital allocation.

---

### 6. Final Thesis Validation Conclusion

The evidence reviewed in this module supports one central conclusion: power availability should be treated as a credible investment constraint for AI infrastructure over the coming decade.

This conclusion does not imply that every region faces the same level of risk or that every announced project will ultimately be developed. Instead, the available evidence consistently indicates that power availability is becoming an increasingly important factor in determining where AI infrastructure can be deployed, how quickly projects can proceed, and which infrastructure assets may become strategically important.

The thesis is therefore validated, with an important qualification: **power availability is a regional and scenario-dependent constraint rather than a uniform national shortage.**

With the underlying premise established, the research can now shift from validating **whether** the constraint exists to understanding **where** it is most significant, **why** it emerges, and **how** those differences may ultimately influence long-term capital allocation across the AI infrastructure value chain.

Validation of the thesis does not establish an investment view.

Instead, it establishes that power availability should be incorporated as an explicit analytical variable in subsequent capital allocation research.


