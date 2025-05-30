# Task-4-factory-optimization-lp
A Linear Programming project to maximize profit using Python and PuLP.


 🏭 Factory Profit Optimization using Linear Programming

This project solves a business problem to **maximize profit** for a factory producing two products by using **Linear Programming (LP)** with the Python library **PuLP**.

## 📌 Problem Statement

The factory produces two products:

 **Product A**  
  - Requires 2 hours of machine time per unit  
  - Requires 3 units of raw materials per unit  
  - Profit of ₹40 per unit  

 **Product B**  
  - Requires 4 hours of machine time per unit  
  - Requires 2 units of raw materials per unit  
  - Profit of ₹50 per unit  

### Available Resources:
- Maximum 100 hours of machine time  
- Maximum 90 units of raw materials  

## 🎯 Objective

Maximize total profit, calculated as:  
Profit = 40 * A + 50 * B

Subject to constraints:  
2A + 4B ≤ 100 (Machine Time Limit)
3A + 2B ≤ 90 (Raw Material Limit)
A, B ≥ 0 (Non-negative integers)

## 💻 How the Code Works

- We define decision variables `A` and `B` representing units to produce for Product A and B.  
- The objective function maximizes total profit.  
- Constraints ensure production does not exceed available resources.  
- The PuLP solver finds the optimal production quantities.  

## ✅ Sample Output

🔎 Optimization Status: Optimal
✅ Units of Product A to produce: 20.0
✅ Units of Product B to produce: 15.0
💰 Maximum Profit: ₹ 1550.0

📊 Business Insight:
To maximize profit, the factory should produce the above units of Product A and B within the available resources.


## ▶️ How to Run

1. Open the provided Jupyter Notebook or Google Colab file.  
2. Run all the code cells; PuLP will be installed automatically.  
3. View the printed output for the optimal production plan and profit.  


## 📌 Internship Task

This code is submitted as **Task 4** of a Data Science Internship to demonstrate solving a real business optimization problem using Python and Linear Programming.

