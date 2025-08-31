# 🧠 Sprint 5 – SQL Mastery: Products & Books Domain
 
**Sprint:** 5  
**Focus:** SQL validation, joins, aggregates, and exploratory testing  
**Tables Used:** `products_data`,`company_data`,   
**Tags:** `SQL` `QA Testing` `Manual Validation` `products` `books` `Exploratory Testing`

---

In Sprint 5, I completed a comprehensive round of SQL testing across the **products** and **books** domains. Through hands-on querying, I explored and validated backend data relationships, pricing logic, and edge cases. This sprint marked a turning point in my QA journey — I now understand **all ends of SQL** and can confidently apply it to real-world testing scenarios.

### ✅ SQL Concepts I Mastered

- **SELECT statements** – precise column targeting for validation  
- **WHERE clauses** – filtering by unit, price, date, and null conditions  
- **JOINs** – verifying foreign key relationships across tables  
- **GROUP BY** – aggregating data by store, author, and date  
- **Aggregate functions** – using `SUM()`, `COUNT()`, and `AVG()` for business logic checks  
- **Aliasing** – renaming fields for clarity in test reports  
- **Negative testing** – surfacing anomalies and edge cases  
- **Date filtering** – validating time-based logic and weekend sales  
- **Exploratory testing** – crafting queries to uncover unexpected patterns


📄 **External SQL Work Samples**  
See additional queries and JOIN/HAVING exercises in this [Google Doc](https://docs.google.com/document/d/1mGMcFIa3NeycO1iCLvTcQ5lg2QinnjyAocPOPtKJM4w/edit?tab=t.0) for Sprint 5 validation work.


### 🧪 Sample Queries

#### 1. Filter Products by Unit and Price Range

```sql
SELECT 
    name, 
    name_store
FROM 
    products_data
WHERE 
    units NOT IN ('pt', 'oz', 'gal')
AND price BETWEEN 5 AND 10;


### 🧪 Sample Queries

#### 1. Filter Products by Unit and Price Range

```sql
SELECT 
    name, 
    name_store
FROM 
    products_data
WHERE 
    units NOT IN ('pt', 'oz', 'gal')
AND price BETWEEN 5 AND 10;


### 🧪 Sample Queries

###🧪 Categorize Fund Activity and Analyze Investment Strategy 

SELECT  
   CASE 
    WHEN invested_companies >= 100 THEN 'high_activity'
    WHEN invested_companies >= 20 THEN 'middle_activity'
    WHEN invested_companies < 20 THEN 'low_activity' 
   END AS categories, 
   ROUND(AVG(investment_rounds))
FROM  
   fund 
GROUP BY 
   categories
ORDER BY 
   ROUND(AVG(investment_rounds))

     
