# 🛒 Amazon Sales Analysis

## 📌 Project Overview

This project analyzes Amazon sales data using SQL to uncover key business insights related to revenue, customer behavior, and product performance.

* Cleaned and structured raw data
* Performed feature engineering (time, day, month)
* Solved 25+ business queries using SQL
* Generated insights for decision-making

---

## 🛠️ Tools & Technologies

* SQL (MySQL)
* Data Cleaning
* Data Analysis

---

## 🧹 Data Preparation

* Created database and table
* Imported dataset using MySQL Table Import Wizard
* Checked for null values
* Verified data integrity

---

## ⚙️ Feature Engineering

Added new columns to enhance analysis:

* **Time of Day** (Morning, Afternoon, Evening)
* **Day Name**
* **Month Name**

---

## 📊 Business Questions Solved

Some key questions answered:

* What is the count of distinct cities in the dataset?
* For each branch, what is the corresponding city?
* What is the count of distinct product lines in the dataset?
* Which payment method occurs most frequently?
* Which product line has the highest sales?
* How much revenue is generated each month?
* In which month did the cost of goods sold reach its peak?
* Which product line generated the highest revenue?
* In which city was the highest revenue recorded?
* Which product line incurred the highest Value Added Tax?
* For each product line, add a column indicating "Good" if its sales are above average, otherwise "Bad."?
* Identify the branch that exceeded the average number of products sold?
* Which product line is most frequently associated with each gender?
* Calculate the average rating for each product line?
* Count the sales occurrences for each time of day on every weekday?
* Identify the customer type contributing the highest revenue?
* Determine the city with the highest VAT percentage?
* Identify the customer type with the highest VAT payments?
* What is the count of distinct customer types in the dataset?
* What is the count of distinct payment methods in the dataset?
* Which customer type occurs most frequently?
* Identify the customer type with the highest purchase frequency?
* Determine the predominant gender among customers?
* Examine the distribution of genders within each branch?
* Identify the time of day when customers provide the most ratings?
* Determine the time of day with the highest customer ratings for each branch?
* Identify the day of the week with the highest average ratings?
* Determine the day of the week with the highest average ratings for each branch?


---

## 🔍 Key Insights

* 📈 Highest revenue was generated in **January**
* 🏙️ **Naypyitaw** recorded the highest sales
* 🛍️ **Food and Beverages** generated the highest revenue
* 💳 **E-wallet** is the most preferred payment method
* 👩 Female customers are slightly more dominant
* 🧾 **Members** contribute more revenue than normal customers

---

## ▶️ How to Run

1. Create a database in MySQL:

   ```sql
   CREATE DATABASE amazon;
   USE amazon;
   ```

2. Create table using provided SQL script

3. Import dataset using MySQL Import Wizard

4. Run SQL queries to analyze data


