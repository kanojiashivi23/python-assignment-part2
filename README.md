# python-assignment-part2
# Restaurant Order Management System 🍽️

This project is a simple Python-based system that simulates how a restaurant manages its menu, customer orders, inventory, and sales data.

The goal of this project was to practice working with Python data structures like dictionaries and lists while solving real-world style problems.

---

## 🔹 What I built

### 1. Menu Exploration
- Displayed the full restaurant menu grouped by categories (Starters, Mains, Desserts)
- Checked which items are available or unavailable
- Found:
  - Total number of items
  - Available items
  - Most expensive item
  - Items priced under ₹150

---

### 2. Cart Operations
- Created a cart system where users can:
  - Add items
  - Remove items
  - Update quantity
- Handled edge cases like:
  - Item not موجود in menu
  - Item unavailable
- Generated a final order summary with subtotal, GST, and total payable

---

### 3. Inventory Tracker
- Used deep copy to safely store original inventory
- Updated stock after order placement
- Prevented stock from going below zero
- Displayed reorder alerts when stock reached minimum level

---

### 4. Sales Log Analysis
- Calculated total revenue for each day
- Identified the best-selling day
- Found the most frequently ordered item
- Added new sales data and updated analysis
- Printed all orders using `enumerate` in a clean numbered format

---

## 🛠️ Concepts Used
- Lists and dictionaries (including nested structures)
- Loops (`for`, `while`)
- Conditional statements
- Functions
- `copy.deepcopy()`
- `enumerate()`

---

## 📂 Project File
- `part2_order_system.py`

---

## 🚀 How to Run
Run the Python file in any IDE or terminal. The outputs will be printed step-by-step.

---

## ✍️ Note
This project helped me understand how real-world systems like order management and inventory tracking work using basic Python concepts.
