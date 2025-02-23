# CO₂ Emission Prediction

This project implements a simple linear regression model to predict CO₂ emissions based on fuel consumption data. The dataset used is `FuelConsumptionCo2.csv`, which includes various parameters related to vehicle fuel consumption and CO₂ emissions.

## Dataset
- **FuelConsumptionCo2.csv**: Contains the following columns:
  - `ENGINESIZE`: Engine size of the vehicle
  - `CYLINDERS`: Number of cylinders
  - `FUELCONSUMPTION_COMB`: Combined fuel consumption (L/100km)
  - `CO2EMISSIONS`: CO₂ emissions (g/km)

## Key Features
- Data loading and preprocessing
- Exploratory data analysis (EDA)
- Training a simple linear regression model using `sklearn`
- Visualizing regression results

## How Prediction Works?
- The model finds a mathematical equation to describe how CO₂ emissions are related to engine size and fuel consumption.
- If using **Simple Linear Regression**, the equation looks like:
  ```
  CO₂ Emissions = m * Fuel Consumption + b
  ```
  where `m` is the slope (how much CO₂ increases per unit fuel consumption), and `b` is the intercept.
- If using **Multiple Linear Regression** (considering multiple features like engine size and cylinders), it looks like:
  ```
  CO₂ Emissions = w1 * Engine Size + w2 * Fuel Consumption + w3 * Cylinders + b
  ```
- After training, when you input new **fuel consumption and engine size** values, the model will predict the **CO₂ emission**.

## Results
The model predicts CO₂ emissions based on engine size and fuel consumption, highlighting the relationship between vehicle specifications and emissions.
