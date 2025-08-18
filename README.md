# 📊 Sales Performance Analysis  
**Portfolio Project – Sales & Profit Analysis**

## 📌 Overview
This project demonstrates my ability to **prepare, model, and analyze business data** using **Power BI, DAX, Excel, SQL, and Python**.  
It showcases how raw sales data can be transformed into **actionable insights and executive dashboards** that support strategic business decisions.  

### 🔥 Power BI Live Demo
  [View Interactive Report](https://app.powerbi.com/view?r=eyJrIjoiMGVmODg0ZDMtM2ZlNy00ZTE3LTlmZTctMjExNmE2ZWI1NGYyIiwidCI6IjEwYmZkOTkwLTFlNTItNGRiMC05ODQyLTEyMWRlMjBhOWU3NCJ9)
---

## 🖼️ Executive Dashboard - Mobile Layout Preview
[![MobileLayoutDashboard](https://github.com/user-attachments/assets/a4b08c86-d6c4-47d6-be73-40ac2e60c3d0)
## 🖼️ Sales Ovierview
![SalesOverview](https://github.com/user-attachments/assets/b1b13bbe-648e-4b05-a99c-141d1046e441)
## 🖼️ Profit Ovierview
![ProfitOverview](https://github.com/user-attachments/assets/16326581-068b-4d08-a022-021bd6924ece)

---

## 🛠️ Key Skills Demonstrated
- **Data Preparation & Transformation:** Revenue, profit, and tax calculations using DAX  
- **Data Modeling:** Power BI relationships, Calendar table, currency conversion  
- **DAX & Analytics:** Measures for Yearly/Quarterly/YTD Profit, Median Sales, Profit Margin  
- **Visualization & Reporting:** Dashboards with bar, column, pie, line, area charts, KPIs, slicers  
- **Executive Dashboarding:** Alerts, subscriptions, and mobile-friendly dashboards  
- **Python Integration:** Pandas for external currency data and transformations  

---

## 🌟 Project Highlights
- Built a **Power BI data model** linking Sales, Purchases, Countries, and Exchange data  
- Created **interactive Sales & Profit dashboards** with slicers and KPIs  
- Designed an **Executive Dashboard** with alerts and subscriptions  
- **Key insights identified:**  
  - 🏆 Highest Net Revenue Product: *Modular Sofa Set – $928.36 USD*  
  - 👩‍💼 Top Sales Rep: *Alice – highest transactions*  
  - 📉 Lowest Net Revenue: *Floral Wallpaper – $9.6*  

---

## 🐍 Python Integration (Currency Exchange Example)
```python
import pandas as pd
from io import StringIO

data = """Exchange ID;ExchangeRate;Exchange Currency
1;1;USD
2;0.75;GBP
3;0.85;EUR
4;3.67;AED
5;1.3;AUD"""
df = pd.read_csv(StringIO(data), sep=';')
df
```
---

## 🧰 Tools & Technologies
- **Power BI:** Data modeling, DAX, visualization, dashboards
- **Excel:** Data cleaning, revenue and profit calculations
- **Python (pandas):** Data import and transformation
- **DAX:** Advanced measures and KPI calculations

---
## 📈 Outcome & Impact

- Delivered actionable insights to track sales, profitability, and customer loyalty
- Enabled executive-level monitoring via dashboards with alerts and subscriptions
- Showcased end-to-end data analysis workflow: data prep → modeling → visualization → executive reporting

---
## 📂 Project Structure

- `datasets/` – SQL scripts and sample sales data exports
- `reports/` – Power BI (.pbix) files for sales dashboards
- `docs/` – Step-by-step guides and documentation
- `images/` – Screenshots of sales dashboards and visuals

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/analystmohitshah/sales-performance-analysis.git

   ```

2. **Open the interatcitve Power BI Report**
   - https://app.powerbi.com/view?r=eyJrIjoiNjIwOGNlYWQtNjI2ZC00YmVjLTg0N2YtYjEwY2MyYjI1MzQzIiwidCI6IjEwYmZkOTkwLTFlNTItNGRiMC05ODQyLTEyMWRlMjBhOWU3NCJ9
   - 
   - Refresh the dataset to load your data.

## Contributing

Contributions are welcome! Please submit issues or pull requests to add new features, improve documentation, or update datasets.

## License

[Specify license here]

## Contact

Maintainer: [analystmohitshah](https://github.com/analystmohitshah)
