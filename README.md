

## ⚽ Football Premier League Standings 

### 📖 Overview

This project demonstrates a complete **data pipeline** that extracts real-time Premier League standings from the **TheSportsDB API**, transforms the data using **Python (pandas)**, and loads it into a **MySQL database** for storage and analysis.

The project follows a clean **REST API → DataFrame → SQL** workflow — applying key data engineering concepts such as data extraction, transformation, validation, and database integration.

---

### 🧩 Tech Stack

* **Python** 🐍
* **pandas** – for data manipulation and transformation
* **requests** – for API communication
* **MySQL** – for structured data storage
* **Git & GitHub** – for version control and collaboration

---

### ⚙️ Features

✅ Fetches live Premier League standings from TheSportsDB API
✅ Cleans and transforms JSON responses into structured DataFrames
✅ Renames and filters columns for clarity and relevance
✅ Converts data types for analytical consistency
✅ Inserts or updates records in a MySQL database using UPSERT logic
✅ Hides sensitive credentials (like API keys) using environment variables
✅ Fully automated ETL flow ready for reuse across APIs

---

### 🧠 Key Learnings

* How to **build an end-to-end ETL pipeline** from a REST API into SQL
* The importance of **data validation and type conversion** before loading
* Using **environment variables** to safely manage secret keys
* Writing **idempotent database operations** (no duplicate rows) using SQL UPSERT
* Strengthening understanding of **API integration**, **data cleaning**, and **database connectivity** in Python

