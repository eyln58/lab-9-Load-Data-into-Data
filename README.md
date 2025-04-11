Loading and Managing Data in a Synapse Data Warehouse

## Overview

This lab focused on loading and managing data in a dedicated SQL pool within **Azure Synapse Analytics**, simulating real-world data warehouse scenarios. It covered loading data from a **data lake**, using **staging tables**, and applying **data transformation strategies** such as **CTAS** and **SCD (Slowly Changing Dimensions)**.

## 🧠 What I Did

- 📦 Loaded data from Azure Data Lake into **staging tables** using the high-performance `COPY INTO` statement
- ✅ Handled data validation by logging rejected rows for review
- 🏗️ Created dimension tables using `CREATE TABLE AS SELECT (CTAS)`
- 🔁 Implemented **Slowly Changing Dimension Type 1 & 2** logic:
  - Type 1: In-place updates
  - Type 2: Inserting new rows to preserve history
- ⚙️ Performed **post-load optimization**:
  - Rebuilt indexes
  - Created column statistics for improved query performance

## 🧰 Tools & Techniques Used

- Azure Synapse Analytics (Dedicated SQL Pools)
- Azure Data Lake Gen2
- T-SQL
- COPY INTO, CTAS, INSERT, UPDATE, SCD
- Index Rebuilding & Statistics Creation

## ✅ Key Takeaways

- Data Lake to Data Warehouse pipelines are seamless in Azure using `COPY INTO`
- Staging tables enable controlled data loading with validations
- SCD management is a core feature of reliable dimensional modeling
- Post-load optimization is essential for ensuring performance

---

📎 **Connect with me on Linkedin**: [https://www.linkedin.com/in/eyilan/]
