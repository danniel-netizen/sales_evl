### Project Assignment: Retail Sales, Returns & Repeat Customer Analysis

Build a **Retail Sales and Customer Analysis System** for a shop.

The shop maintains transaction data for all customer purchases. Your objective is to analyze the data using **SQL** first and then implement the same analysis using **Python**.

#### Business Requirements

The system should answer the following questions:

1. What is the total number of sales?
2. What is the total sales amount?
3. What is the total amount/value of returned items?
4. What is the net sales amount after considering returns?
5. Which products are sold the most?
6. Which products have the highest number of returns?
7. Which customers have purchased more than once?
8. How many times has each customer purchased?
9. What is the total amount spent by each customer?
10. Who are the highest-value customers?
11. What is the average order value?
12. What percentage of orders are returned?
13. Which products have a high return rate?
14. How many customers are repeat customers versus one-time customers?

### Phase 1 — SQL

Create a database and transaction table containing information such as:

* Order ID
* Customer ID
* Customer Name
* Product ID
* Product Name
* Category
* Purchase Date
* Quantity
* Unit Price
* Discount
* Payment Method
* Return Status

Use SQL to solve all the business questions above.

You should demonstrate:

* SELECT
* WHERE
* GROUP BY
* HAVING
* JOIN
* CASE
* Subqueries
* CTE
* Window functions
* Aggregate functions

### Phase 2 — Python

Load the same data into Python using Pandas.

Perform:

* Data cleaning
* Missing-value handling
* Duplicate detection
* Sales analysis
* Return analysis
* Customer analysis
* Product analysis
* Data visualization

Create charts showing:

* Monthly sales
* Monthly returns
* Top-selling products
* Products with highest returns
* Repeat customers
* Customer spending

### Phase 3 — Machine Learning

Extend the project into an ML problem.

Build a model to predict:

**1. Repeat Purchase Prediction**

Predict whether a customer is likely to purchase again based on their previous purchase behavior.

**2. Product Return Prediction**

Predict whether an order/item is likely to be returned based on available transaction and customer information.

Try models such as:

* Logistic Regression
* Decision Tree
* Random Forest

Evaluate the models using appropriate metrics such as:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### Expected Final Output

The final system should provide information such as:

```text
Customer: C001
Total Orders: 5
Total Spending: ₹24,500
Returned Orders: 1
Repeat Customer: Yes
Repeat Purchase Probability: 82%
```

And for products:

```text
Product: Jeans
Total Sold: 250
Total Returned: 35
Return Rate: 14%
Return Probability: 67%
```

### Important

The **same business problem and dataset should be solved first using SQL and then using Python**, so that the learner can understand the difference between:

**Database Analysis → Data Analysis → Machine Learning → AI Prediction**

Submit:

1. SQL table creation script
2. SQL analysis queries
3. Python notebook/script
4. ML model
5. Charts/visualizations
6. Short explanation of the findings
7. README explaining how to run the project


### Note:
Do not checkin/push to main branch , create pull request once done and ready for evaluation.
