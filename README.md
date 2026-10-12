# Inventory-Management-using-Python
A Python desktop application developed as an Advanced Python Programming micro-project. It helps manage product inventory, record sales transactions, automatically update stock, and visualize sales performance.

Features
Product Management: Add products with name, category, price, and stock quantity.
Inventory Display: View product IDs, categories, prices, and available stock in a table.
Sales Recording: Record sales using a product ID and quantity.
Automatic Stock Updates: Reduce stock after successful sales.
Input Validation: Handle invalid numeric inputs, missing products, and insufficient stock.
Sales Analytics: Calculate total revenue and identify the best-selling product.
Data Visualization: Generate a category-wise sales bar chart.
Technologies Used
Python
Tkinter — graphical user interface
SQLite — persistent local database
Pandas — data analysis
Matplotlib — data visualization
Object-Oriented Programming (OOP)
Project Structure
inventory-management-system/
├── inventory_management.py
├── requirements.txt
├── README.md
├── .gitignore
├── screenshots/
└── docs/
Installation and Setup
Prerequisites
Python 3.10 or later recommended
pip
Tkinter support
1. Clone the repository
git clone (https://github.com/Kishwarsahil/Inventory-Management-using-Python)
cd inventory-management-system
Replace YOUR-USERNAME with your GitHub username.

2. Install dependencies
python -m pip install -r requirements.txt
3. Run the application
python inventory_management.py
The application creates inventory.db and its required tables automatically when started.

How It Works
Enter product details and add the product.
View the stored inventory in the product table.
Enter a product ID and quantity to record a sale.
The system checks stock availability, calculates the sale amount, records the transaction, and updates stock.
Click Show Analytics to view total revenue, the best-selling product, and category-wise sales.
Database Design
Products table: ID, name, category, price, stock.

Sales table: product, category, quantity, total.

Limitations
Designed for local, single-user use.
Does not include authentication or cloud synchronization.
Product editing, deletion, search, and advanced forecasting are not implemented.
Future Enhancements
Product search and filtering
Low-stock alerts
Monthly sales reports
CSV/PDF exports
Web-based multi-user access
Advanced sales forecasting
Academic Project
Course: Advanced Python Programming
Course Code: E1CSA348
Institution: Alliance University, Alliance School of Advanced Computing

Developed as a student micro-project.
