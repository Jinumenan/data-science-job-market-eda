# Data Science Job Market EDA

This project explores a dataset of data-related jobs.  
I focus only on **Exploratory Data Analysis (EDA)** to understand salary trends and job characteristics.  
No machine learning model is used in this project.

---

## 📂 Dataset

The dataset contains job listings with columns like:

- `work_year` – year of the job (e.g., 2023)
- `job_title` – role title (e.g., Data Scientist, Data Analyst)
- `job_category` – type of job or domain
- `salary_currency` – currency of the salary (e.g., USD, EUR)
- `salary` – salary in original currency
- `salary_in_usd` – salary converted to USD
- `employee_residence` – country where the employee lives
- `experience_level` – level like junior, mid, senior, etc.
- `employment_type` – full-time, part-time, contract, etc.
- `work_setting` – remote, hybrid, or in-person
- `company_location` – country where the company is located
- `company_size` – size of company (e.g., S, M, L)

> Note: Column names may slightly differ based on the original dataset.

---

## 🎯 Project Goals

The main goals of this EDA project are:

1. Understand the **salary distribution** in data jobs.
2. Compare salaries by:
   - experience level  
   - work setting (remote / hybrid / onsite)  
   - job title  
   - company size  
3. Understand how job market is spread across:
   - locations  
   - experience levels  
   - job types  

This project is useful for beginners who want to study the data science job market.

---

## 🛠️ Tools & Technologies

- **Language**: Python
- **Libraries**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
- **Environment**:
  - Jupyter Notebook / JupyterLab

---

## 📁 Project Structure (example)

```text
project-folder/
│
├── data/
│   └── data_science_jobs.csv        # dataset file
│
├── notebooks/
│   └── job_market_eda.ipynb         # main EDA notebook
│
├── output/
│   └── charts_and_plots/            # (optional) saved images
│
├── README.md
└── requirements.txt
