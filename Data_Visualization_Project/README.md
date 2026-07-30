# 🦠 Data Visualization Project: COVID-19 Patient Outcomes Analysis

An end-to-end data visualization project analyzing patient-level COVID-19 data to uncover which
demographic and clinical factors are most strongly associated with mortality. The project includes
data cleaning, exploratory data analysis (EDA), 10 analytical questions with interactive visualizations,
and a Streamlit dashboard.

---

## 📌 Project Overview

This project explores the **COVID-19 Patient Dataset** (Mexican Ministry of Health) using Python and
Plotly. The objective is to extract meaningful insights about who is most at risk from COVID-19, and to
present them through interactive charts and a dashboard.

The project demonstrates a complete data analysis workflow:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Interactive Dashboard Development
- GitHub Project Documentation

---

## 🎯 Objectives

- Clean and preprocess the dataset.
- Perform exploratory data analysis (EDA).
- Identify which demographic groups and pre-existing conditions carry the highest mortality risk.
- Analyze how age, sex, and pre-existing conditions relate to outcomes.
- Explore hospitalization, ICU admission, and death trends over time.
- Build an interactive Streamlit dashboard for data exploration.

---

## 📊 Dataset

**Dataset:** COVID-19 Patient Dataset (Mexican Ministry of Health)

The dataset contains patient-level records, including:

- Age
- Sex
- Patient Type (outpatient / hospitalized)
- Pre-existing conditions (diabetes, COPD, asthma, hypertension, obesity, and more)
- Pregnancy status
- ICU admission status
- COVID-19 diagnostic classification
- Date of death (or survival indicator)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Plotly Express
- Streamlit
- Jupyter Notebook
- Git & GitHub

---

## 📈 Exploratory Data Analysis

The notebook answers several business questions, including:

1. How does mortality rate vary by age group and sex?
2. Does mortality rate increase with the number of pre-existing conditions?
3. Which pre-existing condition has the highest mortality rate?
4. Does obesity or diabetes drive mortality more, and what happens when a patient has both?
5. Among hospitalized patients, is ICU admission more common for men than women?
6. Which medical unit has the highest ICU utilization?
7. How did weekly deaths trend over time for hospitalized vs. outpatient cases?
8. Do pregnant women face a higher mortality risk than non-pregnant women of the same age?
9. Does the number of pre-existing conditions differ between patients who survived and those who died?
10. Which combination of age and condition count carries the highest mortality risk?

Each visualization includes a brief explanation and insight.

---

## 📊 Streamlit Dashboard Features

The interactive dashboard includes:

- 🧍 KPI Cards
- 🔍 Sidebar Filters
- 📊 Mortality Rate by Age Group
- 🚻 Mortality Rate by Sex
- 🩺 Mortality Rate by Pre-Existing Condition
- 📈 Weekly Deaths Over Time
- 📄 Interactive Data Table
- 📥 Download Filtered Dataset

---

## 📂 Project Structure

```
Data_Visualization_Project_COVID19_Analysis/
│
├── README.md
├── requirements.txt
├── app.py
├── COVID_Data_Analysis.ipynb
├── Covid_Data.csv
└── images
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Data_Visualization_Project_COVID19_Analysis.git
```

Navigate to the project folder:

```bash
cd Data_Visualization_Project_COVID19_Analysis
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the Streamlit dashboard:

```bash
streamlit run app.py
```

---

## 📷 Dashboard Preview

You can add screenshots of your dashboard here.

Example:

```
images/dashboard.png
```

---

## 📌 Key Insights

- Mortality rises sharply from age 50 onward, and men have a higher mortality rate than women at every age group.
- Mortality rate climbs steadily with each additional pre-existing condition.
- Chronic kidney disease has the highest mortality rate of any single pre-existing condition.
- Diabetes drives mortality risk more than obesity does.
- Age outweighs pre-existing condition count as a mortality risk factor.

---

## 👨‍💻 Author

*Tanisha Chaudhary*
Github - https://github.com/Tanisha2621/dataviz-excercises-TanishaChaudhary

---

## ⭐ If you found this project useful, consider giving it a star!
