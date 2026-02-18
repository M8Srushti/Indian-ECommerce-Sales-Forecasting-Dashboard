# Indian E-Commerce Sales Forecasting Dashboard

End-to-end project: Analyze historical sales, forecast next 12 months using Prophet, and build interactive Power BI dashboard for inventory optimization.

## Business Problem
Indian e-commerce companies need accurate sales forecasts to manage inventory after 2025 supply chain disruptions. This project predicts monthly sales, highlights festive seasonality, and recommends stock buffers.

## Tech Stack
- **SQL** – Data cleaning & monthly aggregation (sqliteonline.com)
- **Python** – EDA + Facebook Prophet time-series forecasting (Google Colab)
- **Power BI** – Interactive dashboard with actual vs forecast visuals, KPIs, and state/category insights

## Dataset
Real Indian e-commerce orders (April 2018 – March 2019) from Kaggle: [benroshan/ecommerce-data](https://www.kaggle.com/datasets/benroshan/ecommerce-data)

## Key Deliverables
- 12-month sales forecast with uncertainty intervals
- Power BI dashboard featuring:
  - Actual vs Forecast line chart
  - KPI cards (Total Sales, Forecast, Variance)
  - Sales by Category & State map
  - Slicers for Category and State

## Business Insights
- Strong festive peak in Oct–Dec → recommend 25–40% inventory buffer
- Furniture shows consistent negative profit → review logistics & supplier costs
- Electronics forecast shows growth → prioritize stock allocation

## Files in this Repository
- `Sales_Forecasting_Prophet.ipynb` – Full Python notebook with Prophet model
- `Ecommerce_Sales_Forecast_Dashboard.pbix` – Power BI dashboard file
- `monthly_sales.csv` – Aggregated historical sales
- `sales_forecast.csv` – Prophet forecast output
- `master_sales.csv` – Detailed transaction data

## How to Run / Explore
1. Open `Sales_Forecasting_Prophet.ipynb` in Google Colab
2. Download `Ecommerce_Sales_Forecast_Dashboard.pbix` and open in Power BI Desktop
3. Explore visuals and slicers

## Future Improvements
- Add real sales targets from external data
- Incorporate holiday events in Prophet
- Deploy dashboard online (Power BI Service)

Built by Srushti | Nagpur, India | 2026
