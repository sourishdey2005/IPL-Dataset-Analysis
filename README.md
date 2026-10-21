# 🏏 Indian Premier League (IPL) Comprehensive Analysis Dashboard (2008–2018)

![Dashboard Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Tool](https://img.shields.io/badge/Tool-Microsoft_Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Dataset Coverage](https://img.shields.io/badge/Coverage-2008--2018-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

An interactive, end-to-end analytical dashboard built in **Microsoft Excel** to evaluate franchise performance, match dynamics, venue trends, and individual player impacts across 11 seasons of the Indian Premier League (2008–2018).

---

## 📌 Project Overview

The objective of this project is to transform raw, multi-season IPL match data into an executive-ready business intelligence dashboard. Utilizing structured Excel tables, advanced dynamic lookup models, PivotTables, custom KPI card visual architecture, and synchronized slicers, this dashboard provides cricket enthusiasts and sports analysts with deep exploratory capabilities.

---

## 🖥️ Dashboard Preview

![IPL Analysis Dashboard](dashboard-preview.png)

---

## 🚀 Key Features & Analytical Insights

### 1. Dynamic Tournament KPI Ribbon
* **Interactive Year Slicer:** Single-click navigation through every season from `IPL-2008` to `IPL-2018`.
* **Formula-Driven KPI Shape Containers:**
  * **Season:** Selected tournament edition.
  * **Champion (Winner):** Formula-driven franchise title attribution.
  * **Runner-Up:** Final match runner-up team.
  * **Player of the Match (Final):** Top performer in the championship final.
  * **Player of the Series:** MVP / tournament player accolade recipient.

### 2. Bat First vs. Field First Performance (`Matches Won by Team`)
* Stacked bar breakdown analyzing team victories relative to setting a target vs. chasing.
* Highlights franchise strategic strengths (e.g., Chennai Super Kings' dominant win rate when batting first vs. Mumbai Indians' balanced record).

### 3. Toss Impact Evaluation (`Toss Decision Based on Winning %`)
* Donut visual showing outcome probabilities tied to the toss.
* Demonstrates the overall tournament shift toward fielding first (**65%**) versus batting first (**35%**).

### 4. Venue Analysis (`Top 12 Venues by Match Volume & Win Dynamics`)
* Dual-axis horizontal bar representation assessing pitch bias across major stadiums (e.g., Eden Gardens, Wankhede Stadium, M Chinnaswamy Stadium, Feroz Shah Kotla).
* Compares defending vs. chasing success rates across distinctive playing grounds.

### 5. Championship Treemap (`Title Winners Distribution`)
* Hierarchical block visualization illustrating historic dominance across tournament champions, including:
  * **Chennai Super Kings** (3 Titles)
  * **Mumbai Indians** (3 Titles)
  * **Kolkata Knight Riders** (2 Titles)
  * **Deccan Chargers** (1 Title)
  * **Sunrisers Hyderabad** (1 Title)
  * **Rajasthan Royals** (1 Title)

### 6. Individual Accolades (`Top 10 Man of the Match (MoM) Winners`)
* Frequency distribution identifying players with the highest match-winning impacts (featuring standouts such as Chris Gayle, AB de Villiers, Suresh Raina, and Shane Watson).

---

## 🛠️ Technical Stack & Excel Concepts Used

| Category | Techniques & Functions Applied |
| :--- | :--- |
| **Data Cleaning & Prep** | Data normalization, Flash Fill, removing whitespace, duplicate checks |
| **Formulas & Functions** | `VLOOKUP`, `XLOOKUP`, `INDEX / MATCH`, structured table references (`Table36[...]`), `IFNA` error handling |
| **Data Modeling** | PivotTables, PivotCharts, customized calculation fields |
| **UI / UX Design** | Custom vector card containers, grouped UI components, hidden gridlines/headers for an app-like interface |
| **Interactivity** | Synchronized Slicers with dynamic timeline bindings and protected card anchoring |

---

## 📂 Repository Structure

```text
ipl-analysis-dashboard/
│
├── README.md                      # Comprehensive project documentation
├── dashboard-preview.png          # High-resolution dashboard screenshot
├── IPL_Dataset_Analysis.xlsx      # Complete interactive Excel dashboard workbook
│
└── data/
    └── IPL_Matches_2008_2018.csv  # Raw match-level dataset
```

---

## ⚙️ How to Use & Explore

1. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/your-username/ipl-analysis-dashboard.git
   ```
2. **Open the Workbook:**
   * Launch `IPL_Dataset_Analysis.xlsx` using **Microsoft Excel 2016 or newer** (Excel 365 recommended for best visual rendering).
3. **Interact with the Dashboard:**
   * Click any season on the **Sesion Slicer** (`IPL-2008` to `IPL-2018`) at the top to dynamically update the KPI cards and match breakdowns.
   * Hover over charts and Treemap tiles to view granular data points.

---

## 📈 Future Enhancements

- [ ] Incorporate ball-by-ball delivery statistics for strike-rate and economy analytics.
- [ ] Implement an automated Power Query pipeline for seamless season-over-season data refreshes.
- [ ] Migrate analytical models to Power BI / Tableau for public interactive web hosting.

---

## 👤 Author

* **Your Name**
* **LinkedIn:** [linkedin.com/in/yourprofile](https://linkedin.com)
* **GitHub:** [@yourusername](https://github.com)
* **Portfolio:** [yourportfolio.com](https://yourportfolio.com)

---

*⭐️ If you find this project useful for learning Excel data modeling and dashboard UI design, please consider giving this repository a star!*
