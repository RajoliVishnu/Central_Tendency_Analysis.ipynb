# Central_Tendency_Analysis.ipynb
Exploratory Data Analysis of Wine Quality dataset focusing on central tendency, distribution analysis, and feature correlations using Python.
📊 Wine Quality Analysis
Central Tendency & Exploratory Data Analysis

Day 19 – Data Analysis Internship
🔎 Project Overview

This project focuses on performing exploratory data analysis (EDA) on the Wine Quality dataset with emphasis on central tendency measures and feature distribution analysis.

The objective is to understand how statistical measures such as mean, median, and mode summarize data behavior and how different physicochemical properties relate to wine quality.

📁 Dataset Information

The dataset contains physicochemical attributes of white wine samples along with a quality rating assigned to each sample.

Key Features:

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

Quality (Target Variable)

🎯 Objectives

Perform structured exploratory data analysis

Compute central tendency measures (Mean, Median, Mode)

Analyze feature distributions

Detect skewness and outliers

Examine correlation between variables

Interpret relationships influencing wine quality

🔄 Methodology
1️⃣ Data Loading & Inspection

Imported dataset using Pandas

Examined dataset shape and columns

Checked data types and structure

Verified presence of missing values

2️⃣ Descriptive Statistics

Generated summary statistics using .describe()

Calculated Mean, Median, and Mode

Compared values to identify skewness

3️⃣ Distribution Analysis

Visualized feature distributions using histograms

Evaluated symmetry and spread

Observed skewed variables

4️⃣ Outlier Detection

Used boxplots to identify extreme values

Analyzed variability across features

5️⃣ Correlation Analysis

Generated correlation matrix

Visualized relationships using heatmap

Identified positive correlation between alcohol and quality

📈 Key Insights

Majority of wine samples fall within mid-range quality scores.

Alcohol content shows a positive association with wine quality.

Certain features such as residual sugar exhibit right-skewed distribution.

Outliers are present in acidity-related variables.

Central tendency comparison helps in understanding distribution patterns effectively.

🛠 Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Environment: Jupyter Notebook

▶ How to Run the Project
1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Open the notebook in Jupyter
4. Run all cells

🚀 Learning Outcome

This project strengthened understanding of:

Descriptive statistics

Distribution analysis

Skewness interpretation

Correlation analysis

Data visualization techniques

📌 Internship Context

Completed as part of Day 19 of the Data Analysis Internship program, focusing on applying statistical foundations to real-world datasets using Python.
