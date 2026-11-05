# Customer Personality Analysis – Data Cleaning and Preprocessing

## Project Overview
This project focuses on cleaning and preprocessing the Customer Personality Analysis dataset using Python and Pandas.

The objective is to improve data quality by identifying and handling missing values, duplicate records, inconsistent text formats, incorrect data types, and potential outliers.

## Dataset Information
- **Dataset Name:** Customer Personality Analysis
- **Source:** [Kaggle – Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- **Original Records:** 2,240
- **Total Columns:** 29

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Data Cleaning Steps

1. **Data Inspection:** Examined dataset structure, column names, data types, and statistical summaries.
2. **Missing Values:** Identified 24 missing values in the Income column and replaced them using median imputation.
3. **Duplicate Records:** Checked for duplicate rows. No duplicates were found.
4. **Text Standardization:** Standardized text formatting and removed unnecessary spaces.
5. **Column Names:** Converted column names into lowercase for consistency.
6. **Date Conversion:** Converted the Dt_Customer column into datetime format.
7. **Outlier Detection:** Used the Interquartile Range (IQR) method to identify potential income outliers. Investigated an unusually high value of 666666 and replaced it with the median income.
8. **Final Validation:** Verified missing values, duplicate records, and data types.

## Project Files

| File | Description |
|---|---|
| `Task_1_Data_Cleaning.ipynb` | Jupyter Notebook containing the cleaning process |
| `cleaned_marketing_campaign.csv` | Final cleaned dataset |

## Results
- 2,240 records retained.
- 29 columns retained.
- Missing values reduced to zero.
- No duplicate records.
- Text values and column names standardized.
- Date column converted to the correct format.
- Potential outlier investigated and treated.

## Conclusion
The dataset was successfully cleaned and validated using Python and Pandas. The resulting dataset is structured and ready for further exploratory data analysis.

---

**Project:** Data Analyst Internship – Task 1  
**Focus:** Data Cleaning and Preprocessing
