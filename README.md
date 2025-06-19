# Virginia-Datathon-2025
Data-driven analysis to identify and prioritize Virginia’s most dangerous roads using crash, transit, and infrastructure data with geospatial clustering, predictive scoring, and interactive Folium maps.
# 📊 Datathon 2025 – Data-Driven Road Safety Strategy for Virginia

**Team Name:** Neural Nexus  
**Role:** Data Analyst – Shreya Mishra  
**Project Type:** Geospatial Analysis, Predictive Modeling, Visualization  
**Tools:** Python, Pandas, GeoPandas, Seaborn, Matplotlib, Scikit-learn, Folium

---

## 🧠 Objective

To identify and target the most dangerous 8% of Virginia's roads using a combination of crash severity, infrastructure investment, and transit accessibility. The aim was to generate actionable insights for improving public safety and optimizing state transportation investments.

---

## 🚦 Problem Statement

> *"How can we leverage data to reduce traffic fatalities and improve transit access in Virginia’s underserved and high-risk regions?"*

---

## 🔍 Key Tasks & Methodology

### 📌 1. Data Integration & Cleaning
- Merged crash reports, infrastructure investments, and GTFS transit datasets.
- Cleaned and standardized records across multiple years and formats.

### 🗺️ 2. Geospatial Analysis
- Mapped crash clusters using **Folium** and **GeoPandas**.
- Created heatmaps to detect underserved but high-risk zones.

### 📈 3. Trend Analysis
- Analyzed year-over-year fatality shifts by vehicle type (1994–2022).
- Visualized fatality patterns using **Seaborn** and **Matplotlib**.

### 🧮 4. Predictive Risk Modeling
- Built a composite risk score using crash frequency, access mismatch, and funding data.
- Used scoring to prioritize high-impact zones for potential interventions.

---

## 💡 Key Outputs

- Interactive Folium map showing crash clusters and risk zones
- Line and bar plots of fatality trends by vehicle type
- Prioritized intervention zones based on custom risk scoring model
- Final PDF presentation summarizing insights and recommendations

---

## 📁 Repository Contents

| File                             | Description                                   |
|----------------------------------|-----------------------------------------------|
| `Shreya_Datathon_2025.ipynb`     | Main analysis & visualization notebook        |
| `Shreya_Datathon_v1_1.ipynb`    | Supplemental EDA and clustering               |
| `Datathon_2025.pdf`              | Final report/presentation                     |

---

## 🧰 Tools & Libraries Used

- Python (Pandas, NumPy)
- **Folium** – interactive geospatial visualizations
- GeoPandas – spatial data clustering
- Seaborn & Matplotlib – trend analysis
- Scikit-learn – modeling logic and scoring

---

## 🗂️ Data Sources

- [Virginia DMV Fatal Crash Records (1994–2022)](https://data.virginia.gov/)
- [GTFS Transit Stops & Routes (2024)](https://data.virginia.gov/)
- [VDOT Six-Year Improvement Plan](https://data.virginia.gov/)
- [NCSA Crash Analysis](https://data.virginia.gov/)

