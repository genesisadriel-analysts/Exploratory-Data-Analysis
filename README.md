# 📊 Developer Survey EDA
End-to-End Data Analysis Project | Python • Pandas • Visualization
# 🚀 Overview

This project delivers a complete Exploratory Data Analysis (EDA) on a global developer survey dataset. It demonstrates how raw, messy data can be transformed into meaningful insights about compensation, experience, education, employment, remote work, and technology trends.

Designed to reflect a real-world data analyst workflow, this project highlights data cleaning, feature engineering, and insight-driven analysis.

## 📂 Dataset Description

The dataset contains 65,000+ survey responses from developers worldwide, covering:

* Demographics (Country, Education)
* Professional background (Experience, Employment)
* Work setup (Remote vs On-site)
* Compensation (ConvertedCompYearly)
* Technical skills (Programming languages)

## ⚠️ Challenges addressed:

* Missing values across critical columns
* Inconsistent categorical data
* Multi-select fields (semicolon-separated values)
* Skewed numerical distributions (salary)

## 🧹 Data Preparation & Feature Engineering
* Performed missing value analysis and applied targeted imputation strategies
* Cleaned and standardized categorical variables (e.g., EdLevel, Country)
* Converted YearsCodePro into numeric format for analysis
* Created a new feature: ExperienceLevel (Junior, Mid, Senior, Expert)
* Applied one-hot encoding for multi-value columns (Employment, Languages)
* Reduced category noise for better visualization clarity
## 📊 Key Analyses & Insights

## 📈 Experience vs Job Satisfaction
* Weak correlation observed between experience and job satisfaction
* Indicates satisfaction is influenced by multiple non-linear factors

## 😊 Job Satisfaction Distribution
* Wide variability across respondents
* Suggests diverse work environments and career experiences

## 🌍 Remote Work Trends
* Strong adoption of remote work across various roles
* Reflects the ongoing shift toward flexible work models

## 💻 Programming Languages by Region
* Clear regional differences in language popularity
* Highlights geographic influence on tech stack preferences

## 🎓 Education vs Employment Type
* No strict dependency between higher education and employment type
* Suggests skills and experience often outweigh formal education

## 📈 Key Learnings
* Real-world datasets require significant preprocessing
* Multi-value categorical data needs advanced handling techniques
* Visualization clarity is critical for effective communication
* Insight generation requires both technical and analytical thinking

## 🛠️ Tech Stack
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
📁 Project Structure

      📦 developer-survey-eda
      ┣ 📜 Exploratory Data Analysis.ipynb
      ┣ 📜 survey-data.csv
      ┗ 📜 README.md

## ▶️ How to Run
      git clone https://github.com/your-username/developer-survey-eda.git
      cd developer-survey-eda
      jupyter notebook

## 💼 Business Value
This analysis provides insights that can support:
* 📊 Salary benchmarking and compensation analysis
* 🧑‍💻 Workforce and hiring strategy
* 🌍 Remote work policy decisions
* 💻 Technology adoption trends

 ## 🚀 Future Improvements

* Perform advanced statistical analysis (correlation, regression)
* Build interactive dashboards (Power BI / Tableau)
* Apply machine learning for predictive modeling
* Enhance visual storytelling for executive-level reporting
## 👤 Author

Genesis Adriel Segovia
Data Analyst | Python • Data Cleaning • EDA • Visualization
