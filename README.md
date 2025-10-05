# Neural Nexus – Smarter Transit and Safety Analytics  
### Virginia Datathon 2025 | Virginia Commonwealth University  

---

## Overview  
This project identifies the **deadliest 8% of Virginia’s roads** by combining crash data, transit coverage, and infrastructure spending information.  
The goal is to support smarter public investment decisions by pinpointing **high-risk, underserved road segments** for safety redesign and infrastructure optimization.

---

## Role and Contribution  
Developed as part of the **Virginia Datathon 2025**, this project demonstrates the application of data analytics, geospatial modeling, and visualization for real-world policy impact.  

**Key contributions include:**  
- Integrated multi-source Virginia crash, transit, and infrastructure datasets.  
- Conducted crash severity and pattern analysis using Python (pandas, NumPy, scikit-learn).  
- Applied **GIS-based hotspot mapping** with GeoPandas and Folium for high-risk area visualization.  
- Built a machine learning model to predict crash-prone zones based on environmental and infrastructure parameters.  
- Designed data storytelling dashboards with actionable recommendations for state-level safety investments.

---

## Problem Statement  
**How can data analytics help the Commonwealth of Virginia target the deadliest 8% of roads and reduce statewide fatalities?**

---

## Methodology  

### 1. Data Collection  
Collected and merged multiple public datasets from open Virginia government sources:  
- Virginia DMV Vehicle and Crash Data  
- VDOT Six-Year Improvement Plan  
- VTrans Prioritized Mid-Term Needs  
- Virginia Transit Routes & Stops (GTFS)  
- Fatal Crash Records (1994–2022)

### 2. Data Processing  
- Cleaned, standardized, and merged 100,000+ records using Python (pandas).  
- Derived risk variables (traffic volume, crash rate, transit proximity).  
- Handled missing data and normalized numerical fields for clustering.

### 3. Geospatial Analysis  
- Visualized accident hotspots through clustering and heatmaps.  
- Overlaid crash and transit layers to reveal underserved but high-risk regions.  
- Used **GeoPandas, Shapely, and Folium** for district-level mapping.

### 4. Predictive Modeling  
- Implemented a **logistic regression and random forest** model to predict high-risk road segments.  
- Evaluated model accuracy using precision-recall and ROC metrics.  
- Designed a **Real-Time Crash Risk API** prototype concept for integration with traffic routing systems.

### 5. Visualization and Reporting  
- Built interactive dashboards to display crash severity distribution, fatalities by mode, and spending efficiency.  
- Conducted correlation analysis between infrastructure allocation and crash density.  
- Presented policy insights aligned with VDOT’s safety and funding goals.

---

## Tools and Technologies  
**Languages:** Python, SQL  
**Libraries:** pandas, NumPy, GeoPandas, scikit-learn, Matplotlib, Seaborn, Folium  
**Visualization:** Plotly, Tableau (for exploratory visuals)  
**GIS Tools:** QGIS, ArcGIS Online  
**Collaboration:** Google Sheets, GitHub  

---

## Key Insights  
- **Motorcycle crashes** have the most volatile fatality trend from 1994–2022.  
- **Highway infrastructure** accounts for 70%+ of state spending; **transit investment** remains minimal.  
- Identified multiple **repeat-crash corridors** where targeted redesign could drastically reduce fatalities.  
- Proposed **AI-assisted Crash Risk API** for real-time safety routing integration.

---

## Impact and Value Creation  

| Level | Outcome |
|--------|----------|
| **Local** | Reduces crash frequency and improves safety near schools and urban centers. |
| **Statewide** | Enables data-driven allocation of safety budgets. |
| **Technical** | Establishes a scalable architecture for predictive road safety analytics. |

---

## Results  
- Designed a **geospatial risk prioritization model** for Virginia’s road network.  
- Built an interpretable dashboard that supports **evidence-based transportation planning**.  
- Delivered an end-to-end workflow integrating **data engineering, ML, and GIS visualization**.  

---
