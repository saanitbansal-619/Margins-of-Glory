<!-- PROJECT BANNER -->
<p align="center">
  <img src="images/banner.png" alt="Margins of Glory Banner" width="100%">
</p>

<!-- TITLE -->
<h1 align="center">MARGINS OF GLORY ⚽📊</h1>
<p align="center">
  <em>A Football (Soccer) Analytics Project — Blending Data Science, Match Dynamics & Performance Insights</em>
</p>

<!-- BADGES -->
<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"></a>
  <a href="https://jupyter.org/"><img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter"></a>
  <a href="https://www.tableau.com/"><img src="https://img.shields.io/badge/Tableau-Data%20Viz-005B96?style=for-the-badge&logo=tableau"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"></a>
</p>

---

## 📌 Overview
**Margins of Glory** is a comprehensive football analytics project built from scratch, designed to uncover *hidden performance edges* that decide matches.

We go **beyond basic stats** like goals, assists, or possession. Instead, we engineer advanced metrics like:

- **Clutch xG** → Expected goals in critical match moments.
- **xG Overperformance** → How clinical a team is compared to the quality of chances.
- **Finishing Efficiency** → Ratio of goals scored vs. xG created.
- **Game Momentum Analysis** → Flow of performance during a match.
- **Creativity vs. Finishing Matrix** → Profiling team styles.

This project **merges data science with sports intelligence**, producing insights fit for clubs, analysts, and passionate fans alike.

---

## 🎯 Objectives
1. **Clean & Structure Data** → Transform raw match data into analysis-ready formats.
2. **Engineer Advanced Metrics** → Quantify game-winning edges with custom KPIs.
3. **Visualize Insights** → Use Tableau dashboards for interactive storytelling.
4. **Build Reusable Framework** → So future seasons or leagues can be plugged in easily.

---

## 📂 Project Structure
Margins-of-Glory/
│── output data/
│ ├── AllTeams_Cleaned.csv
│ ├── AllTeams_FeatureEngineering.csv
│
│── Football_Analytics_Feature_Engineering.ipynb
│── Margins of Glory.twbx
│
│── images/
│ ├── banner.png
│ ├── FineLine.png
│ ├── GameDynamics.png
│
│── README.md
│── requirements.txt


---

## 🔍 Data & Methodology

### 1️⃣ Data Cleaning
- Removed missing values, inconsistent naming conventions.
- Standardized metrics for uniform comparison.
- Aggregated team-level performance from match-level data.

### 2️⃣ Feature Engineering
Created **custom metrics**:
- `Clutch_xG` → xG during last 15 mins when score is level or within 1 goal.
- `Finishing_Efficiency` → Goals Scored / xG.
- `Creativity_Score` → Progressive passes + Key passes weighted.
- `xG_Overperformance` → (Goals – xG) / xG.

### 3️⃣ Visualization
- **Tableau dashboards** for match flow, team styles, and league-wide trends.
- Comparative scatter plots: Creativity vs Finishing, Momentum timelines.

---

## 📊 Key Insights
- **Clinical Finishing** correlates strongly with league position in tight leagues.
- Some mid-table teams create massive chances but lack finishing precision.
- Momentum shifts often occur after substitutions — crucial for tactical analysis.
- Clutch xG leaders often overperform in knockout competitions.

---

## 🖥️ Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/Margins-of-Glory.git
cd Margins-of-Glory

python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

pip install -r requirements.txt

jupyter notebook Football_Analytics_Feature_Engineering.ipynb

