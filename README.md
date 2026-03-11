# IPL-PowerBI-Analytics-Dashboard
Interactive Power BI dashboard analyzing IPL player and team performance from 2020–2025.

# 🏏 IPL Performance Analytics Dashboard (2020–2025)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 📌 Project Overview

An interactive Power BI dashboard analyzing **Indian Premier League (IPL) player and team performance** across six seasons (2020–2025). The project transforms raw cricket data into actionable insights covering batting, bowling, team contributions, and nationality-based performance breakdowns.

> Built to demonstrate how historical cricket data can drive smarter squad strategies and auction decisions for IPL 2026.

---

## 📊 Dashboard Preview

![IPL Performance Analytics Dashboard](./dashboard-preview.png)

---

## 🔢 Key Metrics (2020–2025)

| Metric | Value |
|---|---|
| 🏃 Total Runs | 41K |
| 🎯 Total Wickets | 1,176 |
| 🏆 Top Run Scorer | KL Rahul |
| 🏆 Top Wicket Taker | Mohammed Shami |

---

## 📈 Dashboard Features

| Feature | Description |
|---|---|
| **Interactive Slicers** | Filter by Season, Team, Player, Role, and Nationality |
| **KPI Cards** | Live metrics for Total Runs, Total Wickets, and Top Performers |
| **Total Runs by IPL Season** | Year-on-year run trend across all 6 seasons |
| **Top 15 Run Scorers** | Ranked batting leaderboard across the full dataset |
| **Top 15 Wicket Takers** | Ranked bowling leaderboard across the full dataset |
| **Runs Scored by Team** | Side-by-side franchise run contribution comparison |
| **Indian vs Overseas Contribution** | Donut chart breakdown — Indian: 43.07% · Overseas: 56.93% |

---

## 🗂️ Dataset

The dataset covers IPL player performance data from **2020 to 2025** and includes the following fields:

- Player Name
- Team
- Matches Played
- Runs Scored
- Wickets Taken
- Strike Rate
- Batting Average
- Best Bowling Figures
- Nationality (Indian / Overseas)

---

## 🧠 Key Insights

- **KL Rahul** leads all batsmen in total runs across the 2020–2025 period
- **Mohammed Shami** is the highest wicket-taker in the same timeframe
- **2025** recorded the highest total runs of any season in the dataset
- **Overseas players** account for a slightly higher share of total runs (56.93%) compared to Indian players (43.07%)
- **Royal Challengers Bangalore** leads all franchises in total runs scored by team

---

## 🎯 Strategic Use Cases for IPL 2026

Teams preparing for the 2026 auction cycle can use this dashboard to:

- 🔒 **Retention Planning** — Identify consistent performers worth locking in before auctions
- 🎯 **Auction Targeting** — Spot high-value bowlers or middle-order batsmen by team gaps
- ⚠️ **Dependency Analysis** — Flag over-reliance on individual players and address squad imbalance
- ⚖️ **Squad Composition** — Optimize Indian vs. overseas ratio based on real contribution data

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development and data visualization |
| **DAX** | Custom KPI measures and calculated columns |
| **Data Modeling** | Table relationships and schema design |
| **Microsoft Excel** | Data cleaning, preparation, and source management |

---

## 📁 Repository Structure

```
ipl-performance-analytics/
│
├── 📊 IPL_Dashboard.pbix         # Power BI dashboard file
├── 📂 Dataset/
│   └── ipl_data_2020_2025.xlsx   # Raw dataset
├── 🖼️ dashboard-preview.png      # Dashboard screenshot
└── 📄 README.md                  # Project documentation
```

---

## 🚀 How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/ipl-performance-analytics.git
   ```
2. Open `IPL_Dashboard.pbix` in **Power BI Desktop**
3. If prompted, refresh the data source and point it to `Dataset/ipl_data_2020_2025.xlsx`
4. Use the slicers to explore performance by season, team, player, role, or nationality

---

## 👤 Author

**Raju Kumar S**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/your-username)

---

## 📃 License

This project is open source and available under the [MIT License](LICENSE).
