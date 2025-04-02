# Rwanda's CPI Forecasting 

This repository hosts an R Markdown analysis titled **"CPI Forecast Project"**. The comprehensive file `CPI_Forecast.Rmd` covers the entire workflow for forecasting the Consumer Price Index (CPI) using time series and machine learning methodologies.

## Project Objective

The primary objective of this project is to accurately forecast CPI values by leveraging statistical and machine learning techniques, assisting in informed economic decision-making and strategic planning.

## Repository Contents

The repository structure is:

```
CPI_Forecast/
├── CPI_Forecast.Rmd      # Main R Markdown file with detailed analysis
├── data/                 # Data files for analysis
├── outputs/              # Output results such as plots and model forecasts
└── README.md             # Project details and usage guidelines
```

## Detailed Content of `CPI_Forecast.Rmd`

The `CPI_Forecast.Rmd` file includes the following steps:

### 1. Data Loading and Cleaning
- Importing CPI-related data from CSV files.
- Handling missing values with forward and backward fill techniques.

### 2. Data Conversion and Inspection
- Conversion of textual data to numeric formats.
- Exploratory data analysis including summary statistics.

### 3. Exploratory Visualizations
- Time series plots for CPI and Inflation Rate.
- Identification of trends and seasonality.

### 4. Correlation and Stationarity Testing
- Ensuring data stationarity using Augmented Dickey-Fuller tests.
- Correlation matrix generation for numeric variables.

### 5. Feature Engineering
- Creation of lag features and derived metrics such as M2/M1 ratios.
- Validation of features for predictive modeling.

### 6. Forecast Modeling
- **ARIMA Model:** Time series forecasting using Auto ARIMA.
- **Random Forest Model:** Predictive modeling using random forests for robust forecasting.

### 7. Model Evaluation and Validation
- Performance metrics such as MAPE, MAE, and MASE.
- Visualizations of forecasts versus actual CPI values.

## How to Run the Analysis

### Requirements
- R (version 4.0+)
- RStudio

### R Packages
Install the required packages:

```R
install.packages(c("dplyr", "ggplot2", "zoo", "forecast", "Metrics", "randomForest", "caret", "tseries"))
```

### Running Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/CPI_Forecast.git
```

2. Open `CPI_Forecast.Rmd` in RStudio.

3. Execute or knit the document to reproduce analyses and visual outputs.

## Outputs Generated

The `.Rmd` file generates various outputs:
- CPI and Inflation Rate trend visualizations
- Forecast plots from ARIMA and Random Forest models
- Model performance summaries (MAPE, MAE, MASE)

## Contribution

Your contributions to enhance or expand the analysis are welcomed. Feel free to submit pull requests or issues.

## License

This project is available under the MIT License. See `LICENSE` for details.

