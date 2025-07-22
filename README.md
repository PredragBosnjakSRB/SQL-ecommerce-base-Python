# E-commerce Platform for Local Agricultural Products

This project simulates a complete e-commerce system with a relational SQL database and Python-based data analytics. It focuses on the sale of fresh local agricultural products — including fruits, vegetables, meat, honey, and homemade goods — offered by small rural producers.

It also introduces the concept of a weekly curated “Farm Box” with seasonal items, recipe suggestions based on available ingredients, and basic analytics for tracking performance.

---

## Key Features

- Sale of local fruits, vegetables, meat, honey, and homemade products
- Multiple registered small producers (farmers)
- Weekly “Farm Box” — curated seasonal items
- Shopping cart and ordering
- Contact form and customer messages
- Recipe suggestions linked to products
- Sales and customer analytics (via Python/SQL)

---

## Technologies Used

- SQL Server 2019
- Python 3.13
- pandas, SQLAlchemy, pyodbc
- Jupyter Notebook
- ER diagram via dbdiagram.io or Draw.io

---

## Project Structure

The project includes the following structure:

ecommerce-farm-platform/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
│
├── database/
│ └── (Schema and seed files are not publicly available)
│
├── python/
│ ├── db_connection.py
│ ├── analysis.py
│ └── utils.py
│
├── notebooks/
│ └── ecommerce_analysis.ipynb
│
└── images/
└── er_diagram.png

yaml
Copy
Edit

# Note: The full database schema (schema.sql) and seed data are intentionally not included in this public repository to prevent idea misuse. For legitimate review or collaboration, contact the author directly.

---

## Sample Analyses

- Top-selling products by month
- Active users per week
- Seasonal performance of products and Farm Boxes
- Most profitable producers
- Recipe usage patterns

---

##  Contact

For questions or access to full database structure, please reach out via GitHub or email.

---

##  License

MIT License — Free to use, learn from, and modify for educational purposes.

---

## Vision

This project aims to digitally connect small-scale rural producers with urban consumers, promoting healthy eating, seasonal awareness, and support for local agriculture.

## Learning Goals
This project was developed as part of a personal learning journey with the following objectives:

Improve relational database design (ER modeling, normalization)

Practice writing complex SQL queries for reporting and analytics

Connect Python with SQL Server using pyodbc and SQLAlchemy

Apply data analysis techniques with pandas and Jupyter Notebook

Understand how e-commerce systems manage orders, users, and inventory

Explore basic analytics (most sold products, seasonal trends)

Build clean and reusable code with modular Python scripts

Learn how to structure a full-stack backend project on GitHub

