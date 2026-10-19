# Flood Forecasting in Bangladesh: A Comparative Analysis of Time-Series Models

A time-series forecasting research project comparing **ARIMA, SARIMAX, and Prophet** for predicting temperature, rainfall, and water levels across different regions of Bangladesh. This project was conducted as part of my bachelor's thesis in Computer Science and Engineering which later on submitted for publication.

The primary objective was to conduct a comparative analysis of three time-series forecasting models using meteorological and water-level datasets to identify an effective approach for flood-related forecasting.

## 🎯 Project Objectives

- Analyze meteorological and water-level time-series data from Bangladesh.
- Forecast temperature, rainfall, and water levels across different regions.
- Implement and compare ARIMA, SARIMAX, and Prophet.
- Evaluate model performance using Root Mean Squared Error (RMSE) and other reported evaluation metrics.
- Identify the model that performs most consistently across the available datasets.

## 📊 Dataset and Data Source

The datasets were obtained from the **Bangladesh Meteorological Department (BMD)**, a government organization under the administrative control of the Ministry of Defence.

The data were used to investigate time-series patterns and evaluate forecasting performance for the following variables:

- **Temperature**
- **Rainfall**
- **Water levels**

The analysis compares forecasting performance across datasets collected from different regions.

*Note: The exact observation period, regional station names, dataset sizes, and data-download links are not specified here.*

## ⚙️ Methodology

The project follows a comparative time-series forecasting workflow.

### 1. Data Preparation and Exploration

Python libraries were used to prepare, analyze, and visualize the collected datasets. The workflow includes time-series analysis and the Augmented Dickey–Fuller (ADF) test for examining stationarity.

### 2. Forecasting Models

Three time-series forecasting approaches were implemented and compared.

| Model | Description |
|---|---|
| **ARIMA** | Autoregressive Integrated Moving Average, used for time-series forecasting. |
| **SARIMAX** | Seasonal Autoregressive Integrated Moving Average with eXogenous variables, supporting seasonal patterns and external predictors. |
| **Prophet** | A forecasting model designed to capture time-series trends and seasonality. |

The models were evaluated on the available temperature, rainfall, and water-level datasets to compare their predictive performance.

### 3. Model Evaluation

Forecasting performance was assessed using **Root Mean Squared Error (RMSE)** and other evaluation metrics reported in the project.

RMSE measures the typical magnitude of prediction errors, with lower values indicating better predictive performance when models are evaluated on the same target and scale.

The comparative analysis examines model performance across different variables and regions rather than relying on a single dataset.

## 🏆 Key Findings

The comparison of RMSE values across the evaluated datasets indicated that **Prophet consistently outperformed ARIMA and SARIMAX** in predicting rainfall, temperature, and water levels across the regions included in the study.

This finding highlights the potential of Prophet for the forecasting tasks investigated in this project.

*The numerical RMSE values, model configurations, and dataset-specific results should be added to a results table when the original experimental results are available.*

## 🛠️ Technologies and Libraries

**Programming Language**
- Python

**Data Analysis and Processing**
- Pandas
- NumPy

**Visualization**
- Matplotlib
- Seaborn

**Time-Series Analysis and Forecasting**
- Statsmodels
- ARIMA
- SARIMAX
- Prophet

**Model Evaluation**
- Scikit-learn

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Zafrin-Jolly/Forecasting-Floods-in-Bangladesh-Using-Different-Time-Series-Model-A-Comparative-Analysis.git
cd Forecasting-Floods-in-Bangladesh-Using-Different-Time-Series-Model-A-Comparative-Analysis
```

*Note: This installation command lists the libraries used in the provided project details. A `requirements.txt` file, if available, should be used to reproduce the original environment.*

## 🚀 Future Work

Potential directions for extending this research include:

- Evaluating forecasting performance over additional regions and longer observation periods.
- Reporting detailed RMSE and other evaluation metrics for each model and dataset.
- Investigating the effects of model parameters and seasonal patterns on forecast accuracy.
- Exploring how forecasts of rainfall, temperature, and water levels could contribute to flood monitoring and early-warning workflows.

## 🎓 Project Context

**Type:** Bachelor's thesis / research project  
**Field:** Time-Series Forecasting and Data Analysis  
**Application:** Flood-related forecasting in Bangladesh

This research provided an opportunity to apply statistical time-series methods to real-world meteorological data and compare their performance across multiple forecasting tasks.

## 🔗 Repository

[View the source code and project materials on GitHub](https://github.com/Zafrin-Jolly/Forecasting-Floods-in-Bangladesh-Using-Different-Time-Series-Model-A-Comparative-Analysis)

[View the paper](https://www.researchgate.net/profile/Nur-A-Marzan-Dipro/publication/377537885_Forecasting_Flood_in_Bangladesh_Using_Different_Time_Series_Models_A_Comparative_Analysis/links/66c37ba8bcb6b956be013bdb/Forecasting-Flood-in-Bangladesh-Using-Different-Time-Series-Models-A-Comparative-Analysis.pdf)
---

*Using data-driven forecasting to support research on environmental challenges in Bangladesh.*
