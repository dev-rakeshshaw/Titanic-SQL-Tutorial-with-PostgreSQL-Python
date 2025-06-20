# 🛳️ Titanic SQL Tutorial: 50 Expert Queries with Python & PostgreSQL

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![PostgreSQL](https://img.shields.io/badge/Powered%20by-PostgreSQL-336791)](https://www.postgresql.org/)
[![Notebook Ready](https://img.shields.io/badge/Notebook-Jupyter-orange)](Titanic_SQL_Tutorial_Full_50_Queries.ipynb)

> A comprehensive, beginner-to-advanced SQL practice notebook using the classic Titanic dataset — executed entirely through SQLAlchemy in Python.

---

## 🚀 What You'll Learn

- 📊 SQL query writing from basic counts to complex aggregations
- 🧠 Real-world use of PostgreSQL functions like `GROUP BY`, `CASE`, `WINDOW`, `JOIN`, and `percentile_cont()`
- 🔄 Executing SQL queries from Python using SQLAlchemy
- 🧹 Data exploration, cleaning insights, and survival analysis
- 📚 Structuring a Python+SQL notebook for both teaching and portfolio use

---

## 🧾 What’s Inside

The Jupyter Notebook includes:

✅ 50 SQL queries — each with:
- 📝 Clear Markdown explanation
- 📌 Real SQL example
- ⚙️ Executed via SQLAlchemy Python function `run_query()`

📘 Topics Covered:
- Data aggregation & filtering
- Conditional logic with `CASE`
- Statistical analysis (e.g., average, median, standard deviation)
- Text parsing (titles, cabins)
- Data quality checks (missing/nulls)
- Real-world patterns like family size, fare-per-person, gender ratios, and class-wise analysis

---

## 📂 File Structure
📦 Titanic-SQL-Tutorial/
├── Titanic_SQL_Tutorial_Full_50_Queries.ipynb ← 📘 Core tutorial notebook
├── README.md ← 👋 You are here
├── titanic.csv ← 📄 Original dataset

---

## 🛠️ Requirements

- Python 3.7+
- PostgreSQL installed locally or remotely
- pip install pandas sqlalchemy psycopg2
- Titanic dataset imported into a PostgreSQL table named `titanic`
