<!-- Banner -->
<p align="center">
  <img src="banner.png" alt="Margins of Glory Banner" width="100%">
</p>

<p align="center">
  <img src="images/banner.png" alt="Margins of Glory" width="100%">
</p>

<h1 align="center">⚽ Margins of Glory</h1>
<p align="center">
  <i>Advanced Football Analytics — Where matches are won and lost in the tiniest margins.</i>
</p>

---

## 🚀 Live Demo  
📊 [**View Full Interactive Dashboard on Tableau Public**](https://public.tableau.com/views/MarginsofGlory/MARGINSOFGLORY?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  

---

## ✨ Key Features  
- ⚡ **Clutch xG** — Performance under pressure (75+ mins, close scorelines)  
- 📈 **xG Overperformance** — Detecting teams punching above their weight  
- 🎯 **Finishing Efficiency** — Measuring clinical edge with Goals/xG  
- 🖌 **Creativity vs Finishing Map** — Playmaking vs goalscoring tendencies  
- 📊 **Game Dynamics** — Momentum shifts & fine margins  

---

## 📂 Project Structure
Margins-of-Glory/
├── output data/
│ ├── AllTeams_Cleaned.csv
│ ├── AllTeams_FeatureEngineering.csv
├── Football_Analytics_Feature_Engineering.ipynb
├── Margins of Glory.twbx
├── images/
│ ├── banner.png
│ ├── FineLine.png
│ ├── GameDynamics.png
├── README.md
└── requirements.txt

---

## 🖼 Dashboard Previews  

| Fine Line Analysis | Game Dynamics |
|--------------------|---------------|
| ![Fine Line](images/FineLine.png) | ![Game Dynamics](images/GameDynamics.png) |

---

## ⚙️ Quick Start

### View Only
No setup — just click the Tableau Public link above.

### Local Setup
```bash
# Clone the repository
git clone https://github.com/USERNAME/margins-of-glory.git
cd margins-of-glory

# Install Python dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Football_Analytics_Feature_Engineering.ipynb
