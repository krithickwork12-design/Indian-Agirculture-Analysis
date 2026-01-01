#  AgriData Explorer  
## Understanding Indian Agriculture using EDA, SQL & Power BI

---

##  Project Overview

**AgriData Explorer** is an end-to-end data analytics project focused on exploring
**Indian agricultural patterns** using **district-level data from ICRISAT**.
The project combines **Python-based EDA, SQL analysis, and interactive Power BI dashboards**
to derive insights on crop production, yield efficiency, regional dominance,
seasonal trends, and long-term growth.

This project is designed to support:
- **Farmers** – crop selection and productivity improvement  
- **Policymakers** – resource allocation and intervention planning  
- **Researchers** – agricultural trend and efficiency analysis  

---

##  Problem Statement

India’s agricultural data is vast, complex, and fragmented across regions.
Stakeholders face challenges in:
- Understanding crop production trends
- Comparing yield efficiency across regions
- Identifying high-growth and low-performance areas
- Making data-driven decisions for sustainability and policy

This project aims to solve these challenges by building a **data-driven analytical platform**
that provides **clear insights and interactive visualizations**.

---

##  Project Objectives

- Analyze crop production trends across Indian states and districts  
- Identify top-producing states and districts for major crops  
- Study the relationship between cultivated area and production  
- Compare yield efficiency across crops and regions  
- Analyze seasonal patterns (Kharif vs Rabi)  
- Visualize long-term agricultural trends (50+ years)  
- Implement SQL-based analytical questions through dashboards  

---

##  Dataset Information

**Source:** ICRISAT – District Level Agricultural Data  

### Dataset Characteristics
- **Geography:** State & District level  
- **Time Period:** Multi-year (50+ years)  
- **Metrics:**
  - Area Cultivated (1000 ha)
  - Production (1000 tons)
  - Yield (kg/ha)

### Crops Covered
- Rice, Wheat, Maize  
- Oilseeds, Sugarcane, Cotton  
- Sorghum (Kharif & Rabi)  
- Pearl Millet, Finger Millet  
- Groundnut, Sunflower, Soybean  

---

##  Tools & Technologies Used

| Category | Tools |
|--------|------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Database | SQL (SQLite / MySQL) |
| Dashboarding | Power BI |
| Environment | Jupyter Notebook |

---

##  Project Workflow

### 1️ Data Collection
- Imported district-level agricultural data from ICRISAT (CSV)

### 2️ Data Cleaning & Preprocessing
- Standardized column names
- Converted data types
- Handled missing values
- Removed duplicates
- Prepared analysis-ready dataset

### 3️ Exploratory Data Analysis (EDA)
- Univariate, bivariate, and multivariate analysis
- Crop-wise and region-wise comparisons
- Time-series trend analysis (50 years)
- District-level deep dives

### 4️ SQL Analysis
- Answered **10 analytical business questions** using SQL logic:
  - Growth analysis
  - Ranking and trend analysis
  - Yield efficiency
  - Crop comparisons

### 5️ Power BI Dashboard
- Converted EDA and SQL logic into **interactive visuals**
- Built a **9 page dashboard** with slicers, maps, trends, and comparisons

---

##  Key EDA & Analytical Insights

- **West Bengal** is the highest rice-producing state in India  
- **Uttar Pradesh** leads wheat production and wheat yield per hectare  
- **West Bengal contributes ~38.5%** of India’s wheat production  
- **Madhya Pradesh** dominates oilseed production and yield efficiency  
- **Karnataka** leads sunflower production  
- **Gujarat** is the top groundnut producer  
- **Maharashtra** has the highest sorghum production (Kharif & Rabi)  
- **Sugarcane production** increased from ~10,000 to ~40,000 tons over 50 years  
- **Rice production** consistently exceeds wheat production historically  
- **Pearl millet** shows stronger growth than finger millet  

---

##  Statistical Findings

- Strong positive correlation between **cultivated area and production**
- Rice shows the **strongest dependency on area**
- Wheat demonstrates **higher efficiency due to irrigation**
- Maize shows **higher yield variability**
- Area expansion alone is insufficient — **yield practices matter**

---

##  Power BI Dashboard Structure

### Page 1 – National Agriculture Overview
- KPI cards (Rice, Wheat, Oilseeds)
- State-wise rice production map
- Rice vs Wheat trend analysis
- Year & State slicers

### Page 2 – Crop-wise Analysis
- Top rice & wheat producing states
- Sugarcane long-term trend
- Crop contribution analysis

### Page 3 – District-level Analysis
- District-wise rice production
- Tables for yield & production
- Interactive district maps

### Page 4 – Seasonal & Millet Analysis
- Sorghum (Kharif vs Rabi)
- Pearl vs Finger millet trends

### Page 5 – Yield & Efficiency Analysis
- Area vs production correlation
- Soybean yield efficiency
- Rice vs Wheat yield comparison

### Page 6 - 9 – SQL Insights
- All **10 SQL questions implemented visually**
- Growth, ranking, trend, and comparison analysis

---

##  SQL Questions Implemented

1. Year-wise rice production trend (Top 3 states)  
2. Top 5 districts by wheat yield increase (last 5 years)  
3. States with highest oilseed growth (5-year window)  
4. Area vs production correlation (Rice, Wheat, Maize)  
5. Cotton production growth (Top 5 states)  
6. Top groundnut producing districts (2017)  
7. Annual average maize yield  
8. Total oilseed area by state  
9. Districts with highest rice yield  
10. Rice vs Wheat production comparison (Top 5 states, 10 years)  

---

---

##  Business & Policy Implications

### For Farmers
- Focus on yield improvement instead of land expansion
- Select crops aligned with regional strengths

### For Policymakers
- Target low-efficiency, high-area regions
- Promote millets and sorghum for climate resilience
- Invest in irrigation and modern farming technologies

### For Researchers
- Study climate impacts on yield variability
- Analyze district-level efficiency gaps

---

##  Future Enhancements

- Crop yield prediction using machine learning
- Climate & rainfall data integration
- Crop recommendation system
- Real-time dashboards
- State-wise forecasting models

---

##  Conclusion

**AgriData Explorer** delivers a comprehensive, data-driven understanding of Indian agriculture
by combining **EDA, SQL analytics, and interactive dashboards**.



