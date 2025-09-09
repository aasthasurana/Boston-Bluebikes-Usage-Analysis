# 🚴 Analysis of Greater Boston Bluebike Usage (2022–2023)

This repository contains an exploratory and statistical analysis of **Boston Bluebike usage** between 2022 and 2023. The project investigates seasonal, geographic, and demographic usage patterns to optimize bike-sharing services and improve accessibility and efficiency.

---

## 📌 Project Overview
- **Business Problem:**  
  Improve Bluebike accessibility and efficiency by identifying **seasonal** and **geographic** usage patterns and conducting demand–supply analysis across docking stations.

- **Objectives:**  
  - Detect seasonal demand fluctuations.  
  - Analyze station-level patterns of demand and supply.  
  - Segment users by type (members vs. casual users).  
  - Provide recommendations for resource optimization.  

---

## 📊 Data & Methodology
- **Data Source:**  
  Bluebike trip history data (2022–2023), aggregated and queried using **Google BigQuery**.

- **Key Features Analyzed:**  
  - Trip start & stop times  
  - Start & end stations (with geocoordinates)  
  - User type (Member vs. Casual)  

- **Techniques Used:**  
  - SQL queries in **Google BigQuery**  
  - Data cleaning & preprocessing  
  - Exploratory Data Analysis (EDA)  
  - Geographic and seasonal demand pattern visualization
 
- 📜 Results & Insights

Identified seasonal peaks in spring and summer with drops in winter.

Members exhibit consistent year-round usage, while casual riders spike during warmer months.

Certain high-demand stations reveal supply–demand imbalances, suggesting the need for better rebalancing strategies.

---

## ⚙️ Repository Contents
- `Analysis on Boston Bluebike Usage.ipynb` — Jupyter Notebook with data queries, analysis, and visualizations.  

---

## 🛠️ Tools & Libraries
- Python  
  - `pandas`  
  - `matplotlib` / `seaborn` (visualization)  
- SQL with **Google BigQuery**  
- Jupyter Notebook  

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
