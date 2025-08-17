# CodeAlpha_Unemployment_Analysis_with_Python-
CodeAlpha Internship – Unemployment Analysis with Python. Analyzed Indian unemployment trends using Python, Pandas, and Matplotlib.  Includes Covid-19 impact analysis, urban vs rural comparisons, seasonal patterns,  and data-driven insights for economic policies.


## 📌 Overview
This project is part of my **Data Science Internship at CodeAlpha**.  
The goal is to analyze unemployment rate data, clean and explore it, visualize unemployment trends, and investigate the **impact of Covid-19 on unemployment in India**.

## ✅ Objectives
- Analyze unemployment rate data representing unemployed people percentage.  
- Use Python for **data cleaning, exploration, and visualization**.  
- Investigate the **impact of Covid-19** on unemployment rates.  
- Identify **seasonal patterns or trends**.  
- Present insights that could inform **economic or social policies**.

## 📂 Dataset
- [Unemployment in India (2019–2020)](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)  
- [Unemployment Rate up to Nov 2020](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)  

Both datasets were merged, cleaned, and analyzed.

## 🛠️ Technologies Used
- Python 3  
- Pandas (data handling)  
- NumPy (numerical calculations)  
- Matplotlib & Seaborn (visualizations)  

## 📑 Steps Performed
1. **Data Cleaning**
   - Removed missing values & unnecessary columns  
   - Standardized column names  
   - Converted dates into proper `datetime` format  
   - Merged both datasets  

2. **Exploratory Data Analysis (EDA)**
   - National unemployment trend over time  
   - Urban vs Rural unemployment comparison  
   - Zone-wise (North, South, East, West, etc.) unemployment analysis  
   - State-level top/bottom unemployment in 2020  
   - Seasonal patterns (monthly averages)  

3. **Covid-19 Impact**
   - Compared 2019 (pre-Covid) vs 2020 (Covid year)  
   - Observed sharp unemployment spike during **March–April 2020** (lockdown period)  
   - Calculated average increase in unemployment rates  

4. **Insights**
   - National average unemployment rose significantly in 2020 compared to 2019.  
   - The **highest spike** occurred during April 2020, crossing 20% in some regions.  
   - Urban areas were more affected than rural areas.  
   - Seasonal and regional patterns show recurring fluctuations in certain months/zones.  
   - Policies could focus on supporting **urban employment** and providing **job security during seasonal peaks**.

## 📊 Visualizations
The notebook includes:
- 📈 Line plots (2019 vs 2020)  
- 🏙️ Urban vs Rural comparison  
- 🗺️ Zone-wise bar charts  
- 📅 Seasonal monthly patterns  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/atifbashir08/CodeAlpha_Unemployment_Analysis_with_Python.git
   cd CodeAlpha_Unemployment_Analysis_with_Python
