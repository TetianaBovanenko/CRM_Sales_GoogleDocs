# CRM Sales Dashboard Project

## Project Overview
This [project](https://docs.google.com/spreadsheets/d/1uDxGMGDMEmVSMjdTo3TLMLGeyp0d2eWd4KYxz6WkMjY/edit?usp=sharing) involves building a dynamic CRM Sales Dashboard in Google Sheets to analyze and visualize sales performance. The dashboard enables sales teams to track quarterly trends, evaluate agent performance, and identify opportunities for growth. It leverages raw data from the sales pipeline and sales team datasets, which were cleaned, joined, and transformed into actionable insights.

![CRM Sales Logo](https://github.com/TetianaBovanenko/CRM_Sales_GoogleSheets/blob/main/CRM%20Sales%20Dashboard.png?raw=true)

---

## Data Preparation and Integration
The project began with an exploration and quality assessment of the sales pipeline and sales team datasets. Missing values were identified and addressed, and the two datasets were joined to incorporate additional contextual fields such as `manager` and `regional_office`. This enriched the sales pipeline data, allowing for more detailed analysis and segmentation.

---

## Data Analysis and Insights
Pivot tables were used to summarize and analyze the sales data. Key insights included:
- The number of opportunities won each quarter, broken down by individual sales agents.
- A comparison of won vs. lost opportunities, providing a percentage breakdown for each quarter.
- Sales agent performance trends, ranked in descending order of opportunities won.
To enhance readability and comparison, quarters were formatted as pivot table columns, with the most recent quarter displayed first.

---

## Dashboard Development
The cleaned and analyzed data was visualized in an interactive dashboard, which includes:
- **Scorecard Chart:** Displays the number of opportunities won in the most recent quarter (2017-Q4) compared to the previous quarter (2017-Q3).
- **Pie Chart:** Highlights the percentage of deals won vs. lost in the most recent quarter.
- **Bar Chart:** Visualizes opportunities won by each sales agent for the most recent quarter.
- **Slicers:** Enable filtering of data by `regional_office` and `manager` to allow for tailored analysis.
The visuals were arranged into a structured dashboard with a title summarizing the data's purpose.

---

## Key Features
- **Dynamic Visualizations:** Users can track quarterly performance trends and agent rankings.
- **Interactive Filtering:** Slicers allow users to drill down into specific regions or managers for deeper insights.
- **Comparative Analysis:** Highlights changes in performance across quarters for decision-making.

---

## Files Included
- `sales_pipeline.csv`: Raw sales pipeline data.
- `sales_teams.csv`: Sales team details including managers and regional offices.
- Google Sheets dashboard (link provided in the repository).

---

## Future Enhancements
- Automate data updates using Google Sheets App Scripts to maintain a live dashboard.
- Expand the analysis to include revenue and profitability metrics.
- Migrate the dashboard to advanced visualization tools like Google Data Studio or Power BI for enhanced reporting capabilities.
