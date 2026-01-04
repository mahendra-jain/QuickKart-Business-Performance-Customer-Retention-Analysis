# QuickKart-Business-Performance-Customer-Retention-Analysis

## Tools Used
- **Python** – Primary programming language
- **Pandas** – Data manipulation and cleaning
- **Word2Number** – Converting textual numbers to numeric
- **Datetime module / pd.to_datetime** – Standardizing date columns

---

- ## Key Steps in Data Cleaning
1. **Handle Missing Values**
   - Identified and either dropped or imputed missing rows in critical columns.
2. **Standardize Date Columns**
   - Converted mixed-format dates into a consistent `YYYY-MM-DD` format using `pd.to_datetime` and multi-format parsing.
3. **Convert Textual Numbers to Numeric**
   - Converted words like `three`, `fifty` into numeric values using the `word2number` library.
4. **Categorize Data**
   - Added derived columns, e.g., `rating_category` based on numeric ratings.
5. **Column Reorganization**
   - Rearranged columns for better readability and downstream analysis.
6. **Type Conversions**
   - Ensured all columns have correct datatypes for analysis (e.g., `int`, `float`, `datetime`).
