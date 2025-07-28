# 🚖 NYC Taxi Dataset Analysis (PySpark on Google Colab)

## 📌 Project Overview
This project analyzes NYC Yellow Taxi trip data using **PySpark** on **Google Colab**.  
The dataset is in **Parquet** format and contains trip details such as fare, passenger count, trip distance, and vendor information.

---

## ✅ Features Implemented
1. Load NYC taxi data from Parquet into PySpark DataFrames.
2. (Optional) Flatten nested JSON fields.
3. Perform analytical queries:
   - Add a new column `Revenue`.
   - Calculate total passengers in NYC by area.
   - Compute average fare & earnings by vendor.
   - Moving count of payments by payment mode.
   - Find top 2 gaining vendors by date.
   - Identify the route with most passengers.
   - Get top pickup locations in the last 5/10 seconds.

---

## 🛠️ Technologies Used
- **Google Colab** (Python Environment)
- **Apache Spark 3.x** with PySpark
- **Parquet File Format**

---

## 🚀 How to Run the Project
1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook and copy the provided code from `nyc_taxi_analysis_colab.py` (or use the notebook file).
3. Upload the required Parquet datasets when prompted.
4. Run all cells sequentially.
5. View query results directly in the notebook.

---

## 📂 Project Structure
