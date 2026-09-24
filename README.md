# BANKING SYSTEM DATABASE 

## Project Overview

The **Banking System Database** is a MySQL-based database project developed to demonstrate practical skills in **SQL, relational database design, data analysis, and business-oriented querying**.

The project covers the complete database workflow, including database and table creation, defining relationships, inserting data, modifying structures, and performing analytical queries to extract meaningful insights from banking data.

---

## Objectives

* Design and implement a relational banking database using MySQL
* Create tables with appropriate primary and foreign key relationships
* Manage and manipulate structured banking data
* Perform data analysis using SQL queries
* Answer business-oriented questions using relational data
* Apply advanced SQL concepts for analytical use cases
* Strengthen problem-solving and analytical thinking using SQL

---

## Database Structure

The database contains multiple entities representing different aspects of a banking system.

| Table          | Description                                  |
| -------------- | -------------------------------------------- |
| `CUSTOMERS`    | Stores customer information                  |
| `ACCOUNTS`     | Stores customer account details and balances |
| `TRANSACTIONS` | Stores account transaction records           |
| `BRANCHES`     | Stores banking branch information            |
| `LOANS`        | Stores customer loan information             |

### Entity Relationships

```text
CUSTOMERS
    |
    +---- ACCOUNTS ---- BRANCHES
    |         |
    |         +---- TRANSACTIONS
    |
    +---- LOANS
```

These relationships allow data to be analyzed across customers, accounts, transactions, branches, and loans.

---

## Technologies Used

* MySQL
* SQL
* MySQL Workbench
* Relational Database Management
* Database Design
* ER Diagram / Data Modeling

---

## SQL Concepts Demonstrated

### Database and Table Management

* `CREATE DATABASE`
* `CREATE TABLE`
* `ALTER TABLE`
* `DROP TABLE`
* `ADD COLUMN`
* `MODIFY`
* `DESCRIBE`
* `SHOW TABLES`

### Data Manipulation

* `INSERT`
* `SELECT`
* `UPDATE`
* `DELETE`

### Constraints and Relationships

* Primary Keys
* Foreign Keys
* `NOT NULL`
* `UNIQUE`
* Referential Relationships

### Filtering and Sorting

* `WHERE`
* `AND`
* `OR`
* `IN`
* `BETWEEN`
* `LIKE`
* `DISTINCT`
* `ORDER BY`
* `LIMIT`

### Aggregate Functions

* `COUNT()`
* `SUM()`
* `AVG()`
* `MAX()`
* `MIN()`
* `GROUP BY`
* `HAVING`

### Joins

* `INNER JOIN`
* `LEFT JOIN`
* `RIGHT JOIN`
* Multi-table joins

### String Functions

* `CONCAT()`
* `UPPER()`
* `LOWER()`
* `LENGTH()`
* `LEFT()`
* `RIGHT()`
* `SUBSTRING()`
* `SUBSTRING_INDEX()`
* `TRIM()`
* `REPLACE()`
* `LOCATE()`

### Mathematical Functions

* `ROUND()`
* `CEIL()`
* `FLOOR()`
* `ABS()`
* `MOD()`
* `POWER()`
* `SQRT()`
* `GREATEST()`
* `LEAST()`

### Date and Time Functions

* `YEAR()`
* `MONTH()`
* `MONTHNAME()`
* `DAY()`
* `DAYNAME()`
* `QUARTER()`
* `DATEDIFF()`
* `TIMESTAMPDIFF()`
* `DATE_FORMAT()`
* `DATE_ADD()`
* `DATE_SUB()`

### Conditional Analysis

* `CASE WHEN`
* Conditional categorization
* Customer classification
* Loan status classification

### Window Functions

* `ROW_NUMBER()`
* `RANK()`
* `DENSE_RANK()`
* `SUM() OVER()`
* `LAG()`
* `LEAD()`
* `PARTITION BY`

### Views

* Creating SQL views
* Reusable analytical queries

---

## Business Questions Analyzed

The project uses SQL to answer practical banking-related questions.

### Customer Analysis

* How can customer information be retrieved and transformed?
* How can customers be categorized based on age?
* Which customers have multiple loans?
* How can customer-level information be combined with account and loan data?

### Account Analysis

* What types of accounts are maintained?
* Which accounts have the highest balances?
* How many accounts are associated with each branch?
* What is the total account balance by branch?

### Transaction Analysis

* Which accounts have the highest transaction activity?
* What are the largest transactions?
* What is the total transaction amount for different periods?
* How can transactions be ranked by amount?
* How can transaction activity be analyzed over time?

### Branch Analysis

* Which branches have the highest number of accounts?
* Which branches manage the highest account balances?
* Which branches have greater transaction activity?
* How can branch-level banking performance be analyzed?

### Loan Analysis

* What is the average loan amount?
* Which loans have the highest interest rates?
* Which customers have multiple loans?
* What is the duration of each loan?
* How can loans be classified based on their status?
* How can loans be ranked based on loan amount?

---

## Advanced SQL Analysis

The project goes beyond basic SQL queries and applies advanced techniques for analytical purposes.

Window functions are used for:

* Ranking transactions and loans
* Generating row numbers
* Calculating running totals
* Comparing current and previous records
* Comparing current and next records
* Performing analysis within customer groups

Multi-table joins are used to combine information from customers, accounts, transactions, branches, and loans to generate more meaningful business insights.

---

## Project Structure

```text
Banking_System_DB/
│
├── Banking_System_DB.sql
│   └── Database creation, data insertion,
│       SQL queries and analysis
│
├── ER_Diagram.mwb
│   └── Entity Relationship Diagram
│
└── README.md
    └── Project documentation
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Samyakubale/Banking_System_DB.git
```

### 2. Open the SQL File

Open `Banking_System_DB.sql` using **MySQL Workbench** or another MySQL-compatible SQL environment.

### 3. Execute the Script

Run the SQL script to:

1. Create the database
2. Create the required tables
3. Define primary and foreign key relationships
4. Insert sample data
5. Execute analytical queries

### 4. Select the Database

```sql
USE Banking_System;
```

The individual queries can then be executed to explore the database and perform analysis.

---

## Key Learning Outcomes

This project helped strengthen practical understanding of:

* Relational database design
* Database normalization concepts
* Primary and foreign key relationships
* SQL querying
* Data aggregation
* Multi-table analysis
* Data transformation
* Business-oriented problem solving
* Advanced SQL functions
* Window functions
* Time-based analysis
* Analytical thinking

---

## Skills Demonstrated

**SQL | MySQL | Database Design | Data Analysis | Data Modeling | Joins | Aggregate Functions | Window Functions | Data Transformation | Business Analysis**

---

## About Me

I am a **Data Science and Analytics enthusiast** with a background in **Computer Engineering**, currently developing practical skills in **Data Analysis, SQL, Python, Machine Learning, Statistics, and Data Visualization**.

I am interested in using data to identify patterns, solve analytical problems, and generate meaningful insights that can support business decisions.

### Current Technical Focus

* SQL and MySQL
* Python
* Data Analysis
* Statistics
* Power BI
* Tableau
* Machine Learning
* Data Visualization

---

## Connect With Me

**GitHub:**
https://github.com/Samyakubale

**LinkedIn:**
https://www.linkedin.com/in/samyak-ubale

---

## Repository

**Banking System Database:**
https://github.com/Samyakubale/Banking_System_DB
