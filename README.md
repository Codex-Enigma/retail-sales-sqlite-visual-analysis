# 🛍️ Retail Sales Insights with SQLite & Python

A compact yet powerful data project that analyzes retail sales using **SQLite + Python**, and visualizes insights through **Bar, Line, and Pie charts**.  
Perfect for beginner analysts or portfolio projects that showcase SQL querying, data wrangling, and visual storytelling in Python.

---

## 📊 Project Highlights

| 🔍 Feature                      | ✅ Included |
|-------------------------------|-------------|
| SQLite Integration             | ✅ Yes       |
| SQL Queries via Python         | ✅ Yes       |
| Data Summary & Aggregation     | ✅ Yes       |
| Bar Chart (Top Product Revenue)| ✅ Yes       |
| Line Chart (Monthly Trend)     | ✅ Yes       |
| Pie Chart (Category Revenue)   | ✅ Yes       |

---

## 📁 Dataset

This project uses a **tiny SQLite database** (`sales_data.db`) with a single `sales` table containing:

- `product`
- `category`
- `quantity`
- `price`
- `date`

Data is fictional yet realistic, simulating sales across multiple product categories over several months.

---

## 🧠 What You’ll Learn

- How to use **SQLite with Python** via `sqlite3`
- Perform SQL queries directly from Python
- Summarize total revenue, quantity sold, and product/category trends
- Visualize data using **matplotlib** (`bar`, `pie`, and `line`)
- Annotate and label charts for storytelling

---

## 🛠️ Tech Stack

- **Python** (pandas, matplotlib, sqlite3)
- **SQLite** (local embedded database)
- Jupyter Notebook / .py script

---

## 🚀 Run the Project

```bash
# 1. Clone the repo or download the files
git clone https://github.com/Codex-Enigma/retail-sales-sqlite-python-visuals.git

# 2. Open Jupyter Notebook or run the script
jupyter lab
# or
python sales_analysis.py
