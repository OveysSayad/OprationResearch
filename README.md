# OprationResearch
# 🏭 Iran Khodro Production Line Optimization

This project models and solves a real-world production planning problem for Iran Khodro company using integer programming. The objective is to **maximize profit** by optimally selecting and operating production lines while meeting various real-world constraints such as limited capacity, market demand, and contractual obligations.

## 🧩 Problem Description

Iran Khodro aims to launch **up to three new production lines**, each capable of producing specific types of vehicles. The company wants to maximize profit while adhering to several constraints:

- Limited capital and space restrict the number of lines to max 3.
- Certain lines cannot be selected together (e.g., Line 4 and Line 5).
- At least 18,000 cars from **at least 4 different types** must be produced.
- Each selected vehicle type must have **at least 1,500 units**.
- A minimum of **3,300 units** of Peugeot 405 and Samand combined must be produced for a taxi company.
- At least **1,500 vans** must be produced, or a penalty of 3,500 is applied.
- At least **63% of non-commercial cars** must be hatchbacks (Peugeot 206, 207, or SD).
- A limited number of a specific component is available for some hatchbacks.

> ⚙️ The solution involves choosing production lines and allocating vehicle production quantities to meet the above conditions while staying within line time capacities and maximizing total profit.

## 📊 Data Overview

- **Vehicle types**: 7 (Peugeot 206, 207, 405, Samand, Rana, Van, Peugeot SD)
- **Production lines**: 5 (each with different capacities and setup costs)
- **Constraints**: Time limits, market demand, minimum productions, part limitations, penalties
- **Objective**: Maximize total net profit = vehicle revenue - setup costs - penalties

## 🔧 Tools & Libraries

- Python 🐍
## 📈 Output

The final output includes:
- Selected production lines
- Number of vehicles to produce per line
- Total profit
- Verification of all constraints

