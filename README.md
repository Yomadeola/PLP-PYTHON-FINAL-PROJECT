# 🦠 COVID-19 Data Analysis Project

This project analyzes the global spread and impact of COVID-19 using data from [Our World in Data](https://ourworldindata.org/coronavirus). It focuses on trends in confirmed cases, deaths, vaccination rollout, and regional disparities, with visualizations and insights derived from time series data.

---

## 🎯 Objectives

- Load, clean, and prepare COVID-19 data from OWID
- Explore and visualize trends in infections and deaths
- Analyze vaccination progress across countries and continents
- Build an interactive choropleth map showing geographic spread
- Derive insights and reflect on global response patterns

---

## 🛠 Tools & Libraries Used

- **Python 3.x**
- **JupyterLab / Jupyter Notebook**
- **pandas** — data manipulation
- **matplotlib** & **seaborn** — plotting & visualization
- **plotly.express** — interactive choropleth maps
- **OWID CSV Dataset** — latest COVID-19 statistics

---

## 🚀 How to Run the Project

1. **Clone or download the project folder**
2. Place `owid-covid-data.csv` in the same directory
3. Open `PythonFinal.ipynb` in **JupyterLab**
4. Run all cells sequentially to generate:
   - Time series plots for cases, deaths, and vaccinations
   - Interactive maps
   - Final insights and summary

> 🔧 *If you see any warnings during CSV load, use `low_memory=False` in `pd.read_csv()`.*

To install required packages:

```bash
pip install pandas matplotlib seaborn plotly


📁 Project Files
owid-covid-data.csv — data source

PythonFinal.ipynb — notebook with analysis & visuals

README.md — this file
