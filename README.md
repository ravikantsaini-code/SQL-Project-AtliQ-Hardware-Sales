# 🗄️SQL-Project-AtliQ-Hardware-Sales

**Project Summary**

Designed and implemented a high-performance SQL analytics framework for a global hardware manufacturer to automate sales reporting workflows. Migrated critical business logic from manual Excel-based processes to scalable Stored Procedures and User Defined Functions (UDFs), reducing reporting turnaround time by 95% while creating a centralized and reliable “Single Source of Truth” for stakeholders across global markets.

# [View SQL Project PDF](SQL%20Project.pdf)

# 💻Technical Execution

This project was designed using a Star Schema architecture optimized for scalable analytical workloads and high-performance reporting.

**1. Fiscal Logic Standardization (UDFs)**
Developed custom User-Defined Functions (UDFs) to automate fiscal-year calculations and temporal transformations aligned with the company’s September–August fiscal calendar. This eliminated inconsistencies between calendar-based and fiscal-based reporting across datasets.

**2. Optimized Analytical Views**
Built reusable SQL Views such as gross_sales and net_sales to abstract complex joins and business logic from the reporting layer. This improved maintainability, simplified analytics workflows, and enabled faster query execution for large-volume datasets.

**3. Dynamic Business Classification Engine**
Implemented parameter-driven Stored Procedures such as get_market_badge to automate market segmentation and performance classification using threshold-based business rules. Markets were dynamically categorized into tiers like “Gold” and “Silver” based on sales volume criteria.

# Tech Stack
**Database & Querying**
* MySQL
* SQL
* Relational Database Management Systems (RDBMS)
* Database Design

**SQL Skills**
* Joins & Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* Aggregate Functions
* Views
* Stored Procedures
* User-Defined Functions (UDFs)
* Query Optimization
