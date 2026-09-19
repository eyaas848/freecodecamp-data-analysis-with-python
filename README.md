# Data Analysis with Python — freeCodeCamp

A collection of five Python data analysis projects completed as part of **freeCodeCamp's Data Analysis with Python Certification**. Each project applies statistical computation, data cleaning, and visualization techniques using NumPy, Pandas, Matplotlib, and Seaborn to real-world datasets.

## Overview

| # | Project | Core Skills |
|---|---------|--------------|
| 1 | [Mean-Variance-Standard Deviation Calculator](#1-mean-variance-standard-deviation-calculator) | NumPy array operations, statistical computation |
| 2 | [Demographic Data Analyzer](#2-demographic-data-analyzer) | Pandas filtering, aggregation, groupby logic |
| 3 | [Medical Data Visualizer](#3-medical-data-visualizer) | Data normalization, categorical & correlation plots |
| 4 | [Page View Time Series Visualizer](#4-page-view-time-series-visualizer) | Time series analysis, line/bar/box plots |
| 5 | [Sea Level Predictor](#5-sea-level-predictor) | Linear regression, trend forecasting |

## Tech Stack

`Python` · `NumPy` · `Pandas` · `Matplotlib` · `Seaborn` · `SciPy`

---

## 1. Mean-Variance-Standard Deviation Calculator

**File:** `mean_var_std.py`

Computes the mean, variance, standard deviation, max, min, and sum of a 3x3 matrix along rows, columns, and across all elements using NumPy, returning the results as a structured dictionary.

```python
calculate([0,1,2,3,4,5,6,7,8])
```

## 2. Demographic Data Analyzer

**File:** `demographic_data_analyzer.py`

Analyzes 1994 U.S. Census demographic data to answer questions on income distribution, education level, working hours, and nationality using Pandas filtering and aggregation.

## 3. Medical Data Visualizer

**File:** `medical_data_visualizer.py`

Visualizes patient medical examination data, calculating BMI-based overweight status and generating categorical bar plots and correlation heatmaps to explore relationships between cardiovascular disease and lifestyle factors.

## 4. Page View Time Series Visualizer

**File:** `time_series_visualizer.py`

Visualizes freeCodeCamp forum page view data (2016–2019) through line, bar, and box plots to reveal daily trends, monthly seasonality, and year-over-year growth.

## 5. Sea Level Predictor

**File:** `sea_level_predictor.py`

Uses linear regression on EPA/NOAA/CSIRO sea level data (1880–2014) to predict global sea level rise through 2050, comparing long-term trends against the post-2000 rate of change.

---

## Repository Structure

```
freecodecamp-data-analysis-with-python/
├── mean_var_std.py
├── demographic_data_analyzer.py
├── medical_data_visualizer.py
├── time_series_visualizer.py
├── sea_level_predictor.py
├── datasets/
│   ├── adult.data.csv
│   ├── medical_examination.csv
│   ├── fcc-forum-pageviews.csv
│   └── epa-sea-level.csv
└── README.md
```

## Running the Projects

```bash
git clone https://github.com/eyaas848/freecodecamp-data-analysis-with-python.git
cd freecodecamp-data-analysis-with-python
pip install numpy pandas matplotlib seaborn scipy
python3 <project_file>.py
```

## Certification

These projects fulfill the requirements for the **freeCodeCamp Data Analysis with Python Certification**.

🔗 [freecodecamp.org/learn/data-analysis-with-python](https://www.freecodecamp.org/learn/data-analysis-with-python/)

## Author

**Aya** — Computer Engineering Student.
