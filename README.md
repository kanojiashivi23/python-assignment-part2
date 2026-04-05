# python-assignment-part2
# Restaurant Order Management System 🍽️

This project is a Python-based system that simulates how a restaurant manages its menu, customer orders, inventory, and daily sales.

The main aim of this project was to practice Python data structures like lists and dictionaries while applying them to a real-world scenario.

---

## 🔹 What this project includes

### 1. Menu Exploration
- Displayed the restaurant menu grouped by categories (Starters, Mains, Desserts)
- Checked which items are available or unavailable
- Found:
  - Total number of items
  - Number of available items
  - Most expensive item
  - Items priced under ₹150

---

### 2. Cart Operations
- Created a cart system to:
  - Add items
  - Remove items
  - Update item quantity
- Handled cases where:
  - Item is not found in the menu
  - Item is unavailable
- Generated a final order summary including subtotal, GST (5%), and total amount

---

### 3. Inventory Tracker
- Used deep copy to create a backup of inventory
- Updated stock after order placement
- Ensured stock never goes below zero
- Displayed reorder alerts when stock reached minimum levels

---

### 4. Sales Log Analysis
- Calculated total revenue for each day
- Identified the best-selling day
- Found the most frequently ordered item
- Added new sales data and updated the results
- Printed all orders using `enumerate()` in a numbered format

---

##  Concepts Used
- Lists and dictionaries (including nested data)
- Loops (`for`, `while`)
- Conditional statements (`if-else`)
- Functions
- `copy.deepcopy()`
- `enumerate()`

---

##  Project File
- `part2_order_system.py`

---

##  How to Run
Run the Python file in any IDE or terminal. The outputs will be displayed step by step.

---

##  Final Note
This project helped me understand how basic programming concepts can be used to build simple real-world systems like order management and inventory tracking.
