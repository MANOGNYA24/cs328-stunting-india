# Childhood Stunting in India
 
**CS 328 Writing Assignment | IIT Gandhinagar**
 
**Team:** Akshit Chhabra | Akul Gupta | D A S K R Manognya | Saksham Chourasia
 
**Live submission:** https://teampandas-cs328-writing-assignment.netlify.app/ 
 
---
 
## Overview
 
Stunting (low height-for-age among children under 5) is one of the clearest markers of chronic nutritional deprivation. This analysis studies childhood stunting in India at two levels:
 
1. **National context** using World Bank indicators over time
2. **State-level variation** using NFHS-5 state factsheet data
We test three hypotheses about which state-level factors (sanitation, female literacy, household prosperity) are associated with stunting, build a multivariable regression model, identify outlier states, and analyse change over time between NFHS-4 and NFHS-5.
 
---
 
## Files
 
| File | Description |
|---|---|
| `TeamPandas_IDS_WritingAssignment.ipynb` | Main analysis notebook |
| `nfhs5_state_data.csv` | NFHS-5 state-level factsheet data |
| `india_state.geojson` | India state boundaries for choropleth maps |
| `API_SH.STA.STNT.ZS_*.csv` | World Bank: stunting rate (India) |
| `API_SH.STA.ORTH_*.csv` | World Bank: ORS treatment rate (India) |
| `API_SH.STA.BASS.ZS_*.csv` | World Bank: access to improved sanitation (India) |
| `API_SE.ADT.LITR.FE.ZS_*.csv` | World Bank: adult female literacy rate (India) |
 
---
 
## How to Run
 
**1. Clone the repo**
```
git clone https://github.com/MANOGNYA24/cs328-stunting-india.git
cd cs328-stunting-india
```
 
**2. Install dependencies**
```
pip install numpy pandas matplotlib scipy statsmodels geopandas plotly
```
 
**3. Open the notebook**
```
jupyter notebook TeamPandas_IDS_WritingAssignment.ipynb
```
 
**4. Run all cells**  
 
---
 
## Data Sources

- [World Bank Open Data](https://data.worldbank.org/) — national indicators (stunting, ORS, sanitation, literacy)
- [Kaggle — NFHS-5 State Data](https://www.kaggle.com/) — state-level stunting and predictor variables
- [geohacker/india on GitHub](https://raw.githubusercontent.com/geohacker/india/master/state/india_state.geojson) — India state boundaries GeoJSON
