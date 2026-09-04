# Data Validation & Conditional Formatting

## Project Overview
This project focuses on improving data quality and analysis clarity for an **employee performance dataset** using Excel's **Data Validation**, **formulas (IFS)**, **sorting**, and **Conditional Formatting**.

The goal was to move beyond "getting a formula to work" and instead ensure the *results made logical sense* catching and correcting a classification inconsistency in the process.

## What Was Done
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/fb282ea5-404b-4151-a7c6-98f69432b45c" />


### 1. Data Validation
Added dropdown restrictions and input rules to prevent invalid entries and maintain data integrity at the point of entry.

### 2. Achievement Analysis
Calculated achievement percentage by comparing **Sales Achieved** against **Monthly Target**.

### 3. Achievement Status Classification
Employees were classified into four categories based on their achievement:
- **Below Target**
- **Near Target**
- **Target Achieved**
- **Target Exceeded**

### 4. Performance Status
Built a clearer performance classification that combines the employee's **rating** with their **actual achievement**, rather than relying on rating alone.

### 5. Data Quality Check — Review Date
While reviewing the Review Date column, older dates were found appearing after more recent ones. Dates were sorted in **descending order (newest to oldest)** to create a consistent, logical timeline.

### 6. Conditional Formatting
Applied formatting rules to visually flag high and low performance levels at a glance.

## Key Lessons

- Noticed that an employee could hold an **"Excellent"** performance rating while still falling **below** their sales target — a mismatch that raised questions about the original classification logic rather than accepting it at face value.
- Reviewed and rebuilt the logic using the **`IFS`** function to create a Performance Status that reflects the *actual relationship* between rating and target achievement.
- Reinforced that data analysis isn't just about formulas running correctly — it's about verifying that the output makes sense.

## Final Achievement Status Distribution

| Status | Count |
|---|---|
| Target Exceeded | 121 |
| Target Achieved | 6 |
| Near Target | 26 |
| Below Target | 97 |

## Skills Demonstrated
- Excel Data Validation
- Logical formulas (`IFS`)
- Sorting & data consistency checks
- Conditional Formatting
- Data quality auditing / critical review of outputs

## Tools
- Microsoft Excel

## Contact
📩 [Email](mailto:adeyosoye37@gmail.com)

🔗 [Linkedin](https://www.linkedin.com/in/daniel-y-/)

💬 [Chat on Whatsapp](https://wa.me/2348141512158)
