# ICC Men’s T20 World Cup 2026 – Match Analytics

## Project Overview
This project presents an interactive Power BI dashboard that provides a high-level
analytical overview of the ICC Men’s T20 World Cup 2026 matches.

The dashboard focuses on match outcomes, team performance, tournament stages,
venue impact, and key performance indicators to support data-driven insights
for cricket analytics and reporting.

---

## Dashboard Objectives
- Analyze overall tournament performance
- Identify best-performing teams
- Compare match outcomes across stages
- Track win percentage and standings
- Highlight venue and pitch impact on matches

---

## Key KPIs
- Total Matches Played
- Best Performing Team
- Best Team Win Percentage
- Highest Match Total
- Stage-wise Team Performance

---

## Tech Stack
- Power BI Desktop
- DAX (Measures & Calculated Columns)
- Power Query (Data Transformation)
- Excel / CSV (Data Source)

---

## Data Model Overview
The dashboard follows a **star/snowflake schema** for efficient analysis.

### Dimension Tables
- **Dim_Team** – Team details
- **Dim_Date** – Match date attributes
- **Dim_Stage** – Tournament stages (Group, Super 8, Semi Final, Final)
- **Dim_Venue** – Match venues and pitch types

### Fact Table
- **Fact_Matches**
  - Match results
  - Team performance metrics
  - Wins, losses, points
  - Match totals and standings

A bridge table is used to manage team–match relationships.

---

## Power BI Techniques Used
- Calculated columns for match metrics
- DAX measures for KPIs and rankings
- Conditional formatting for standings
- Dynamic filtering by stage and venue
- Buttons for page navigation
- Slicers for interactive analysis
- Image and layout formatting for storytelling
- Performance-optimized data modeling

---

## Dashboard Views

### Overview Page
Provides tournament-level insights including total matches,
best team, win percentage, and highest match total.

![Overview](Resources/Overview.png)

---

### Stage-wise Analysis
Users can analyze team performance across different stages:
- Group Stage
- Super 8
- Semi Final
- Final

![Stage Analysis](Resources/SemiFinal.png)

---

### Team Performance
Displays standings, wins, losses, points, and win percentage
for each team using tabular and KPI visuals.

![Team Performance](Resources/Final.png)

---

## Insights Generated
- Identified the best-performing team across stages
- Compared win percentages across teams
- Analyzed high-scoring matches
- Observed performance consistency in knockout stages

---

## Project Outcome
This dashboard enables:
- Clear visibility into tournament performance
- Faster comparison of teams and stages
- Interactive exploration of match data
- Strong storytelling through visuals and KPIs

The project strengthened my skills in Power BI data modeling,
DAX calculations, and analytical dashboard design.
