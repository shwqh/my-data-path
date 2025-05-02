# 📊 Filtering, Sorting, and Basic Analysis Functions

In this lab, I practiced how to manage and analyze data in Excel using key tools and functions. I focused on **controlling data display** and extracting **useful insights**.

---

### ✨ Skills practiced

| Skill | Description |
|--------|------------|
| 🔍 Filtering | Used basic and custom filters to view specific data |
| 📑 Sorting | Organized data using multi-level sorting |
| ✅ IF / IFS | Applied logic functions to analyze data conditions |
| 🔢 COUNTIF | Counted cells meeting a condition |
| ➕ SUMIF / SUMIFS | Summed values based on single/multiple conditions |

---

### 🛠️ Hands-on Activities

#### Exercise 1: Filtering and Sorting
- Applied Auto Filter to show only:
  - "Frequent" purchase status
  - "Cancelled" transactions
  - "Desktop" purchase touchpoints
- Cleared filters to return full view
- Used custom filter to show top 50 orders by value
- Applied Custom Sort by:
  - Shipping date (Ascending)
  - Order value (Descending)

#### Exercise 2: Key Functions
- `=IF(AE2="Complete","Yes","No")`: Check if the order is complete
- `=IF(AD2>300,"Large",IF(AD2>100,"Medium",IF(AD2>0,"Small")))`: Classify order size
- `=IFS(...)`: Simplified multiple condition check
- `=COUNTIF(N2:N195,"VISA")`: Counted how many customers used a VISA card
- `=SUMIF(...)`: Summed order values where size is "Large"
- `=SUMIFS(...)`: Summed "Large" orders from "Baby Boomers"

---

### 📎 Attached File: [ Lab3.xlsx][Download Excel File](https://github.com/shwqh/my-data-path/raw/main/Excel-Labs/Lab3.xlsx)
Includes all the tasks and formulas applied in this lab.

---
 
> This exercise helped strengthen my ability to:
> - View and filter data with more control
> - Use logic-based formulas
> - Perform analysis useful in real-world business scenarios
