**Fetch Data Analyst Take-Home - Read Me**

**Overview:**
This repository contains all deliverables and supporting files for the Fetch Data Analyst Take-Home Assignment. The assignment involved exploring, cleaning, and analyzing datasets provided by Fetch, followed by generating insights, visualizations, and stakeholder communication materials.

Repository Structure


Fetch - Data Analyst Take Home.docx - The final written report, including data exploration findings, SQL queries, analysis results, visualizations, assumptions, and stakeholder communication.
Fetch - Data Analyst Take Home.ipynb - Python script containing code to explore data, clean the datasets, load them into SQLite, run SQL queries, and generate visualizations. 
Cleaned_datasets.zip - A zipped folder containing the cleaned versions of the three datasets:  
- `PRODUCTS_TAKEHOME_CLEANED.csv`  
- `TRANSACTION_TAKEHOME_CLEANED.csv`  
- `USER_TAKEHOME_CLEANED.csv` |

**How to Use:**

1. Review the Final Report
Start by opening `Fetch - Data Analyst Take Home.docx` to review the complete analysis, insights, and recommendations.

2. Run the Analysis Script
To explore the data and re-run the queries, which:
- Loads the cleaned datasets into an in-memory SQLite database.
- Runs all analysis queries.
- Generates visualizations for key questions.
- Outputs findings to the console.

3. Data Files
The cleaned versions of the original datasets are provided in `Cleaned_datasets.zip`, which includes:
- PRODUCTS_TAKEHOME_CLEANED.csv (product information with missing data handled)
- TRANSACTION_TAKEHOME_CLEANED.csv (cleaned transaction data)
- USER_TAKEHOME_CLEANED.csv (user data with standardized dates and fields)

---

**Notes:**
- The SQL queries are designed to run within SQLite.
- All data exploration, cleaning, and visualization are handled in Python using pandas, matplotlib, and seaborn.
- If any assumptions or clarifications are needed, they are documented in the final Word report under Assumptions sections.
