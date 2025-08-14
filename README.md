# Tableau-Project: Pre & Post Economic Impact of COVID-19
Five curated storylines showing how COVID-19 shifted development, policy, health outcomes, and labor markets—by region and income group—using LODs, correlation, z-score outliering, and parameterized thresholds.

Complexity:
- Analytics: FIXED LODs (means, stdevs, latest-by-country), z-scores for outliers, CORR() for GDP↔HDI, ratio calcs (Death/Case), parameterized wealth buckets.
- Interactivity: parameter controls (GDPpc thresholds), click-to-filter, drill-to-detail sheets, map drilldowns.
- Modeling: Federated connection across 4 flat files (CSV/Excel) with relationships on Country, Date (Year/Month), Income Group.

Chart Types Used: 
Scatter with trend, dual-axis line, clustered/stacked bar, histogram/distribution, filled map, cohort-style monthly trend, Gantt timeline, KPI tiles

Data Sources & “Queries”: 
- Connections (federated across flat files)
- Relationship keys (semantic model)
- Joins through Tableau relationships over CSVs

Data Transformation Tools:
- Python (pandas)
- Excel 
