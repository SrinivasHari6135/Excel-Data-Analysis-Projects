# Customer Feedback Data Cleaning

An Excel data-cleaning project that transforms messy, inconsistent customer feedback data into a clean, structured dataset ready for analysis.

## Problem

The raw feedback export had several common real-world data quality issues:
- Full names stored as a single messy field with inconsistent/extra spacing (e.g. `"Sneha   Rao"`)
- Missing rating values (blank cells where customers didn't leave a score)
- No status tracking for follow-up on feedback

## What Was Done

- **Split** the raw "Full Name" field into separate **First Name** and **Last Name** columns
- **Cleaned** inconsistent whitespace in name fields
- **Handled missing ratings** by filling gaps so every record has a usable value
- **Added a Status column** (`New`, `In Progress`, `No Action Needed`) to track review/follow-up state for each feedback entry

## What's Inside

- **Customer Feedback** — The original raw dataset (50 records) as received, kept for reference.
- **Updated Customer Feedback** — The cleaned dataset with split names, corrected ratings, and an added Status column.

## Skills Demonstrated

- Data cleaning (text splitting, whitespace handling)
- Handling missing/null values
- Structuring data for downstream analysis
- Adding derived/tracking columns

## Tools Used

Microsoft Excel
