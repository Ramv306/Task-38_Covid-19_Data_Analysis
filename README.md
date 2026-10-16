# 📊 COVID-19 Global Impact Dashboard

A comprehensive data analytics project analyzing global COVID-19 trends, case fatality rates, and vaccination rollouts across different regions using **Python**, **Excel**, and **Power BI / Tableau**.

---

## 📌 Project Overview

The objective of this project is to practice the complete analytics pipeline—from cleaning messy real-world time-series data to engineering derived metrics and communicating actionable visual insights to non-technical stakeholders.

---

## 🛠️ Tech Stack & Tools Used

* **Programming / Scripting:** Python (Pandas, NumPy)
* **Data Manipulation:** Data Cleaning, Handling Missing Values, Rolling Averages
* **Visualization:** Power BI / Tableau / Matplotlib & Seaborn
* **Version Control:** Git & GitHub

---

## 📂 Key Features & Derived Metrics

1. **7-Day Rolling Averages:** Calculated 7-day moving averages for `new_cases` and `new_deaths` to smooth out daily reporting noise and weekend lag.
2. **Case Fatality Rate (CFR %):** Computed as `(Total Deaths / Total Cases) * 100` to measure disease severity over different waves.
3. **Cumulative Metrics:** Tracked overall progress of total reported cases, deaths, and vaccination progress across regions.

---

## 📈 Dashboard Highlights

* **Dynamic Filters (Slicers):** Select specific countries and filter by date range.
* **Trend Analysis:** Line charts comparing 7-day moving averages across different pandemic waves.
* **Fatality & Vaccination Insights:** Bar charts and cards highlighting global fatality rates vs. vaccination trends.

---

## 💡 Key Findings & Insights

* **Smoothing Noise:** 7-day rolling averages proved essential for accurately identifying peak transmission periods without daily spike anomalies.
* **Vaccination Impact:** Higher vaccination coverage strongly correlated with a notable decline in Case Fatality Rates (CFR %) during subsequent waves.
* **Regional Differences:** Significant variation was observed in mortality and recovery rates across different global regions based on healthcare response time.

---

## 📁 Repository Structure

```text
├── data/
│   ├── raw_covid_data.csv          # Original dataset
│   └── covid_19_cleaned_global_dataset.csv # Final cleaned dataset
├── notebook/
│   └── covid_data_analysis.ipynb   # Python analysis & feature engineering
├── dashboard/
│   └── covid19_dashboard.pbix      # Power BI / Tableau Dashboard file
└── README.md                       # Project documentation
