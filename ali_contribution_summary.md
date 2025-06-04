
# 📊 PDF Comparison Automation

## 🔧 What I Did

This script automates the comparison of financial PDF reports (BEFORE vs AFTER) and exports the results to Excel.

### ✅ Key Contributions

- Created `extract_table_lines()` function to extract structured table lines using regex.
- Updated `Check_3()` to run only on one specific report pair for isolated testing.
- Used `PyPDF2` to extract raw text from PDFs.
- Wrote comparison logic to identify missing rows between BEFORE and AFTER versions.
- Used `pandas` and `openpyxl` to write output to `Table_Comparisons.xlsx`.
- Configured `Expected_Values.py` with custom folder paths.
- Verified successful runs using print statements and Excel validation.
- Manually recreated expected folder structure to match legacy repo logic.
- Prepared all code for team review in a GitHub branch (`ali-branch`).
- Learned how to manage GitHub commits and uploads manually without Git CLI access.

### 📁 Files Modified

- `Check_3_Raw_Text_Processing.py`
- `Expected_Values.py`

### 📦 Output

- `Table_Comparisons.xlsx` — contains discrepancy results
- Logs printed to terminal showing matched/missing rows

### 🔁 Next Steps

- Scale logic across all report types
- Reuse extractor pattern with flexible split markers
- Push clean version to public repo for portfolio

---

🛠️ _Ali, 2025_
