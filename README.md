# Airbnb NYC Listing Analysis (2019)

**Category:** Data Importing and Cleaning Projects  
**Goal:** Clean and summarize Airbnb listings data from multiple file formats to support business insights.

---

##  Project Description

New York City is one of the most visited cities in the world, and Airbnb offers thousands of listings to meet that demand. This project explores 2019 Airbnb listings by combining data from:

- `airbnb_price.csv` (listing prices)
- `airbnb_room_type.xlsx` (room descriptions)
- `airbnb_last_review.tsv` (review dates)

---

## Questions Answered

1. What are the **earliest and most recent review dates**?
2. How many listings are **private rooms**?
3. What is the **average listing price**, rounded to 2 decimal places?
4. Can these insights be summarized into a single-row DataFrame?

---

##  Tools Used

- Python 3
- pandas
- numpy
- CSV, TSV, and Excel file handling
- Data cleaning (text replacement, type conversion)
- Summary statistics

---

##  Output

A single-row summary DataFrame:

| first_reviewed | last_reviewed | nb_private_rooms | avg_price |
|----------------|---------------|------------------|-----------|
| 2019-01-01     | 2019-07-09    | 11,356           | 141.78    |

---
