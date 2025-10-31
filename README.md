# Titanic-Exploratory-Data-Analysis-EDA-
This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset, exploring passenger demographics, survival trends, and correlations between key variables. The goal is to extract insights using statistical summaries and visualizations to better understand which factors influenced survival rates.
🎯 Objectives

Load and inspect the Titanic dataset

Identify missing values and data quality issues

Explore relationships between features such as Age, Sex, Pclass, and Fare

Visualize data distributions and correlations

Summarize findings and insights

🧰 Tools & Libraries

Python 3

Pandas – for data manipulation and analysis

Matplotlib & Seaborn – for data visualization

NumPy – for numerical operations

ReportLab – for generating the PDF report

📂 Files Included
File Name	Description
Titanic_EDA.ipynb	Jupyter Notebook with all EDA steps
train.csv	Original Titanic dataset
Titanic_EDA_Full_Report.pdf	Final PDF report summarizing visual and statistical findings
plots/	Folder containing generated visualizations (histograms, heatmaps, etc.)
📊 Steps Performed

Data Loading & Inspection

Used .info(), .describe(), .value_counts() to understand structure and types.

Data Cleaning

Handled missing values (Age, Embarked, Cabin).

Statistical Summary

Computed numerical summaries and class-wise survival statistics.

Visual Analysis

Histograms for Age & Fare

Boxplots for Fare distribution

Countplots for Survival by Sex and Class

Scatterplots for Age vs Fare

Correlation Heatmap

Observations

Females had higher survival rates

Higher-class passengers had better survival chances

Fare is right-skewed (some very high values)

Age is missing for ~20% of records

📈 Key Insights

Sex & Class are strong predictors of survival

Fare and Age show meaningful variation across survivors

Cabin data is mostly missing but may carry latent patterns (deck info)

Embarked column has minor missing data easily filled by mode

📜 Deliverables

✅ Jupyter Notebook (.ipynb)

✅ PDF Report (Titanic_EDA_Full_Report.pdf)

✅ Supporting dataset (train.csv)

🚀 How to Run
# Clone the repository
git clone https://github.com/yourusername/Titanic-EDA.git
cd Titanic-EDA

# Open in Jupyter Notebook
jupyter notebook Titanic_EDA.ipynb

# Or run directly as Python script (optional)
python Titanic_EDA.py
📚 Summary of Findings

Survival is positively correlated with passenger class and fare.

Female passengers had much higher survival rates.

The dataset requires preprocessing before modeling (handling missing values, encoding categorical variables).

The EDA lays a solid foundation for predictive modeling (e.g., Logistic Regression, Random Forest).
