# Indian Startup Funding — Decoded

Pandas + EDA project analyzing a deliberately messy dataset of Indian startup funding records (Flipkart, Zomato, Paytm, BYJU'S, Razorpay, and 80+ others). Built as part of **The Unlox Academy's Week 2 curriculum**, focused on taking real-world messy data — inconsistent column names, mixed-case categories, currency strings, multi-format dates — and turning it into clean, analysis-ready data.

## What's in here

- **`Week2_Assessment_RishiBhuta.ipynb`** — full notebook covering:
  - **Theory** — core pandas concepts (Series vs DataFrame, `.loc` vs `.iloc`, `SettingWithCopyWarning`, `pd.cut()` vs `pd.qcut()`, etc.)
  - **Output prediction** — reasoning through pandas behavior before running code
  - **Applied EDA** — a full cleaning pipeline followed by filtering, derived columns, grouping/aggregation, and business-style questions (e.g. identifying "emerging players," city-level investment hubs, market saturation by city + industry)
- **`indian_startups_funding.csv`** — the raw dataset (468 records, intentionally messy)

## Cleaning pipeline

The raw data required:
- Standardizing column names to snake_case
- Normalizing city aliases (e.g. Bangalore/BLR → Bengaluru, Bombay → Mumbai)
- Standardizing industry and funding-stage category variants
- Parsing currency strings (₹, INR, Cr, Crore, commas) into numeric values
- Parsing dates across multiple formats
- Removing duplicate rows

## Stack

Python, pandas, NumPy

## Author

Rishi Bhuta — Diploma in Computer Engineering, Thakur Polytechnic, Mumbai
