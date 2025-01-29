# Germany GDP Forecasting with Machine Learning 📊  

This project provides a machine learning model to analyze and predict Germany's Gross Domestic Product (GDP) using data sourced from the **World Bank**. It applies linear regression techniques to forecast future GDP values and visualize economic trends over time. The model can be adapted to analyze other countries as well.  

## Data Source  
The GDP data used in this project was downloaded from the **World Bank** and is contained in the following file:  
- **`API_NY.GDP.MKTP.CD_DS2_es_csv_v2_5998674.csv`** – GDP data file.  

## Project Files  
- **`main.py`** – Main script containing data processing, visualization, and prediction logic.  
- **`API_NY.GDP.MKTP.CD_DS2_es_csv_v2_5998674`** – Data with information.  
- **`requirements`** – Requirements to create project.  

## Features  
- **Data Processing:**  
  - Cleans and prepares Germany and EU GDP data for analysis.  
  - Handles missing values and data type conversions.  
  - Restructures data for easier processing and visualization.  

- **Visualization:**  
  - Time series plots to observe GDP trends for Germany and the EU.  
  - Regression plots to analyze relationships over the years.  
  - Dual-axis plots to compare GDP trends between Germany and the EU.  

- **Machine Learning Model:**  
  - Implements linear regression to estimate future GDP growth.  
  - Provides forecast values for Germany's GDP based on historical data.  
  - Compares predictions with actual data for validation.  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/AlejandroMeyer/Machine-Learning-for-GDP-Growth-Estimation.git
   cd germany-gdp-forecast
