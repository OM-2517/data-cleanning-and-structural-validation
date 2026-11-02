# Data Cleaning & Structural Validation


## Project Overview

This project focuses on transforming raw, unstructured data into a clean, consistent, and reliable format suitable for data analysis.

The objective is to identify and handle common data quality issues, including duplicate records, missing values, inconsistent formats, and invalid entries, while preserving data integrity.

The project demonstrates a structured data cleaning and validation process using Python and Pandas.

## Objectives

* Identify and remove duplicate records.
* Detect and handle missing values.
* Standardize inconsistent data formats.
* Validate data types and structural constraints.
* Identify invalid records and preserve them for review.
* Generate a clean dataset ready for further analysis.

## Dataset

The project uses a synthetic retail transaction dataset containing deliberately introduced data quality issues.

The dataset includes the following attributes:

* Invoice Number
* Stock Code
* Description
* Quantity
* Invoice Date
* Unit Price
* Customer ID
* Country

**Note:** The dataset is synthetic and is used for demonstrating data cleaning techniques. It does not represent actual customer transactions.

## Tools and Technologies

| Tool             | Purpose                                           |
| ---------------- | ------------------------------------------------- |
| Python           | Data processing and automation                    |
| Pandas           | Data cleaning and manipulation                    |
| NumPy            | Numerical operations                              |
| Jupyter Notebook | Interactive analysis and documentation            |
| Excel            | Reviewing cleaning results and validation reports |

## Methodology

### 1. Initial Data Assessment

* Inspected the dataset structure and column data types.
* Identified missing values and duplicate records.
* Examined data inconsistencies and invalid entries.

### 2. Data Cleaning

* Removed exact and confirmed duplicate records.
* Standardized text fields and date formats.
* Handled missing values using appropriate methods.
* Identified invalid records and separated them for review.

### 3. Structural Validation

* Verified data types and required fields.
* Checked for duplicate transaction identifiers.
* Validated numerical values and date formats.
* Confirmed that the cleaned dataset followed the defined validation rules.

### 4. Results and Reporting

* Generated the cleaned dataset.
* Created a cleaning log and validation report.
* Documented the cleaning process and its results.

## Project Results

The cleaning process produced a final dataset containing 934 records.

| Metric                                   | Result |
| ---------------------------------------- | -----: |
| Initial records                          |    985 |
| Exact duplicates removed                 |     15 |
| Additional normalized duplicates removed |     14 |
| Invalid records quarantined              |     22 |
| Final cleaned records                    |    934 |
| Structural validation checks passed      |    9/9 |

The cleaning process preserves the original dataset and separates invalid records for further review.

## Repository Structure

```text
Data-Cleaning-Structural-Validation/
│
├── README.md
├── raw_retail_transactions.csv
├── cleaned_retail_transactions.csv
├── cleaning_log.csv
├── quarantined_records.csv
├── validation_results.csv
├── Task1_Data_Cleaning_Results.xlsx
├── Task1_Data_Cleaning_Report.pdf
├── Task1_Data_Cleaning_Report.docx
├── task1_cleaning_pipeline.py
└── task1_data_cleaning_notebook.ipynb
```

## How to Run the Project

### Step 1: Clone the repository

```bash
git clone <your-repository-url>
```

### Step 2: Navigate to the project directory

```bash
cd Data-Cleaning-Structural-Validation
```

### Step 3: Install the required libraries

```bash
pip install pandas numpy
```

### Step 4: Run the Python script

```bash
python task1_cleaning_pipeline.py
```

Alternatively, open the Jupyter Notebook in Google Colab or Jupyter Notebook and execute the cells sequentially.

## Deliverables

* Raw dataset
* Cleaned dataset
* Python cleaning pipeline
* Jupyter Notebook
* Data cleaning log
* Quarantined records
* Structural validation results
* Final project report

## Conclusion

This project demonstrates how systematic data cleaning and structural validation can improve data quality and reliability.

By identifying duplicates, handling missing values, standardizing formats, and validating structural constraints, the project produces a dataset suitable for further analysis while maintaining transparency and data integrity.

---

**Project:** Data Cleaning & Structural Validation
