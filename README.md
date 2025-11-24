# Pet Store Transactions Analysis

![Python](https://img.shields.io/badge/Python-Data_Cleaning-green)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-purple)
![Statistics](https://img.shields.io/badge/Statistics-Exploratory_Analysis-orange)
![Framework](https://img.shields.io/badge/Framework-OSEMN-ff69b4)

---

## Project Overview  
This project analyzes **pet store transaction data** to uncover **sales trends**, **product performance**, and **customer purchasing patterns**.  
Using the **OSEMN framework**, it provides **data-driven recommendations** for improving inventory strategy and business decision-making.

---

## Key Achievements
- **Data Scale:** Analyzed 2,903 transaction records
- **Top Insights:** Cat treats & dog bedding as revenue drivers  
- **Technical Stack:** Python (Pandas, Seaborn) + Tableau dashboard
- **Business Impact:** Inventory optimization strategies

---

## Business Context  
- **Scenario:** Pet Store Retail Business  
- **Challenge:** Identify top-performing product categories and optimize stock strategy  
- **Objective:** Provide actionable insights for sales growth and profitability  
- **Scope:** Analysis of **2,903 transaction records** across multiple product categories  

---

## Framework Applied — OSEMN  

### Obtain & Scrub  
- Imported and validated **2,903 records** from the raw dataset  
- **Data Cleaning Steps:**  
  - Removed missing `Product_Name` or `Product_Category` entries  
  - Filtered price outliers using quantile thresholds (0.0001–0.999)  
  - Dropped `Size` column with >500 null values  
  - Replaced missing `Customer_ID` with `"Unknown"`  
- **Feature Engineering:** Created a `Subtotal` column (`Price × Quantity`)

---

### Explore  
- Conducted **Exploratory Data Analysis (EDA)** to identify sales and pricing trends  
- **Category Insights:**  
  - Top-selling categories by product line  
  - Median pricing comparison between cats and dogs  
- **Visualizations:** Horizontal bar charts showing total sales by category  

---

### Interpret & Present  
- Translated analytical results into **business-focused insights**  
- **Performance Summary:**  
  - **Cats:** Treats (most popular), Bedding (highest price)  
  - **Dogs:** Bedding (most popular), Toys (highest price)  

---

## Key Findings & Business Impact  

### Performance Insights  
- **Cat Products Dominate** overall sales volume  
- **Category Leaders:** Treats and toys (cats), bedding (dogs)  
- **Premium Segment:** Bedding drives higher median prices  
- **Optimization Potential:** Cross-selling opportunities between product lines  

### Strategic Recommendations  
1. **Boost High Performers:** Prioritize cat toys/treats inventory  
2. **Sustain Top Dog Category:** Continue investment in dog bedding  
3. **Balance Volume vs. Margin:** Monitor both sales and profit contribution  
4. **Plan Seasonally:** Adjust product mix based on demand trends  

---

## Profitability Analysis of Pet Products Visualization (Tableau)
<img width="1171" height="490" alt="image" src="https://github.com/user-attachments/assets/28856499-ebea-47c0-b6e6-5d346ad8db82" />

**Tableau Public:** https://public.tableau.com/app/profile/sumaya.mateen/viz/MetaAssignment_17618077249700/MostProfitableProductsDashboard2


## Analytical Framework - OSEMN

| Stage | Implementation |
|-------|----------------|
| **Obtain** | Imported 2,903 transaction records |
| **Scrub** | Data cleaning, outlier removal, feature engineering |
| **Explore** | EDA, statistical analysis, trend identification |
| **Model** | Category performance modeling & insights |
| **iNterpret** | Business recommendations & Tableau visualization | 

---

## Files Included

- [Pet_Store_Transactions_Analysis.ipynb](Pet_Store_Transactions_Analysis.ipynb) — Jupyter Notebook with full pet store transaction analysis

---

## Project Context  
**Course:** Python Data Analytics  
**Program:** Meta Data Analyst with GenAI Professional Certificate  
**Focus:** End-to-end data analysis project demonstrating real-world business application
