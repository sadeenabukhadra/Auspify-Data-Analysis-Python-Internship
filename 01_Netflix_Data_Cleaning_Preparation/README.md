# Task 1: Netflix Data Cleaning & Preparation

## Overview

This task focuses on cleaning and preparing the Netflix dataset for further business analysis and reporting.

The goal is to improve data quality by identifying missing values, checking duplicate records, standardizing categorical columns, and exporting a clean dataset ready for analysis.

---

## Objectives

- Import the Netflix dataset using Python and Pandas.
- Explore the dataset structure and data types.
- Identify and handle missing values.
- Check and analyze duplicate records.
- Standardize categorical columns:
  - Country
  - Rating
  - Type
- Export the cleaned dataset for further analysis.

---

## Dataset Information

- **Dataset Name:** Netflix Titles Dataset
- **Number of Records:** 8,790
- **Number of Columns:** 10

### Columns

| Column | Description |
|--------|-------------|
| show_id | Unique identifier for each title |
| type | Content type (Movie / TV Show) |
| title | Title name |
| director | Director name |
| country | Country of production |
| date_added | Date added to Netflix |
| release_year | Release year |
| rating | Content rating |
| duration | Movie duration or number of seasons |
| listed_in | Content categories |

---

## Data Cleaning Process

### 1. Data Import

The dataset was imported using Pandas and loaded into a DataFrame for analysis.

### 2. Dataset Exploration

The dataset structure was explored to understand:
- Number of records and columns.
- Data types.
- Available features.
- Data completeness.

### 3. Missing Values Analysis

Missing values were checked using Pandas.

**Result:**
- No missing values were detected in the dataset.
- No missing value treatment was required.

### 4. Duplicate Records Analysis

Complete duplicate rows were checked.

**Result:**
- No duplicate records were found.

Additional analysis was performed on duplicated titles. Some titles appeared more than once, but they had different `show_id` values, meaning they represented separate records and were not removed.

### 5. Data Standardization

Text columns were checked and cleaned to ensure consistency.

The following columns were standardized:

- **Country**
  - Removed extra spaces.
  - Ensured consistent capitalization.

- **Rating**
  - Removed extra spaces.
  - Ensured uppercase formatting.

- **Type**
  - Checked content categories.
  - Ensured consistent naming (`Movie`, `TV Show`).

---

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab

---

## Project Files

Netflix_Data_Cleaning_&_Preparation_task1.ipynb

Complete notebook containing the cleaning process and analysis.


netflix_cleaned.csv

Cleaned dataset exported after preprocessing.


screenshots/

Screenshots showing the cleaning and verification steps.

---
Screenshots showing the cleaning and verification steps.

---

## Conclusion

The Netflix dataset was successfully cleaned and prepared for business analysis.

The final dataset contains consistent formatting, no missing values, and no duplicate records, making it ready for further exploratory data analysis and visualization tasks.
