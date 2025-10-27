# 🌎 Ozone Pollution Analysis

This project presents a detailed **data-driven analysis of ozone pollution** across California using official state-level air monitoring datasets.
The notebook explores how ozone concentrations vary **seasonally, geographically, and by human activity**, offering valuable insights for policymakers and environmental researchers.

---

## 📊 Project Overview

Ozone is one of the most critical air pollutants affecting human health and climate.
This notebook investigates:

* **Seasonal variation** in ozone levels across California.
* **Regional disparities** and hotspot detection.
* **Impact of weekday vs weekend activities** on pollution.
* **Compliance with EPA standards** for ozone concentration.

---

## 🧰 Technologies Used

| Category             | Tools                       |
| -------------------- | --------------------------- |
| Programming Language | Python 3                    |
| Data Manipulation    | pandas, numpy               |
| Visualization        | matplotlib, seaborn, plotly |
| Environment          | Jupyter Notebook            |

---

## 🧪 Analysis Workflow

1. **Data Loading and Exploration**

   * Read raw CSV data from California air monitoring stations.
   * Explore dataset shape, structure, and missing values.

2. **Data Cleaning and Preprocessing**

   * Handle null or inconsistent readings.
   * Convert timestamps and standardize units.

3. **Exploratory Data Analysis (EDA)**

   * Summary statistics for ozone levels.
   * Seasonal and weekday/weekend comparisons.
   * Visualizations for trends and distributions.

4. **Geospatial Insights**

   * Map ozone levels by county using choropleth plots.
   * Identify high-risk zones (San Bernardino, Riverside, Tulare).

5. **Regulatory Assessment**

   * Compare observations against the **EPA ozone threshold (0.070 ppm)**.
   * Highlight sites nearing critical risk levels.

---

## 📈 Key Findings

* 🌤️ **Summer ozone levels** are **~36.6% higher** than winter levels.
* 🚗 **Weekday ozone levels** show a **0.9% increase** vs weekends — indicating industrial and traffic influence.
* 🏭 **Hotspots identified**: San Bernardino, Riverside, and Tulare counties.
* ⚖️ All sites remain **below EPA thresholds**, but one approaches the 0.070 ppm limit.

---

## 🧩 Repository Structure

```
📁 california-ozone-analysis/
│
├── notebook.ipynb          # Main analysis notebook
├── data/                   # (optional) Raw or cleaned datasets
└── README.md               # Project documentation
```

---

## 📚 Future Improvements

* Integrate **real-time air quality API** for live monitoring.
* Develop a **dashboard** (e.g., with Streamlit or Dash).
* Expand analysis to **multi-year comparisons** and **forecasting** with ML.

