# 📈 SEO Traffic Forecast (Prophet Model)

**Predict organic traffic trends with seasonality and holiday awareness.**

This repository contains a Jupyter Notebook that ingests historical traffic data (Google Analytics/Search Console) and uses **Facebook Prophet**
to generate accurate forecasts. It is designed to help SEO teams set realistic KPIs and anticipate seasonal fluctuations.

## ⚡ Key Capabilities
* **Holiday Integration:** Automatically detects national holidays (currently set to `PE` - Peru) to adjust traffic expectations.
* **Trend Analysis:** Visualizes long-term growth vs. short-term noise.
* **Actionable Output:** Generates a 40-day forward-looking forecast to assist in quarterly planning.

## 🛠️ Tech Stack
* **Python 3.x**
* **Facebook Prophet** (Forecasting)
* **Pandas** (Data Manipulation)
* **Matplotlib** (Visualization)

## 📊 How to Use
1.  Upload your CSV with columns `ds` (date) and `y` (traffic).
2.  Set your `cap` (maximum logical traffic ceiling).
3.  Run the notebook to generate the forecast plot.
