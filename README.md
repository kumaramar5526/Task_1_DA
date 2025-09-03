# Data Cleaning and Preprocessing - Mall Customers Dataset

## Objective
The goal of this task was to clean and prepare the raw dataset by handling missing values, duplicates, inconsistent formats, and ensuring uniform column naming and data types.

## Steps Performed
1. **Loaded Dataset**  
   Imported the dataset using `pandas`.

2. **Removed Duplicates**  
   Used `.drop_duplicates()` to ensure no repeated rows.

3. **Handled Text Inconsistencies**  
   - Standardized `Gender` column to have only two consistent values: `Male` and `Female`.

4. **Renamed Columns**  
   Converted column names into a clean and uniform format:
   - `CustomerID` → `customer_id`  
   - `Gender` → `gender`  
   - `Age` → `age`  
   - `Annual Income (k$)` → `annual_income_k`  
   - `Spending Score (1-100)` → `spending_score`  

5. **Checked and Fixed Data Types**  
   Ensured numerical columns are integers and `gender` is categorical.

6. **Profiling Summary**  
   - Total Customers  
   - Average, Min, and Max of **Age**  
   - Average, Min, and Max of **Annual Income (k$)**  
   - Average, Min, and Max of **Spending Score**  

7. **Exported Cleaned Dataset**  
   Saved the final cleaned dataset as `Mall_Customers_Cleaned.csv`.

## Deliverables
- `Mall_Customers_Cleaned.csv` → Cleaned dataset  
- `TAsk_1_DA.ipynb` → Python script used for cleaning  
- `README.md` → This document summarizing the steps  

## Tools Used
- Python (Pandas)
