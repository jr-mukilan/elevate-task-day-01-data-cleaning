Elevate Labs – Day 01 Task: Data Cleaning and Preprocessing

 📅 Date:
May 26, 2025

🧠 Task Overview:
This task focused on cleaning and preprocessing a raw dataset using Google Sheets and Excel 2007.  
The dataset was synthetically generated to simulate real-world business data containing typical issues such as:
- Missing values
- Duplicate rows
- Inconsistent text formatting
- Varying date formats

 🛠️ Tools Used:
- Google Sheets
- Microsoft Excel 2007
- GitHub

📂 Files Included:
- `cleaned_dataset_day1_google_sheets.xlsx` – Final cleaned dataset
- `README.md` – Documentation of process

🔧 Cleaning Steps Performed:

1. **Missing Value Handling
   - Filled missing `Age` and `Spending_Score` using column averages.
   - Replaced missing `Country` entries with `"UNKNOWN"`.

2. Duplicate Removal
   - Removed exact duplicate rows using Google Sheets `Remove duplicates` feature.

3.Text Standardization
   - Converted all `Gender` entries to lowercase (`male`, `female`)
   - Converted all `Country` entries to uppercase (`INDIA`, `USA`, etc.)

4.Date Formatting
   - Standardized `Join_Date` column to `DD-MM-YYYY` format using Google Sheets custom date options.

5. Column Renaming
   - Cleaned all column names to lowercase with underscores for consistency.
   - Example: `Customer_ID` → `customer_id`

 📌 Notes:
- Dataset size: 100+ rows
- Dataset is synthetic and created for internship practice, based on Kaggle-like structure

📝 Learning Outcome:
This task helped me understand real-world data preprocessing using spreadsheets. I practiced identifying and resolving common data quality issues, making the data ready for analysis.

---

Submitted by: Mukilan J.R  
