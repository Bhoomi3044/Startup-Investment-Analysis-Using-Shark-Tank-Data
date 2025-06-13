# Startup-Investment-Analysis-Using-Shark-Tank-Data
This project presents a comprehensive analysis of the Shark Tank India dataset using Python (for EDA) and Power BI (for visualization dashboard). It aims to uncover insights on startup funding patterns, founder backgrounds, and investor behavior.

---

## Tools Used

- **Python**: For data cleaning, preprocessing, and exploratory data analysis (EDA)
- **Power BI**: For creating an interactive dashboard to visualize key trends

---

## Part 1: Python - Exploratory Data Analysis

### Steps:

1. **Load the Dataset**  
   - Import data using Pandas.
   - View structure, missing values, and types.

2. **Clean and Preprocess**  
   - Handle null values and format fields.
   - Convert categorical data where needed.

3. **Exploratory Analysis**  
   - Funding by sector, gender, and deal type.
   - Shark-wise investment trends.
   - Visualizations using Matplotlib and Seaborn.

4. **Insights**  
   - Industry-wise preferences
   - Average funding vs equity trends
   - Solo vs joint shark deals

---

## Part 2: Power BI - Dashboard Visualization

### Steps:

1. **Import Dataset**
   - Load `shark_tank_india_dataset.csv` into Power BI.

2. **Data Transformation (Power Query Editor)**
   - Clean column names
   - Split multiple values (e.g. multiple sharks in one deal)
   - Create calculated columns (e.g. total deal amount)

3. **Create Visuals**
   - Bar charts for shark investments
   - Pie chart for sector-wise pitches
   - Line chart for season-wise deal trends
   - Slicers for filtering by shark, sector, and founder gender

4. **Interactive Features**
   - Drill-through on individual pitches
   - Filters for year, episode, and investment type
   - Dynamic cards for Total Pitches, Deals Closed, Total Funding

---
