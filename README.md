# Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python

This project demonstrates how to generate a simple sales summary using a tiny SQLite database in Python. It includes:
- Running SQL queries using `sqlite3`
- Loading data into a Pandas DataFrame
- Displaying total quantity sold and revenue per product
- Visualizing the revenue with a basic bar chart using `matplotlib`

---

## 🔧 Tools Used
- Python 3
- SQLite (via `sqlite3`)
- Pandas
- Matplotlib

---

## 📂 Dataset

The SQLite database `sales_data.db` contains one table: `sales` with the following schema:
- `id`: Primary Key
- `product`: Product name (TEXT)
- `quantity`: Quantity sold (INTEGER)
- `price`: Unit price (REAL)

---

## 📈 Output

The script:
1. Connects to the database
2. Runs a query to get total quantity and revenue per product
3. Prints the summary table
4. Plots a revenue bar chart

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies (if not already installed):
   ```bash
   pip install pandas matplotlib

## run the script
python sales_summary.py

## output
  product  total_qty  revenue
0   Apple         15     37.5
1  Banana         30     30.0
2  Orange         20     30.0
