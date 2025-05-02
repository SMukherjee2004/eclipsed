# 🌘 Eclipse Prediction Data Preprocessing and EDA

This repository contains a Jupyter notebook focused on preprocessing and exploratory data analysis (EDA) of a solar eclipse dataset, which includes features like path width, central duration, Eclipse Time, Delta T (s), Lunation Number,	Saros Number,	Eclipse Type,	Gamma,	Eclipse Magnitude and datetime. The goal is to prepare clean and standardized data for use in an eclipse prediction model.

## 📂 Contents

- `Research_01.ipynb` — Main notebook for data preprocessing and EDA.
- Handling of missing values in key features.
- Manual standardization of datetime columns.
- Visual and statistical exploration of numeric eclipse data and feature-based storytelling 
- the final `solar_final.csv` file for further improvements.

## 🔧 Features Processed

- Path Width (km)
- Central Duration
- Datetime (standardized manually due to exceptions)
- Eclipse types (encoded)
- Eclipse time (standerdized amnually)
and more.

## 📊 Techniques Used

- Missing value imputation
- Datetime parsing and formatting
- Frequency distribution plots
- Descriptive statistics

## 🚀 Getting Started

### Requirements

- Python 3.8+
- Jupyter Notebook
- pandas, matplotlib, seaborn, numpy, folium & plotly

You can install the requirements using:

```bash
pip install pandas matplotlib seaborn numpy folium plotly
