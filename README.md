# Egypt Real Estate Data Analysis & Machine Learning Insights  

A project to **clean**, **analyze**, **visualize**, and **explore predictive modeling** for real estate data in Egypt using Python and basic machine learning techniques.  
The goal is to understand property market trends, identify factors affecting prices, and experiment with simple ML models to see how property features may influence pricing.  

---

## Introduction  

This project focuses on analyzing a **Real Estate Listings dataset** collected from various regions in **Egypt**.  
The dataset includes important property details such as **price, location, area, number of bedrooms, bathrooms, property type, and furnishing status**.  

The main objectives are:  
- To clean and preprocess the raw dataset.  
- To explore and visualize patterns and relationships in property listings.  
- To experiment with a **basic machine learning model** for understanding how property features affect pricing.  
- To build a simple **dashboard** for visual exploration and summary.  

The project is organized into five main stages:  
1. **Data Cleaning & Preprocessing**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature Engineering & Modeling**  
4. **Dashboard & Visualization**  
5. **Final Reporting**

---

##  Dataset Description  

The dataset contains **10,326 rows (records)** and **17 columns (features)**,  
representing property listings from various Egyptian cities and neighborhoods.  

Each record includes information such as:  
- **title** – Listing headline.  
- **location** – City or area of the property.  
- **price** – Property price (may contain mixed formats like “1,200,000 EGP”).  
- **rooms** – Number of rooms.  
- **bathrooms** – Number of bathrooms.  
- **area** – Total property area in square meters.  
- **latitude / longitude** – Geographic coordinates.  
- **compound / developer / finishing** – Construction or furnishing details.  
- **description** – Short text describing the property.  

###  Detected Issues Before Cleaning  
- Missing values in several columns (e.g., `price`, `area`, `location`).  
- Non-numeric characters inside numeric fields (like “EGP”, “sqm”).  
- Duplicated records and inconsistent capitalization in text.  
- Outliers in prices and areas (very high or very low values).  

> 🧹 These problems will be fixed to make the data ready for accurate analysis and model training.

---

##  Methodology  

###  Data Cleaning & Preprocessing  
- Load and inspect data using **pandas**.  
- Handle missing values (by removal or imputation).  
- Convert text-based numbers (like “1,200 EGP”) to numeric format.  
- Drop duplicates and fix inconsistent text formats.  
- Detect and treat outliers using IQR or Z-score methods.  
**Deliverables:** Clean dataset + preprocessing notebook.  

---

###  Exploratory Data Analysis (EDA)  
- Study the distribution of prices, area sizes, and room counts.  
- Compare average prices across locations.  
- Identify correlations between numeric features.  
- Visualize insights using **matplotlib** and **seaborn** (scatter plots, histograms, heatmaps, boxplots).  
**Deliverables:** Visual summaries and descriptive statistics.  

---

###  Machine Learning Modeling (Experimental)  
- Perform **feature engineering** (encoding, scaling).  
- Split the dataset into training and testing sets.  
- Try simple **regression models** (e.g., Linear Regression, Random Forest).  
- Evaluate model performance using **MAE**, **MSE**, and **R²**.  
>  The model here is **exploratory**, meant for learning and testing—not a finalized price predictor.  
**Deliverables:** Jupyter Notebook with model experiments.  

---

###  Visualization & Dashboard  
- Create visual summaries and comparisons between areas and price ranges.  
- Build an **interactive dashboard** (in Power BI or Python) for quick exploration.  
- Include charts for price distribution, top cities by listing count, and property type comparison.  
**Deliverables:** Dashboard file + visuals in notebook.  

---

##  Tools and Technologies  

**Programming:** Python  
**Libraries:** pandas, NumPy, matplotlib, seaborn, scikit-learn  
**Visualization Tool:** Power BI  
**Environment:** Jupyter Notebook  

---

##  Expected Outcomes  

- A **cleaned and well-structured dataset** ready for analysis.  
- Visual insights about **Egypt’s property market**.  
- A **basic machine learning experiment** exploring price relationships.  
- A **dashboard** summarizing results and trends.  
- A **single comprehensive Jupyter Notebook** documenting all stages.  

---

##  Project Deliverables  

By the end of the project, the following files will be delivered:  
- Cleaned dataset file (`.csv`)  
- Jupyter Notebook (containing preprocessing, EDA, and ML sections)  
- Power BI dashboard file (`.pbix`)  
- Final project report (Markdown or PDF)  
itHub: *[Your GitHub Profile Link]*  

