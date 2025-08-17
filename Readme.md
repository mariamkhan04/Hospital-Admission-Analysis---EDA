# Project: Understanding Patient Admission Patterns

## 📌Problem Statement

A city hospital wants to analyze its admission trends to improve scheduling, reduce waiting times, and manage resources more effectively.
The dataset contains anonymized patient admission records, and the goal is to perform Exploratory Data Analysis (EDA) to uncover useful patterns.

## 🎯 Objectives

- Practice EDA using Pandas and visualization libraries.
- Identify trends in admissions by gender, age, department, and room type.
- Summarize insights using plots and tables.

## 📊 Dataset Details

- **Dataset Name:** Hospital Admissions Data
- **Link:** https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data
- **Rows:** 15,757
- **Columns (after cleaning):**

    - patient_id → Unique identifier for each patient
    - age → Age of the patient
    - gender → Gender (M/F)
    - admission_type → Admission type (E = Emergency, OPD = Outpatient)
    - admission_date → Date of admission
    - previous_visits → Indicator if patient had prior visits (0 or 1)
    - admission_day → Day of the week (derived from admission date)

## 🛠️ Steps Performed

- **Data Cleaning & Preprocessing**
    - Selected only relevant columns.
    - Renamed columns for clarity.
    - Converted admission dates to datetime.
    - Extracted admission_day.
    - Checked for missing & duplicate values.

- **EDA Questions**
    1. What is the total number of admissions?
    2. What is the distribution of gender among admitted patients?
    3. Which age group is most frequently admitted?
    4. What are the most common admission types?
    5. On which day of the week do most patients get admitted?
    6. What percentage of patients have visited before (previous_visits > 0)?
    7. Is there a difference in admission types across genders?
    8. Create 3+ visualizations to represent interesting patterns in the data.

- **Visualizations using Matplotlib**

## Key Insights
- Analyzed **14,348** hospital admissions.
- **Male patients (63%)** were admitted more than females.
- The **66+ age group** had the highest hospitalization rate.
- **Emergency admissions (9,934)** far exceeded OPD (4,414).
- Admissions peaked in **January** and were highest on **Mondays**.

## 📌 Tools & Libraries Used

- **Python**
- **Pandas** → Data wrangling and analysis
- **Matplotlib** → Data visualization
- **Jupyter Notebook** → Interactive analysis

## 🚀 How to Run

1. **Clone this repo:**

```bash
git clone https://github.com/mariamkhan04/Hospital-Admission-Analysis---EDA.git
cd Hospital Admission Analysis - EDA
```

2.  **Install dependencies:**
```bash
pip install pandas matplotlib jupyter
```

3.  **Open the notebook:**
```bash
jupyter notebook EDA.ipynb
```

## 👩‍💻 Author

[Mariam Khan](https://www.linkedin.com/in/mariam-khan0424/)