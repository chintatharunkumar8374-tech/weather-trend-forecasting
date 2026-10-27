# Weather Trend Forecasting Using Global Weather Data

## Project Overview

This project was developed as part of the PM Accelerator Technical Assessment. It analyzes global weather data to identify weather patterns, explore geographical differences, and forecast temperature trends using Python and machine learning.

## Dataset

**Source:** [Global Weather Repository – Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository)

The dataset contains 170,928 weather observations and 41 original columns, including temperature, humidity, precipitation, wind speed, air quality, and geographical information.

## Tools and Technologies

Python, Google Colab, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels, and Cartopy.

## Project Methodology

1. **Data Cleaning:** Handled missing values, checked duplicates, identified temperature outliers, and normalized numerical features.
2. **Exploratory Data Analysis:** Analyzed temperature, precipitation, humidity, and weather feature correlations.
3. **Anomaly Detection:** Used Isolation Forest to identify unusual weather observations.
4. **Climate and Geographical Analysis:** Studied monthly temperature patterns and differences between countries.
5. **Environmental Impact:** Examined correlations between air pollution and weather conditions.
6. **Feature Importance:** Used Random Forest to identify important variables for temperature prediction.
7. **Spatial Analysis:** Visualized weather locations on a world map using Cartopy and Matplotlib.
8. **Forecasting:** Compared ARIMA, Random Forest, and Ensemble models using MAE, RMSE, and R².

## Key Findings

- Most recorded temperatures were between 15°C and 30°C.
- Most precipitation values were close to 0 mm.
- Isolation Forest identified 1,710 unusual weather observations.
- UV index and atmospheric pressure were the two most important features in the Random Forest feature importance analysis.
- Random Forest achieved the lowest RMSE among the three forecasting approaches.
- The forecasting models had difficulty capturing short-term temperature fluctuations.

## How to Run

1. Download or clone this GitHub repository.
2. Open the `Weather_Forecasting (1).ipynb` notebook in Google Colab.
3. Download the Global Weather Repository dataset from Kaggle.
4. Upload the CSV dataset into the Colab environment.
5. Install the dependencies listed in `requirements.txt`.
6. Run the notebook cells in order to reproduce the analysis and visualizations.

## Project Files

- `Weather_Forecasting (1).ipynb` — Python notebook containing the analysis and forecasting models.
- Weather Trend Forecasting Report — detailed explanations, visualizations, and observations.
- `requirements.txt` — required Python packages (to be added).

## Limitations

The forecasting models did not fully capture short-term temperature variations. Some country names also require standardization to improve geographical comparisons.

## Acknowledgment

This project was prepared for the PM Accelerator Technical Assessment using the Global Weather Repository dataset available on Kaggle.
