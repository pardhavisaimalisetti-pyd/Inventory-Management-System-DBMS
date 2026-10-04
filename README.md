# Inventory Management System – DBMS

A Database Management System project for managing customers, products, inventory, orders, warehouses, employees, and regions.

## Project Contents

- **SQL** – complete database SQL and data-only SQL
- **Dataset** – verified inventory management dataset (8 CSV files, 400 records each)
- **ER Diagram** – the project ER diagram showing entities, attributes, keys, and relationships
- **Screenshots / Results** – 13 SQL query/result screenshots

## Database Tables

1. Customer
2. Product
3. Inventory
4. Orders
5. OrderDetails
6. Warehouse
7. Employee
8. Region

## Key Relationships

- Region → Warehouse
- Warehouse → Employee
- Warehouse → Inventory
- Product → Inventory
- Customer → Orders
- Orders → OrderDetails
- Product → OrderDetails

## Dataset

- 8 CSV files
- 400 records per CSV
- 3,200 total records
- Duplicate primary keys: 0
- Orphan foreign-key references: 0
- Product profit mismatches: 0
- Negative inventory/reorder values: 0

## SQL Results Included

The screenshots include:

1. Database Tables
2. Customer Table
3. Product Table
4. Inventory Table
5. Orders Table
6. OrderDetails Table
7. Inventory–Product–Warehouse JOIN
8. Low-Stock Query
9. Stock Aggregate Query
10. Order Status Query
11. Primary-Key Validation
12. Foreign-Key Validation
13. Product-Profit Validation

## Technologies

- MySQL
- SQL
- CSV
- OneCompiler-style SQL result screenshots

## Academic Project

Inventory Management System – DBMS
