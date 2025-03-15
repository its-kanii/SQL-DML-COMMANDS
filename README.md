# **SQL DML Commands with Real-Time Examples**  

📌 This repository contains **SQL DML (Data Manipulation Language) commands** with real-time examples to help you learn how to manage data effectively in a database.  

---

## **📖 Table of Contents**  
- [📌 Introduction](#-introduction)  
- [🛠️ SQL DML Commands](#️-sql-dml-commands)  
  - INSERT  
  - UPDATE  
  - DELETE  
  - SELECT  
- [💡 Real-Time Example: Employee Management System](#-real-time-example-employee-management-system)  
- [📌 Use Cases](#-use-cases)  
- [🚀 How to Run](#-how-to-run)  
- [📬 Contribution](#-contribution)  

---

## **📌 Introduction**  
SQL **DML commands** allow us to manipulate and retrieve data within a database. This repository provides hands-on examples using a simple **Employee Management System**.  

---

## **🛠️ SQL DML Commands**  

### 🔹 **INSERT Command**  
📌 Adds new records to a table.  
```sql
INSERT INTO Employees (EmpID, Name, Age, Department, Salary)  
VALUES (1, 'Alice Johnson', 30, 'HR', 60000);
```

---

### 🔹 **UPDATE Command**  
📌 Modifies existing records.  
```sql
UPDATE Employees  
SET Salary = 85000  
WHERE EmpID = 2;
```

---

### 🔹 **DELETE Command**  
📌 Removes records from a table.  
```sql
DELETE FROM Employees  
WHERE EmpID = 3;
```

---

### 🔹 **SELECT Command**  
📌 Retrieves data from a table.  
```sql
SELECT * FROM Employees;
```

---

## **💡 Real-Time Example: Employee Management System**  

A company needs to:  
✅ **Add** employees when hired  
✅ **Update** salaries after appraisals  
✅ **Delete** records when employees leave  
✅ **Fetch** employee details  

🔹 **Use the provided SQL queries to manage employee data effectively.**  

---

## **📌 Use Cases**  
💼 **HR Systems:** Employee database management  
🛍️ **E-Commerce:** Product & customer data handling  
🏦 **Banking Systems:** Managing transactions  
🏥 **Healthcare:** Patient record updates  

---

## **🚀 How to Run**  
1️⃣ Install MySQL/PostgreSQL/SQLite on your system.  
2️⃣ Clone the repository:  
   ```bash
   git clone https://github.com/its-kanii/SQL-DML-COMMANDS.git
   ```  
3️⃣ Open your SQL database and execute the scripts.  

---

## **📬 Contribution**  
👨‍💻 Want to improve this repo? Fork it, make changes, and submit a pull request!  
📩 Have questions? Open an issue or connect with me on **[LinkedIn](https://www.linkedin.com/in/kanimozhi-kathirvel-3630182a5/)**.  

---

### **⭐ Don't forget to Star the Repo if you find it useful!** 🚀  


