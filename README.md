# Elevate-Task-3

# Task 3: SQL for Data Analysis - ElevateLabs Internship

## 📌 Objective:
Use SQL queries to extract and analyze data from a database.

##  Tools Used:
- MySQL Workbench
- Ecommerce Dataset (imported)

## 🗂 Dataset Used:
A custom ecommerce dataset with columns:
Github Account
`ProductID`, `ProductName`, `Category`, `Price`, `Rating`, `NumReviews`, `StockQuantity`, `Discount`, `Sales`, `DateAdded`.

---

## ✅ Queries Performed:

### 1. Basic SELECT, WHERE, ORDER BY, GROUP BY
```sql
SELECT ProductName FROM ecommerce WHERE Category = 'Electronics';
SELECT Category, COUNT(*) AS TotalProducts FROM ecommerce GROUP BY Category;
