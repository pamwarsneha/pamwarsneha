
# ✈️ Travel Analysis Dashboard

This repository contains a Power BI dashboard designed to analyze customer travel data across occupations, designations, gender, and more. The goal is to derive actionable insights from the dataset to support business strategies related to marketing pitches and travel preferences.

## 📦 Data Source

- The dataset used was sourced from **Kaggle**.
- It contains anonymized information about customers, including:
  - Age, Monthly Income
  - Gender, Marital Status
  - Occupation & Designation
  - Number of Trips
  - Duration of Sales Pitch

## 📊 Dashboard Insights

This **Travel Analysis Dashboard** visualizes:

- 👤 **Customer Demographics**:
  - Total Sum of Age: `169K`
  - Total Sum of Monthly Income: `104M`
  - Gender distribution with marital status
- 💼 **Professional Profile**:
  - Segmentation by **Occupation** (Salaried, Small Business, Large Business, Freelancer)
  - Analysis by **Designation** (Executive, Manager, Sr. Manager, AVP, VP)
- 📈 **Performance Metrics**:
  - Sum of `NumberOfTrips`: `14K`
  - Average Order Value (AOV): `1169.5`
  - Duration of Sales Pitch by Designation
- 📉 **Charts Included**:
  - Bar chart: Monthly Income by Occupation
  - Pie chart: Gender and Marital Status
  - Donut chart: Duration of Pitch by Designation
  - Line chart: Designation vs Duration trend
  - Bar chart: Designation by Number of Trips

## 🧰 Tech Stack Used

| Tool/Technology | Purpose                                      |
|------------------|----------------------------------------------|
| **Power BI**     | Dashboard development and data visualization |
| **Microsoft Excel** | Data transformation & cleaning             |
| **DAX**          | Measures like AOV, Sum calculations, filtering |
| **Power Query**  | Data cleaning and transformation              |

## 🧹 Data Cleaning Techniques Used

- **Handling Nulls**: Removed or replaced missing values in `Income`, `Trips`, and `Pitch Duration`.
- **Type Conversion**: Converted numeric fields (e.g. income, trips) from text to appropriate data types.
- **Outlier Removal**: Detected and removed extreme values in pitch durations.
- **Column Standardization**: Renamed columns for consistency and readability.

## 🔎 Data Mining Skills Applied

- **Segmentation**: Occupation and designation-wise breakdown to understand target personas.
- **Trend Analysis**: Identified how pitch duration varies with seniority.
- **Cross-tabulation**: Used for gender-marital status combinations.
- **Aggregation**: Performed on KPIs like income, trips, and pitch duration to derive business metrics.
- **Behavioral Insights**: Mapped designations with travel activity frequency.

## 📁 Files Included

- https://github.com/pamwarsneha/pamwarsneha/blob/main/Travel%20Analysis.png: A snapshot of the complete Power BI dashboard.

## 🧑‍💼 Use Case

Perfect for analysts and business strategists aiming to:

- Optimize travel marketing strategies.
- Tailor sales pitches based on seniority levels.
- Understand income-wise customer segmentation.
- Improve targeting based on occupation and gender insights.

## 🚀 Getting Started (For Replication)

1. Download dataset from [Kaggle](https://www.kaggle.com/)
2. Clean and preprocess using Excel or Power BI Power Query.
3. Load data into Power BI and use DAX to build measures like:
   - `AOV = Total Revenue / Number of Trips`
4. Design dashboard visuals based on business goals.
5. Export as `.png` or `.pbix` for sharing and review.


<!--
**pamwarsneha/pamwarsneha** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
