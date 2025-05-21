☕ Coffee Shop Challenge

A Python OOP project modeling Customers, Coffees, and Orders.

📁 Structure

coffee-shop-challenge/
├── customer.py
├── coffee.py
├── order.py
├── debug.py
└── tests/
    ├── customer_test.py
    ├── coffee_test.py
    └── order_test.py

🧪 Run

pipenv install
pipenv shell
python3 -m unittest discover tests

✅ Features

Customer ↔️ Order ↔️ Coffee (many-to-many)

Validations on all attributes

Aggregate methods like average_price, num_orders