# Scarlet Dress Shop Management System

This project is a full-stack web-based management system for a fashion store, developed using Python (Flask) and MySQL. It manages the core operations of a dress shop, including products, customers, employees, orders, suppliers, tailoring services, payments, and warehouse inventory.

The system is modular: each functional component is implemented in a separate file and integrates backend logic with a web interface built using HTML templates.

## Features

- Product management (add, update, delete, view)
- Customer management
- Employee management
- Order processing
- Supplier management
- Tailoring service tracking
- Payment handling
- Warehouse and inventory view

## Tech Stack

- Python (Flask)
- MySQL
- HTML / CSS
- Jinja2 Templates

## Project Structure

- `main.py` – application entry point
- `customers.py` – customer-related logic
- `employeeMan.py` – employee management
- `order.py` – order processing
- `payment.py` – payment handling
- `products.py` – product management
- `Suppliers.py` – supplier logic
- `tailoring.py` – tailoring services
- `WarehouseView.py` – warehouse view
- `setup_database.sql` – database schema and sample data
- `templates/` – HTML templates
- `static/` – static files and uploads

## Setup

1. Install Python 3.11 or higher.
2. Install dependencies:

```bash
pip install flask
```

3. Create the database using the provided SQL script:

```bash
mysql -u <username> -p < setup_database.sql
```

4. Update database connection settings in `main.py` if needed.

5. Run the application:

```bash
python main.py
```

## Notes

- The repository was initialized locally and pushed to GitHub.
- You should add a `.gitignore` file to exclude generated files such as `__pycache__/`.
- The UI is functional but can be improved with additional styling and validation.

## Future Enhancements

- Add authentication and authorization
- Improve frontend design
- Add more validation for forms and input data
- Add automated tests

