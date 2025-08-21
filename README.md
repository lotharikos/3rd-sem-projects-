# 📊 Exploratory Data Analysis of COVID-19 (Worldometer Snapshot - August 2020)

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a static snapshot of **COVID-19 data (August 2020)** from [Worldometer](https://www.worldometers.info/coronavirus/).  
The goal is to uncover insights into the global pandemic trends, with a focus on **country-wise differences, continent-level comparisons, and normalized per-capita statistics**.  

This project is part of my **data analytics portfolio**, showcasing my skills in:
- Data cleaning & preprocessing
- Handling missing values with different strategies
- Visualizations using Python libraries
- Storytelling with data insights

---

## 🛠️ Tools & Libraries
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical computations
- **Matplotlib & Seaborn** – visualizations

---

## 📂 Repository Structure
3rd-sem-projects/
│
├── data/
│ └── worldometer_data.csv # raw dataset (snapshot from August 2020)
│
├── notebooks/
│ └── EDA_Covid19.ipynb # Jupyter notebook with full analysis
│
└── README.md # project documentation



---

## 🔎 Key Steps in the Analysis
1. **Data Understanding**
   - Load dataset, inspect columns, check shape
   - Explore country-level and continent-level data

2. **Data Cleaning**
   - Handle missing values:
     - Imputation with median/mode (small/moderate gaps)
     - Dropping highly incomplete columns
   - Standardize column formats (remove commas, cast to numeric)

3. **Exploratory Data Analysis**
   - Global overview: top 10 countries by cases & deaths
   - Distribution of cases/deaths across continents
   - Normalized comparisons: cases & deaths per million population
   - Outlier detection (countries with extreme metrics)

4. **Visualization**
   - Bar plots, boxplots, and scatter plots
   - Heatmaps for correlation between key variables
   - Highlighted insights with clean visual storytelling

---

## 📈 Expected Insights
- Which continents and countries were most affected (absolute vs per-capita terms)
- Variations in testing rates and mortality ratios
- Identification of unusual data patterns or outliers

---

## 🚀 Usage
Clone the repository:
```bash
git clone https://github.com/lotharikos/3rd-sem-projects.git
 ## ⚠️ Disclaimer

This dataset is a static snapshot from August 2020 and is used strictly for educational purposes.
It does not represent live or current COVID-19 data.
