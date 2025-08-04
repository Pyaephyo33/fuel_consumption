# Fuel Consumption Analysis & Forecasting (2000–2022)

This repository presents a complete data science workflow to explore, analyze, and forecast fuel consumption trends in Canada from 2000 to 2022. It combines in-depth EDA with feature engineering and multiple ML models to uncover insights and predict future usage patterns.

---

## 📊 Features

### 🔎 EDA Highlights (`EDA.ipynb`)
- Year-wise fuel consumption and CO₂ emission trends
- Comparative analysis by:
  - Engine size
  - Number of cylinders
  - Fuel type & vehicle class
- Impact of COVID-19 (2020–2022) on fuel metrics

### 🧠 ML Models (`ML.ipynb`)
- Supervised learning with:
  - Linear Regression
  - Ridge Regression
  - SVR
  - XGBoost
- Time-Series Models:
  - ARIMA
  - LSTM (future-ready setup)
- Evaluation metrics: RMSE, MAE, R² score
- Forecast visualizations with ±5% confidence

### 🛠️ Feature Engineering (`Extended_Features.ipynb`)
- Rolling averages
- Year-on-year differentials
- Polynomial & interaction terms

---

## 📁 Project Structure

```
fuel/
├── EDA.ipynb                      # Exploratory Data Analysis
├── Extended_Features.ipynb        # Feature Engineering
├── ML.ipynb                       # ML modeling and forecasting
├── Fuel_Consumption_2000-2022.csv# Raw dataset
├── requirements.txt               # Python dependencies
├── plots/
│   ├── eda/                       # EDA visualizations
│   └── ml/                        # Forecast and model plots
```

---

## 🧪 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/Pyaephyo33/fuel-forecasting.git
cd fuel-forecasting

# Install dependencies
pip install -r requirements.txt

# Run notebooks
jupyter notebook
```

---

## 📈 Sample Insights

- Fuel consumption dropped significantly in 2020 due to COVID-19 restrictions.
- Vehicles with larger engines and more cylinders have higher combined fuel usage and emissions.
- SVR and XGBoost showed the most accurate forecasts (based on RMSE).

---

## 🔮 Use Cases

- Environmental impact modeling
- Governmental energy policy analysis
- Fleet consumption planning
- Emissions reduction programs

## 📜 License

This repository is licensed for academic and personal research use. Contact for commercial use cases.

---

## 📬 Contact

- GitHub: [Pyaephyo33](https://github.com/Pyaephyo33)
