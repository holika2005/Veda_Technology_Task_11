# Task 11 — Basic Data Sorting & Filtering (Sample Superstore)

## Objective
Use sorting and multiple filters to explore the **actual Sample Superstore dataset** and answer five simple business questions.

## Tools from the task
- Microsoft Excel
- Google Sheets (the `.xlsx` workbook can be uploaded to Google Sheets)

## Dataset used
The source is the Sample Superstore workbook previously provided (`sample_-_superstore (1)(2).xls`). It contains the original `Orders`, `People`, and `Returns` sheets. The Orders sheet contains 10,194 rows and 21 columns. The ZIP also includes the original `.xls` source file for traceability.

## Deliverables
- `Task_11_Superstore_Sorting_Filtering.xlsx`
  - **Raw Orders** — all original Orders records, preserved as the raw data copy.
  - **People** — original regional manager lookup.
  - **Returns** — original returns lookup.
  - **Filtered Data** — `Region = West` AND `Sales >= $100`, sorted by Sales from largest to smallest.
  - **5 Questions & Answers** — five answers calculated from the actual Orders sheet.
- `sample_-_superstore (1)(2).xls` — original source dataset.
- `README.md` — project notes and steps.

## How to reproduce the filter
1. Open the workbook in Excel, or upload it to Google Sheets.
2. Open `Raw Orders` and use the filter dropdowns.
3. Set **Region** to `West`.
4. Set **Sales** to **greater than or equal to 100**.
5. Sort **Sales** from largest to smallest.
6. Compare the result with `Filtered Data`.
7. Keep `Raw Orders` unchanged; use filters to hide rows instead of deleting records.

## Interview questions
- **When would you use filtering instead of deleting rows?** Filtering temporarily hides records that do not match criteria while preserving the full source for other analyses.
- **Why should raw data be preserved?** It keeps the analysis reproducible and makes it possible to verify results or recover from mistakes.

## Calculated check
- Total sales: $2,326,534.35
- Highest-sales region: West
- Highest-sales category: Technology
- Filter criteria: West region and sales of at least $100
