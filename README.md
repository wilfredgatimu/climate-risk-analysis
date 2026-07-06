# climate-risk-analysis: Chattogram, Bangladesh 2019-2024
Power BI + SQL analysis of 5-year Chattogram, Bangladesh climate data. Identified 40% increase in extreme rain and 3-month flood risk window. Built for infrastructure/ops risk planning.
**Power BI + SQL | Business Impact: Shifted $M infrastructure planning from "averages" to "peak risk"**

### Business Problem
Construction and logistics firms in Chattogram budget using 5-year rainfall averages. But climate data shows extreme rain events increased 40% since 2019, causing unplanned delays and drainage failures.

### Key Findings
1. **70% of annual flood risk occurs in Jun-Aug Monsoon** — Only 3 months drive majority of delays
2. **Extreme rain days +40% vs 10-year avg** — Storms are fewer but more intense  
3. **50% of workdays face weather delays** — 24.5% from rain/heavy rain alone
4. **Wind risk peaks days 1, 13, 30 monthly** — Crane/roofing work should avoid these dates

### Business Recommendations
1. Plan for peaks, not averages. Increase drainage budget 30% for Jun-Aug.
2. Shift outdoor construction to Dry Season Nov-Apr to cut delay risk 50%.
3. Avoid high-wind dates for lifts → saves 20+ high-risk days/year.

### Tech Stack
- **SQL**: Date tables, season binning, rain category classification
- **Power BI**: YoY analysis, heatmaps, treemaps, KPI cards, executive summary
- **DAX**: `CALCULATE`, `DIVIDE`, time intelligence, dynamic risk %

### Dashboard Pages
