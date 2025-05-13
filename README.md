# inventory_management_system# Inventory Management System

A robust command-line Inventory Management System built with Python using Object-Oriented Programming (OOP) principles. This system allows management of various product types, stock operations, sales tracking, and data persistence in JSON format.

## Features

- Abstract base class for `Product`
- Subclasses for different product types:
  - **Electronics** (brand, warranty)
  - **Grocery** (expiry date with expiry check)
  - **Clothing** (size, material)
- Inventory operations:
  - Add, remove, search, and list products
  - Sell and restock functionality
  - Calculate total inventory value
  - Remove expired groceries
- Persistent storage using JSON
- CLI interface for interactive usage
- Custom error handling for:
  - Duplicate product IDs
  - Invalid product operations
  - JSON loading errors

## How to Run

1. Make sure you have Python installed (>= 3.7).
2. Run the program from terminal or command prompt:

```bash
python main.py
inventory_management_system/
├── main.py            # Entry point with CLI
├── inventory.py       # Classes and logic
├── inventory.json     # (optional) Saved data file
