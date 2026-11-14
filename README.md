FIFA World Cup 2026 Player Performance Dashboard

## Project Overview

The **FIFA World Cup 2026 Player Performance Dashboard** is an interactive data analytics project developed using Microsoft Power BI to analyze and visualize football player and team performance.

The project uses player performance data sourced from Kaggle. Power Query and Microsoft Excel were used for data cleaning, transformation, and validation before developing an interactive dashboard.

The dashboard provides insights into player ratings, team goals, defensive performance, attacking performance, player-of-the-match awards, clutch performance scores, and goalkeeper statistics.

The main objective is to transform raw football performance data into meaningful insights through interactive visualizations and DAX-based KPIs.

##  Project Objectives

- Analyze individual player performance across different teams and positions.
- Evaluate team-level performance using goals and other performance metrics.
- Understand player contributions through ratings and player-of-the-match awards.
- Analyze attacking and defensive performance.
- Compare player performance based on nationality, position, team, and club.
- Build an interactive dashboard to support data-driven performance analysis.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Initial data inspection and validation |
| Power Query | Data cleaning and transformation |
| Power BI Desktop | Dashboard development and visualization |
| DAX | KPI calculations and analytical measures |
| Kaggle | Dataset source |

#  Dataset Information

The dataset was sourced from Kaggle and contains football player and performance-related information.

### Key Dataset Attributes

- Player Name
- Team
- Nationality
- Position
- Club Name
- Jersey Number
- Match ID
- Player Rating
- Goals Team
- Shots on Target
- Fouls Committed
- Clearances
- Player of the Match Awards
- Clutch Performance Score
- Goalkeeper Punches

##  Project Workflow

### 1. Data Collection
- Collected the football player performance dataset from Kaggle.
- Imported the dataset into Microsoft Excel and Power BI.

### 2. Data Cleaning
Used Power Query to prepare the dataset for analysis.

Key activities:
- Checked missing and null values.
- Identified duplicate records.
- Reviewed column data types.
- Standardized data formats.
- Validated player, team, nationality, and position information.

### 3. Data Transformation
- Transformed raw data into an analysis-ready format.
- Organized player, team, nationality, position, and club-level information.
- Prepared relevant columns for KPI calculations and visualizations.

### 4. DAX & KPI Development
Created DAX-based measures to calculate important performance indicators.

### 5. Dashboard Development
Designed an interactive Power BI dashboard using KPI cards, charts, and slicers to explore player and team performance.

## 📊 Key Performance Indicators (KPIs)

The dashboard highlights the following performance metrics:

| KPI | Dashboard Value |
|---|---:|
| Total Player Ratings | 198.45K |
| Total Team Goals | 73K |
| Total Clearances | 44K |
| Total Fouls Committed | 23K |
| Total Shots on Target | 3K |
| Player of the Match Awards | 2K |
| Clutch Performance Score | 3.03M |
| Goalkeeper Punches | 1K |

*Note: These values represent the aggregated metrics displayed in the dashboard based on the dataset.*

##  Dashboard Visualizations

The dashboard includes the following visualizations:

1. **KPI Cards:** Display key player and team performance indicators.
2. **Jersey Number by Team:** Compares the sum of jersey numbers across teams.
3. **Match Count by Position:** Analyzes match records across defenders, midfielders, forwards, and goalkeepers.
4. **Player of the Match Awards by Day:** Tracks player recognition across different days.
5. **Clutch Performance by Club:** Compares clutch performance scores across clubs.
6. **Nationality and Shots Analysis:** Explores nationality distribution and shots-related metrics.
7. **Player and Nationality Filters:** Allows users to explore individual players and nationality-based information.

##  Interactive Dashboard Features

- Team-level performance analysis.
- Player-level performance filtering.
- Nationality-based exploration.
- Position-wise performance comparison.
- Club-level performance analysis.
- Interactive slicers and filters.
- Multiple KPI cards for quick performance tracking.

##  Key Analytical Insights

The dashboard helps explore:

- Overall player ratings and performance distribution.
- Team-level goal contributions.
- Defensive contributions through clearances.
- Fouls committed across player records.
- Attacking performance through shots on target.
- Player recognition through player-of-the-match awards.
- Club-level clutch performance comparisons.
- Goalkeeper contributions through punches.

##  Future Enhancements

- Develop player performance ranking based on multiple KPIs.
- Introduce player comparison functionality.
- Build team performance ranking dashboards.
- Apply Machine Learning to predict player performance.
- Develop player performance scoring models.
- Integrate real-time football statistics through APIs.
- Create advanced player performance insights using AI.

##  Project Structure

```text
FIFA-World-Cup-2026-Player-Performance-Dashboard/
│
├── Dataset/
│   └── fifa_player_performance.csv
│
├── Dashboard/
│   └── FIFA_World_Cup_2026.pbix
│
├── Screenshots/
│   └── dashboard_preview.png
│
├── Documentation/
│   └── Project_Report.pdf
│
└── README.md
```

*Replace the example filenames with your actual uploaded files.*

##  How to Run the Project

1. Clone or download this repository.
2. Download and install Microsoft Power BI Desktop.
3. Open the `.pbix` file using Power BI Desktop.
4. If required, update the dataset source path.
5. Refresh the data.
6. Explore the dashboard using the available slicers and filters.

##  Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Validation
- Exploratory Data Analysis
- Microsoft Excel
- Power Query
- Power BI
- DAX Measures
- KPI Development
- Data Visualization
- Analytical Thinking
- Interactive Dashboard Development

##  Author

**Anjani**

Aspiring Data Analyst | Python | SQL | Excel | Power BI | Data Analytics

##  Acknowledgment

Dataset sourced from Kaggle.

This project was developed for learning and demonstrating practical data analytics, data visualization, and business intelligence skills.

If you find this project useful, feel free to ⭐ the repository!
