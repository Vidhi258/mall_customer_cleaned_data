# Task 1: Data Cleaning and Preprocessing

## Dataset:
Mall Customer Segmentation Data  
Source: Kaggle  
File: Mall_Customers.csv

---

## Cleaning Steps Applied:

1. **Removed Missing Values**  
   - Checked using `.isnull().sum()`  
   - No missing values found

2. **Removed Duplicate Rows**  
   - Used `.drop_duplicates()` to clean repeated entries

3. **Standardized Text Columns**  
   - Converted 'Gender' values to lowercase for consistency

4. **Renamed Column Headers**  
   - Replaced spaces with underscores and changed to lowercase

5. **Fixed Data Types**  
   - Converted `age`, `annual_income_(k$)`, and `spending_score_(1-100)` to `int`

---

## Challenges Faced:

- Some column names included special characters like `(k$)`  
  → Kept as-is to preserve meaning but ensured they're valid for Python syntax

---

## Tools Used:

- **Language:** Python  
- **Library:** Pandas

---

## Output:

- Cleaned dataset saved as `mall_customers_cleaned.csv`
