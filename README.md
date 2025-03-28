# 🚗 Predicting CO2 Emissions using Simple Linear Regression

This project demonstrates how to build a simple linear regression model using Python to predict **CO2 emissions** of cars based on a single feature from a real-world dataset: `FuelConsumption.csv`. The dataset contains detailed information on fuel consumption and emissions for light-duty vehicles sold in Canada.

---

## 📁 Dataset

The dataset used is publicly available from the [Government of Canada](http://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64).

Each record includes:

- `MODEL YEAR` — Year of manufacture
- `MAKE` — Manufacturer
- `MODEL` — Model name
- `VEHICLE CLASS` — Category (e.g., COMPACT, SUV)
- `ENGINE SIZE` — Engine displacement in litres
- `CYLINDERS` — Number of engine cylinders
- `TRANSMISSION` — Transmission type
- `FUEL TYPE` — Type of fuel used
- `FUEL CONSUMPTION in CITY (L/100 km)`
- `FUEL CONSUMPTION in HWY (L/100 km)`
- `FUEL CONSUMPTION COMBINED (L/100 km)`
- `FUEL CONSUMPTION COMBINED MPG`
- `CO2 EMISSIONS (g/km)` — **Target Variable**

---

## 🎯 Objective

Build a **simple linear regression model** to predict `CO2 EMISSIONS (g/km)` based on one independent feature. For this project, we use `ENGINE SIZE` as the predictor.

---

## 🧪 Technologies Used

- Python 🐍
- Pandas 📊
- Matplotlib 📈
- scikit-learn 🔧
- Jupyter Notebook 📓

---

## 🛠️ How It Works

1. **Load the dataset**
2. **Visualize the data**
3. **Select feature and target**
4. **Split the data** into training and testing sets
5. **Train** a simple linear regression model
6. **Visualize the regression line**
7. **Evaluate** the model on test data

---

## 📷 Sample Output

*Scatter plot showing engine size vs CO2 emissions, with the fitted regression line.*

---

## 📂 Project Structure

