# COVID-19 Data Analysis Project

## Overview
This project analyzes the impact of COVID-19 across countries and explores its relationship with worldwide happiness indicators. Using real-world datasets, we:
- Load, clean, and explore COVID-19 and Happiness data
- Visualize trends and patterns in both datasets
- Merge the datasets to analyze correlations between pandemic impact and happiness factors (GDP, life expectancy, social support, etc.)
- Derive insights and answer questions such as: Did happier countries have better COVID-19 outcomes?

## Methodology
1. Data Loading & Exploration:
   - Loaded COVID-19 and worldwide happiness datasets into pandas DataFrames.
   - Explored structure, missing values, and summary statistics.
2. Data Cleaning:
   - Aggregated COVID-19 data by country and calculated total cases.
   - Standardized country names for merging.
3. Exploratory Data Analysis (EDA):
   - Visualized top 10 countries by COVID-19 cases.
   - Plotted the distribution of happiness scores.
4. Merging & Correlation Analysis:
   - Merged datasets on country name.
   - Analyzed and visualized correlations between happiness indicators and COVID-19 cases using a heatmap.

## Key Findings
- The correlation matrix and heatmap revealed the strength and direction of relationships between happiness indicators and COVID-19 cases.
- Insights may include whether countries with higher happiness scores or better social support had fewer COVID-19 cases, or if GDP and health indicators played a role in pandemic outcomes.
- Further analysis can be performed by exploring additional variables, time trends, or country-specific case studies.

## How to Run
1. Open the notebook `Covid-19_data_analysis.ipynb` in Jupyter or VS Code.
2. Run all cells in order to reproduce the analysis and visualizations.
3. Review the plots and summary for insights.

---

Author: Umang Dixit

Date: 12 August 2025
