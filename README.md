# Global Climate Analysis: CO₂, Greenhouse Gas Emissions & Temperature Trends (1950–2024)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)

This repository contains a global climate data analysis covering 75 years of CO₂ emissions, greenhouse gas emissions, and mean surface temperatures across countries (1950–2024).

🔗 **Original Notebook on Kaggle:** [View here](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)  
📓 **Notebook on GitHub:** [View here](https://github.com/lucalullo/Global-Emissions-and-Temperature-1950-2024/blob/main/global-emissions-and-temperature-1950-2024.ipynb)

## 📈 Key Findings

| Indicator | 1950 | 2024 | Change |
|---|---|---|---|
| Global CO₂ | 5,792 MtCO₂ | 37,393 MtCO₂ | **+546%** |
| Global GHG | 17,040 MtCO₂eq | 54,412 MtCO₂eq | **+219%** |
| Mean Temperature | 18.69°C | 20.34°C | **+1.65°C** |
| Top CO₂ emitter | USA | China | — |
| Fastest-growing CO₂ source | Coal | Natural Gas | **+2,168%** |
| Most warmed country | — | Uzbekistan | **+3.48°C** |

## 🛠️ Key Features

- **Global Emission Trends:**
  - Time series of global CO₂, GHG, and mean temperature from 1950 to 2024
  - Decade-over-decade percentage growth comparison across all three indicators
  - Acceleration driven by industrialization of China and India from the 2000s onward

- **Emission Source Analysis:**
  - Breakdown of CO₂ by source: coal, oil, natural gas, cement
  - Stacked area chart (absolute) and 100% area chart (share) for source composition over time
  - Natural gas identified as the fastest-growing source: from 353 Mt to 8,009 Mt (+2,168%)

- **Top Emitters 2024:**
  - Top 15 countries by total CO₂ and total GHG with global share percentages
  - Bubble chart: total CO₂ vs per-capita CO₂, sized by total GHG
  - Cumulative share area chart — Top 5 countries vs rest of the world (1950–2024)
  - China accounts for 32.9% of global CO₂ but only 8.7 t/capita; Saudi Arabia and Kuwait exceed 20–40 t/capita

- **Global Warming by Country:**
  - Temperature delta (1950 → 2024) for all countries with available data
  - Top 20 most warmed and 10 least warmed countries
  - Central Asian ex-Soviet countries lead warming: Uzbekistan (+3.48°C), Kazakhstan (+3.29°C), Kyrgyzstan (+3.20°C)
  - 5-year rolling average temperature curves for selected countries

- **Choropleth Maps:**
  - Per-capita CO₂ by country (2024)
  - Temperature delta by country (1950 → 2024)
  - Animated choropleth: evolution of per-capita CO₂ every 5 years from 1950 to 2024

- **Statistical Correlations:**
  - Correlation matrix across global CO₂, GHG, and mean temperature aggregates
  - Scatter plots with linear trend lines: CO₂ vs Temperature (r = 0.895), GHG vs Temperature (r = 0.889)
  - Note: correlations are descriptive and do not imply direct causality

## 🚀 How to use

1. Clone the repo: `git clone https://github.com/lucalullo/Global-Emissions-and-Temperature-1950-2024.git`
2. Install dependencies: `pip install pandas numpy matplotlib seaborn plotly`
3. Download the datasets from Kaggle:
   - [Global Mean Temperature by Country 1950–2024](https://www.kaggle.com/datasets/lucalullo/global-mean-temperature-by-country-1950-2024)
   - [Global CO₂ Emissions by Country 1950–2024](https://www.kaggle.com/datasets/lucalullo/global-co2-emissions-by-country-1950-2024)
   - [Global GHG Emissions by Country 1950–2024](https://www.kaggle.com/datasets/lucalullo/global-ghg-gas-emissions-by-country-1950-2024)
4. Run the `global-emissions-and-temperature-1950-2024.ipynb` notebook

---

**Author:** [Luca Lullo](https://github.com/lucalullo)  
*Data Scientist | Machine Learning Applied*
