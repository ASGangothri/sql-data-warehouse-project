# SQL Data Warehouse Project

This project demonstrates a complete end-to-end **Data Warehouse (DWH)** workflow, including data ingestion, staging, transformation, modeling, and quality checks across Bronze, Silver, and Gold layers.

I built this project to understand how real data engineering pipelines work using:
- SQL
- ETL concepts
- Data modeling
- Data quality validation
- Multi-layer architecture (Bronze → Silver → Gold)

---

## 📌 Project Architecture
The warehouse is designed in 3 layers:

### **1. Bronze Layer**
Raw data loaded exactly as received  
✔ Minimal processing  
✔ Data stored in CSV files  
✔ Used mainly for ingestion

### **2. Silver Layer**
Cleaned and standardized data  
✔ Null-handling  
✔ Type corrections  
✔ Deduplication  
✔ Business-ready fields

### **3. Gold Layer**
Final analytics tables  
✔ Dimension & fact model  
✔ Business metrics  
✔ Ready for dashboards and reporting

---

## 📂 Project Folder Structure
---
datasets/ → Raw data (CSV files)
docs/ → Architecture diagrams
images/ → ERD & flow images
scripts/ → SQL scripts for transformations
sql/ → DDL + DML scripts
tests/ → Data quality checks

## 🛠️ SQL Scripts Included

### **🔹 Bronze Scripts**
- `dd_bronze.sql`
- `proc_load_bronze.sql`

### **🔹 Silver Scripts**
- `dd_silver.sql`
- `proc_load_silver.sql`
- `quality_checks_silver.sql`

### **🔹 Gold Scripts**
- `dd_gold.sql`

---

## 🧪 Data Quality Tests
Located inside `tests/` folder.

Checks include:
- Duplicate primary keys  
- Null values  
- Invalid dates  
- Incorrect relationships  
- Data format/standardization issues  

---

## 🧱 Data Models and Diagrams

All architecture diagrams are stored inside:

docs/
images/


Includes:
- ERD diagrams  
- Data flow diagram  
- ETL workflow chart  
- Layered warehouse structure  

---

## 🚀 How to Run the Project
1. Load CSVs into Bronze tables  
2. Run Bronze → Silver transformation scripts  
3. Run Silver quality checks  
4. Load Silver → Gold tables  
5. Validate all data using `tests/` scripts  

---

## 🎯 What I Learned
This project helped me understand:
- Multi-layer warehouse architecture  
- Writing clean SQL for ETL pipelines  
- Automating transformations  
- Designing dimension & fact tables  
- Creating data quality validation scripts  

---

## 📌 Future Enhancements
- Add stored procedures for Gold layer  
- Implement orchestration using Airflow  
- Add Power BI dashboard on Gold Layer  

---

## 📧 Contact
**A S Gangothri**  
Feel free to connect with me regarding this project!
