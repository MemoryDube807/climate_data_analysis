# Zambia Climate Data Quality Assessment

## Overview
This repository contains a comprehensive data quality assessment of a 34-year daily weather dataset (1991–2024) for Zambia. The project evaluates environmental data retrieved from the ERA5 reanalysis via Open-Meteo, focusing on identifying structural errors, physical impossibilities, and true climatological anomalies across four meteorological stations (Kitwe, Ndola, Lusaka, and Livingstone).

## Project Objectives
*   **Data Profiling & Cleaning:** Handled missing values, unit inconsistencies, and sentinel codes (e.g., -99 mm placeholders).
*   **Distributional Analysis:** Evaluated departures from Gaussian distributions for temperature, humidity, pressure, and highly right-skewed rainfall data.
*   **Outlier Detection:** Applied robust 1D statistical methods (1.5 IQR, MAD) alongside multivariate anomaly detection (Mahalanobis distance) to differentiate between sensor errors and genuine extreme weather events.

## Repository Contents
*   climate data exploratory.ipynb: The Jupyter Notebook containing the full Python analysis, data cleaning pipeline, and statistical modeling.
*   climate data exploratory report.pdf`: The formal Data Quality Report detailing the findings, extreme event classifications, and dataset limitations.

## Tech Stack
*   **Language:** Python
*   **Environment:** Jupyter Notebook
*   **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib

## Author
**Memory Dube**  
*Master of Science in Computer Science (Climate Change Specialization)*  
*Copperbelt University*
