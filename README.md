
# Online Retail Dataset Analysis

##  Project Overview
This project explores an online retail dataset to uncover customer purchasing patterns, product pricing behavior, and sales trends. The goal is to apply **data science techniques** to clean, analyze, and visualize the dataset, then extract actionable business insights.

---

##  Tools Used
- **Python** for data analysis  
- **Pandas** for data cleaning, aggregation, and feature engineering  
- **Matplotlib & Seaborn** for visualizations (boxplots, violin plots, countplots, pairplots, heatmaps)  
- **Jupyter Notebook** for interactive exploration  

---

##  Steps Performed
1. **Data Loading & Cleaning**  
   - Imported dataset into Pandas  
   - Handled missing values, duplicates, and irrelevant columns  
   - Converted date/time features into usable formats (Year, Month, Day, Hour)

2. **Exploratory Data Analysis (EDA)**  
   - Boxplots to detect outliers in Quantity, UnitPrice, and TotalPrice  
   - Countplots to visualize frequency distributions (e.g., by Country, Customer Segment)  
   - Violin plots to show both distribution shape and summary statistics  
   - Pairplots to explore relationships between numeric variables  
   - Correlation heatmaps to detect strong feature relationships

3. **Feature Engineering**  
   - Derived new features like `TotalPrice = Quantity × UnitPrice`  
   - Extracted time-based features (Year, Month, Day, Hour) for temporal analysis  

4. **Insights & Interpretation**  
   - Summarized findings in human‑written insights for business relevance  

---

##  Key Insights
- Most transactions are modest, but a few bulk or high‑value orders dominate the extremes.  
- UnitPrice is skewed, with most items priced low and a handful of premium products stretching the range.  
- TotalPrice outliers highlight top customers or bulk purchases that drive revenue.  
- CustomerID is not meaningful for distribution analysis and should be excluded from boxplots.  
- Correlation analysis confirms that Quantity and TotalPrice are strongly related, while UnitPrice varies independently.  
