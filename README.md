# Tableau-Project: Pre & Post Economic Impact of COVID-19
Five curated storylines showing how COVID-19 shifted development, policy, health outcomes, and labor markets by region and income group using LODs, correlation, z-score outliering, and parameterized thresholds.

Complexity:
- Analytics: FIXED LODs (means, stdevs, latest-by-country), z-scores for outliers, CORR() for GDP↔HDI, ratio calcs (Death/Case), parameterized wealth buckets.
- Interactivity: parameter controls (GDPpc thresholds), click-to-filter, drill-to-detail sheets, map drilldowns.
- Modeling: Federated connection across 4 flat files (CSV/Excel) with relationships on Country, Date (Year/Month), Income Group.

Stories & Dashboards:
- Development vs Human Development — 2019→2020 shifts, outliers
Dashboards: Question1_Part1 → Sheets: Correlation B/W GDP vs HDI, GDP Per Capita Vs HDI_2019/2020, HDI Components by Country, Outliers
- Regional Impact & Health Burden — GDP/HDI vs cases/deaths by region
Dashboards: Question1_Part2a → Sheets: Region_GDP_HDI, Region_cases_deaths
- Policy & Stringency — Health vs Non-Health measures; Stringency Index over time
Dashboards: Question1_Part2b → Sheets: H & NH, H & NH2, SI overtime
- Fatality vs Wealth — Death/Case ratios by income tier; distributions & trends
Dashboards: Question2_Part 1a, Question2_Part 1b, Question2_Part 2 → Sheets: Death/Case Ratio Exploration, Death/Case Ratio By Wealth Index, Total Deaths Distribution by Wealth Index, Monthly Trend in Cases vs Deaths, Regional Comparison, Death/Case Ratio Across the World, Country Demographics
- Labor Markets — Unemployment vs GDPpc; monthly timelines & geography
Dashboard: Question3 → Sheets: Gdp per capita vs Unemployment Rate, Trend of 2020 Monthly Unemployment Rate vs GDP per Capita, Gantt Correlation, Map

Chart Types Used: 
- Scatter with trend
- Dual-axis line
- Clustered/stacked bar
- Histogram/distribution
- Filled map
- Ccohort-style monthly trend
- Gantt timeline
- KPI tiles

Data Sources & “Queries”: 
- Connections (federated across flat files)
- Relationship keys (semantic model)
- Joins through Tableau relationships over CSVs

Data Transformation Tools:
- Python (pandas)
- Excel 
