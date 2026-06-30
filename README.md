# Global-Quality-of-Life-Analysis-using-Python

<h1 align="center">🌍 Global Quality of Life Analysis using Python</h1>

<p align="center">
  Exploratory Data Analysis and visualization of global quality of life indices across countries using Python.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge">
  <img src="https://img.shields.io/badge/Matplotlib-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
</p>

---

## 📌 Project Overview

This project performs exploratory data analysis on global quality of life indices by country.

The analysis focuses on understanding how different countries compare across quality of life, purchasing power, safety, healthcare, cost of living, property price, traffic commute time, pollution, and climate-related indicators.

The project uses Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn preprocessing tools.

---

## 🎯 Business Questions

This analysis aims to answer questions such as:

- Which countries have higher quality of life scores?
- How does cost of living vary across country rankings?
- What is the relationship between purchasing power and property price to income ratio?
- How is pollution related to traffic commute time?
- How are safety, healthcare, and quality of life indicators distributed?
- Which countries fall into good, average, or bad traffic commute categories?

---

## 📊 Dataset Information

The dataset contains quality of life indicators for multiple countries and years.

### Main Columns

| Column | Description |
|---|---|
| Rank | Country ranking based on quality of life indicators |
| Country | Country name |
| Quality of Life Index | Overall quality of life score |
| Purchasing Power Index | Purchasing power level |
| Safety Index | Safety score |
| Health Care Index | Healthcare quality score |
| Cost of Living Index | Cost of living score |
| Property Price to Income Ratio | Housing affordability indicator |
| Traffic Commute Time Index | Traffic and commute time indicator |
| Pollution Index | Pollution level |
| Climate Index | Climate-related score |
| Year | Year of record |

---

## 🛠️ Tools and Libraries Used

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis programming |
| Pandas | Data loading, cleaning, and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Label encoding for categorical variables |
| Jupyter Notebook | Interactive analysis environment |

---

## ✅ Project Workflow

- ✅ Imported required Python libraries
- ✅ Loaded the quality of life dataset
- ✅ Explored dataset shape, column types, and summary statistics
- ✅ Checked missing values
- ✅ Cleaned text columns such as country, climate index, and year
- ✅ Checked duplicate records
- ✅ Created multiple visualizations
- ✅ Created traffic status categories using traffic commute time
- ✅ Encoded categorical variables using LabelEncoder
- ✅ Built a correlation heatmap to understand feature relationships

---

## 📈 Visualizations Created

The notebook includes the following visual analysis:

- 📦 Boxplot of quality of life index by year
- 📈 Pollution index vs traffic commute time analysis
- 📊 Cost of living index by rank
- 📉 Safety index distribution
- 🔴 Purchasing power vs property price to income ratio regression plot
- 🚦 Traffic commute status classification
- 🌍 Country-wise traffic commute comparison
- 📊 Country-wise quality of life distribution
- 🔥 Correlation heatmap

---

## 🔍 Key Insights

Some insights from the analysis include:

- Countries show clear differences in quality of life, safety, healthcare, cost of living, and pollution indicators.
- Traffic commute time can be grouped into good, average, and bad categories.
- Most countries fall into the average traffic commute category.
- Purchasing power and property price to income ratio can be compared to understand housing affordability pressure.
- Correlation analysis helps identify relationships between quality of life factors such as safety, healthcare, pollution, and cost of living.

---

## 💼 Business Use Case

This project can support:

- 🌍 Country comparison analysis
- 🏙️ Relocation decision support
- 📊 Socio-economic research
- 🏢 International business expansion analysis
- 🧳 Immigration and lifestyle planning
- 🏡 Housing affordability comparison
- 🚦 Urban mobility and pollution analysis

The project can help analysts, researchers, students, and business teams understand how quality of life indicators vary across countries.

---

## 📁 Folder Structure

```text
global-quality-of-life-analysis/
│
├── README.md
├── notebook/
│   └── quality_of_life_analysis.ipynb
│
├── data/
│   └── quality_of_life_indices_by_country.csv
│
├── images/
│   ├── correlation-heatmap.png
│   ├── safety-index-distribution.png
│   └── traffic-pollution-analysis.png
│
└── docs/
    └── insights.md
🎯 What I Learned
✅ Loading and exploring datasets using Pandas
✅ Checking dataset shape, column types, and missing values
✅ Cleaning text-based columns
✅ Creating statistical visualizations using Seaborn and Matplotlib
✅ Building boxplots, histograms, bar charts, joint plots, KDE plots, and heatmaps
✅ Creating categorical groups using pd.cut()
✅ Encoding categorical variables using LabelEncoder
✅ Understanding relationships between numerical features using correlation analysis
✅ Preparing a Jupyter Notebook project for GitHub portfolio
🔮 Future Improvements
🔲 Fix and improve chart titles
🔲 Add more business-focused insights
🔲 Create country-level ranking tables
🔲 Add top 10 and bottom 10 country comparisons
🔲 Add year-wise trend analysis
🔲 Build a Power BI or Tableau dashboard from the same dataset
🔲 Add machine learning model to predict quality of life index
🔲 Deploy dashboard using Streamlit
👨‍💻 Author

Saran Kumar Krishnan

<p> <img src="https://img.shields.io/badge/GitHub-SaranStiff02-black?style=for-the-badge&logo=github"> <img src="https://img.shields.io/badge/Project-Python_EDA-green?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"> </p> ```
