# Temperature Prediction

## Problem
Predict the temperature of a location based on humidity sensor readings —
estimating environmental conditions from a single atmospheric variable.

## Data
- ~700,000 hourly sensor readings across multiple locations
- Features: Humidity
- Target: Temperature
- Additional columns (sensor_id, lat, lon, pressure) not used in modelling

## Method
- Isolated relevant columns and dropped null rows
- 80/20 train-test split with random_state=42
- Linear Regression to model the relationship between humidity and temperature
- Priority metric: R² Score — measures how well humidity explains temperature variance

## Results
| Metric | Score |
|--------|-------|
| MSE    |       |
| RMSE   |       |
| R²     |       |

> Run the notebook to populate the results above with your actual output values.

## Stack
Python, pandas, numpy, scikit-learn, matplotlib, seaborn

## Run It
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook Temperature_Prediction_Test.ipynb
```
> Place `humidity.csv` in the same folder as the notebook before running.
