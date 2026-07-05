# Real-Estate-Data-Analysis
An end-to-end data analysis project exploring housing prices , property features ( like pool availabillity and furnished status ), and market trends over time using pandas ,seaborn,matplotlib.

An interactive and end-to-end data analysis project focused on exploring the housing market, property pricing trends, and the impact of various features (like location, furnishing status, and amenities) on property values.

---

## 🚀 Project Overview
This project dives deep into a real estate dataset to uncover hidden patterns and provide valuable market insights. Through comprehensive data cleaning, filtering, and advanced visualization techniques, we analyze how property characteristics drive pricing and how the market has evolved over time.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Environment:** Jupyter Notebook

---

## 🔍 Key Insights & Analysis Covered

### 1. Pricing vs. Property Features (Scatter Analysis)
* Analyzed the core relationship between **Property Area** and **Price**.
* Segmented the market based on amenities like **Pool Availability (`Has_Pool`)** to isolate premium properties and identify multi-million dollar outliers.

### 2. Regional Analysis & Distribution (Grouped Bar Plots)
* Grouped and aggregated properties by **Location** and **Furnishing Status** (e.g., Unfurnished, Fully Furnished, Semi-Furnished).
* Cleaned and filtered out corrupted data fields (like `UnKhown` inputs) to ensure completely accurate distributions.

### 3. Historical Market Trends (Time-Series Line Plots)
* Tracked the **Mean Price over the Years** (from 1985 onwards).
* Exposed historical market cycles, major crashes, and all-time high peaks (e.g., the post-2020 real estate boom).

---

## 📈 Visualizations Showcase
The project utilizes carefully customized plots, incorporating custom formatting (like formatting price ticks into `$K` units for scannability), adjusted legends, and styled spines (`plt.subplots_adjust`, `bbox_to_anchor`, `FuncFormatter`) to ensure dashboard-grade visuals.

* **Trend Line:** Tracking market fluctuations and long-term appreciation.
* **Bar Charts:** Comparing market volume across different Indian cities.
* **Scatter Plots:** Isolating property sizes against financial valuations.

### 1. Area vs Price by Not-Pool
![Scatter Plot](https://github.com/codenoob5311/Real-Estate-Data-Analysis/blob/main/Area-Price.png) 

### 2. Location vs Count by Furnished
![Scatter Plot](https://github.com/codenoob5311/Real-Estate-Data-Analysis/blob/main/Location-Count.png)

---

