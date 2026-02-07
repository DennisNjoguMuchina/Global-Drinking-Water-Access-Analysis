# 🌍 Global Access to Drinking Water Data Analytics Project
## Data

[View project spreadsheet](https://docs.google.com/spreadsheets/d/1RuVxDUMx2cIDjYOMIVnO88dMnCzbo_EeDQKp0A74N5E/edit?usp=sharing)

![alt text](/pict_featured_large.jpg)
## 📌 Project Overview
This project analyzes global access to drinking water services across countries and income groups using Excel.  
The aim is to understand how population size, urbanization, and income level influence access to safe drinking water.

The analysis focuses on:
- National, urban, and rural population distributions
- Water service levels (basic, limited, unimproved, surface)
- Differences across income groups
- Global inequalities in access

---

## 🎯 Objectives
- Investigate global drinking water access patterns
- Compare access across income groups
- Analyze urban vs rural disparities
- Build analytical summaries using Excel
- Create visualizations to communicate insights

---

## 🗂️ Dataset Description
The dataset contains global estimates on drinking water access including:

**Population metrics**
- National population size
- Urban population share

**Water service indicators**
- At least basic service
- Limited service
- Unimproved service
- Surface water use

**Breakdowns**
- National
- Rural
- Urban

---

## 🧹 Data Cleaning & Preparation
Steps performed:

- Imported dataset into Excel
- Corrected separator issues and structured columns
- Handled missing values (NAN)
- Standardized column naming
- Converted population units
- Created new analytical features:

New features created:
- `urban_population_total`
- `rural_share_percent`
- `population_total_millions`
- `water_basic_national_percent_rounded`
- `urban_share_percent_rounded`
- `rural_share_percent_rounded`

---

## 📊 Exploratory Analysis

### 1️⃣ Global population vs dataset population
Compared:
- Dataset total population
- World population benchmark
- Urban population totals
- Percentage differences

📌 **Add visualization here:**
- Global population comparison table OR chart  
(Screenshot from "Global 2020 report")

---

### 2️⃣ Urban vs Rural population distribution
A line chart was created to show:
- National population size vs
- Urban population share
- Rural population share

![alt text](/National%20population%20versus%20urban%20and%20rural%20share.png)
- Line chart (population vs urban/rural shares)

---

### 3️⃣ Water access distribution by service level
Measures calculated:
- Mean
- Median
- Mode
- Interquartile range
- Standard deviation

Across:
- National
- Rural
- Urban

📌 ![alt text](/Access%20to%20water%20.png)
- Box & whisker / candlestick chart

---

### 4️⃣ Water access vs population size
100% stacked column charts created for:
📌![alt text](/National%20Distribution%20Of%20Access%20To%20Water%20per%20Service%20Level%20(1).png)
- National population vs service levels
![alt text](/Urban%20Distribution%20Of%20Access%20To%20Water%20per%20Service%20Level.png)
- Urban population vs service levels

---

### 5️⃣ Income group analysis
A pivot table was created to analyze:

- Population size by income group
- Average urban share
- Average basic, limited, unimproved, surface access


![alt text](/Screenshot%202026-02-07%20165611.png)

📌 ![alt text](/Income%20group%20vs%20water%20access%20.png)
- Income group vs water access chart

---

## 📈 Key Insights

- High-income countries show near-universal access to basic drinking water.
- Low-income countries rely more on unimproved and surface water sources.
- Urban areas consistently have better access than rural areas.
- Population size influences global access trends significantly.
- Access to basic water services increases with national income level.

---

## 🧠 Skills Demonstrated

- Data cleaning
- Feature engineering
- Exploratory data analysis
- Pivot table modeling
- Data visualization
- Analytical storytelling

---

## 🛠️ Tools Used
- Microsoft Excel
- Pivot Tables
- Aggregation functions
- Statistical summaries
- Data visualization techniques

---

## 🌍 Real-World Impact
Access to safe drinking water is a major global development challenge tied to:
- Public health
- Infrastructure
- Economic development
- Sustainable Development Goals (SDG 6)

This project demonstrates how data analysis can help identify inequality and inform policy decisions.

---

## 🚀 Future Improvements
- Build Power BI dashboard
- Add country-level drilldowns
- Automate pipeline using Python
- Add time-series analysis