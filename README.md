# Healthcare Data Analysis

Exploratory data analysis of a healthcare dataset using Python, Pandas and visualization libraries.

## Project overview

This project analyzes a healthcare dataset using Python.  
The goal was to clean the data and explore patient demographics, diagnoses, hospital stay length, billing amounts and test results.

The project demonstrates basic data cleaning, exploratory data analysis, grouping, aggregation and data visualization skills.

## Tools used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains healthcare records including patient age, gender, diagnosis, admission type, billing amount, hospital stay length and test results.

The original dataset in this project comes from Kaggle.
Source:  [Healthcare Dataset on Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)
The original dataset is stored in the `data/raw` folder.
The cleaned dataset used for exploratory data analysis is stored in the `data/processed` folder.

## License

The dataset is available on Kaggle under the CC0: Public Domain license.

## Project structure

```text
healthcare-data-analysis
│
├── data
│   ├── raw
│   │   └── healthcare_dataset_original.csv
│   │
│   └── processed
│       └── healthcare_dataset_cleaned_added_columns.csv
│
├── notebooks
│   ├── 01_data_cleaning.ipynb
│   └── 02_eda.ipynb
│
└── README.md
```

## Data cleaning
The cleaning process included:
- loading the dataset,
- checking missing values,
- removing duplicates,
- converting date columns to datetime format,
- standardizing patient names,
- exporting the cleaned dataset.

## Analysis questions
The analysis focused on:
1. What is the age distribution of patients?
2. How are patients distributed by gender?
3. What are the most common diagnoses?
4. How does hospital stay length differ by diagnosis and admission type?
5. How do billing amounts differ by diagnosis, insurance provider and admission type?
6. How do test results differ by diagnosis and age group?

## Key Findings

- The original dataset contained 55,500 records. After removing duplicate rows, 54,966 records were analyzed.
- The dataset does not contain missing values.
- Patients’ ages range from 13 to 89 years. The age distribution is relatively even, with the most frequent age group being 61–70 years.
- Gender distribution is almost balanced, with a very similar number of male and female patients.
- Medical conditions are distributed very evenly across the dataset. Arthritis is the most frequent condition, but the differences between diagnoses are small.
- Diagnoses do not show a strong difference by gender or age group.
- The average billing amount is similar across medical conditions, insurance providers, and admission types. The highest average billing amount is associated with Obesity, Medicare, and Elective admissions, but the differences are small.
- The average length of hospitalization is approximately 15.5 days.
- Hospital stay length does not differ substantially by diagnosis or admission type.
- A noticeably higher number of patients stayed exactly 30 days, which may indicate that 30 days is an upper limit in the dataset.
- Test results are relatively balanced across medical conditions and age groups.
- Overall, the dataset appears to be highly balanced, which may indicate a synthetic or artificially generated dataset.

## Project status
The data cleaning and exploratory data analysis are completed.  
The next step is to create a Power BI dashboard.```
