# COVID-19 Data Analysis

This Jupyter Notebook presents an exploratory data analysis (EDA) of global COVID-19 data. It extracts, processes, and visualizes important trends such as case counts, death rates, testing rates, and reproduction numbers across different countries and time periods.

## 📊 Features

* Data loading and cleaning from a structured dataset (likely from [Our World in Data](https://ourworldindata.org/coronavirus))
* Visualizations of trends over time for:

  * Total and new cases/deaths
  * Cases/deaths per million people
  * Testing rates and test positivity
  * ICU/hospital admissions
* Focus on country-wise and continent-level insights
* Use of `pandas`, `matplotlib`, and `seaborn` for data manipulation and plotting

## 📁 Dataset Columns

Some key columns include:

* `location`, `continent`, `date`
* `total_cases`, `new_cases`, `total_deaths`, `new_deaths`
* `total_cases_per_million`, `total_deaths_per_million`
* `total_tests`, `new_tests`, `positive_rate`
* `reproduction_rate`, `icu_patients`, `hosp_patients`

## 📦 Requirements

Install the required Python packages using:

```bash
pip install pandas matplotlib seaborn jupyter
```

## 🚀 Getting Started

To run the notebook:

1. Clone this repository
2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
3. Open the notebook file and run each cell step by step

## 📌 Notes

* This analysis provides historical insights and may not reflect real-time pandemic status.
* Data source and freshness should be verified if repurposing.
