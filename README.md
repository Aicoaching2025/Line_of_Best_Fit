# 📈 Finding the Best-Fitting Line

This project uses **linear regression** to find the best **slope (`m`)** and **intercept (`b`)** for a dataset.

## 🎯 Problem Statement
We want to find the best **linear equation**:

\[
y = mx + b
\]

that minimizes the **total error** for a given dataset.

## 🛠️ How the Code Works
1️⃣ **Calculate the line equation** → `get_y(m, b, x)`  
2️⃣ **Compute errors** → `calculate_error(m, b, point)`  
3️⃣ **Find total error for a line** → `calculate_all_error(m, b, points)`  
4️⃣ **Test multiple lines** → `possible_ms` and `possible_bs`  
5️⃣ **Find the best line** → Loops through all possible `(m, b)` values  
6️⃣ **Make predictions** → `get_y(best_m, best_b, 6)`

## 📊 Data Visualization
The project visualizes **different lines** and how well they fit the data.

## 🚀 How to Run the Code
1️⃣ Clone the repository:
   ```bash
   git clone https://github.com/aicoaching2025/linear-regression.git
