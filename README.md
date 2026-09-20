# beauty-salon-db
A multi-branch beauty salon database (SQL Server) with schema, backup, and full project documentation

# Beauty Salon Database — DBD262 Group V7 Project

A relational database design and implementation project for a multi-branch beauty salon business, built as part of the DBD262 coursework.

## Overview

The database models the full operations of a beauty salon chain, including branches, staff, scheduling, client management, services, appointments, payments, inventory, suppliers, and promotions.

**22 tables**, including:

- Branches, Employees, EmployeeRoles, EmployeeSchedules
- Clients, ClientReviews
- ServiceCategories, Services, ServicePackages, PackageServices, EmployeeServices
- Appointments, AppointmentServices
- PaymentMethods, Payments
- ProductCategories, Suppliers, Products
- PurchaseOrders, PurchaseOrderItems, Inventory
- Promotions

## Repository Structure

```
.
├── docs/
│   └── DBD262_Group_V7_M1.pdf     # Project report / documentation
├── sql/
│   └── BeautySalonDB_Schema.sql   # Full DDL: database, tables, constraints
└── backups/
    └── BeautySalonDB.bak          # SQL Server database backup file
```

## Getting Started

### Option 1 — Run the SQL script
1. Open `sql/BeautySalonDB_Schema.sql` in SQL Server Management Studio (SSMS) or Azure Data Studio.
2. Execute the script against a SQL Server instance. It will create the `BeautySalonDB` database and all tables.

### Option 2 — Restore from backup
1. In SSMS, right-click **Databases** → **Restore Database**.
2. Choose **Device**, select `backups/BeautySalonDB.bak`.
3. Restore to a new or existing SQL Server instance.

## Tech Stack

- Microsoft SQL Server (T-SQL)

## Project Report

See [`docs/DBD262_Group_V7_M1.pdf`](docs/DBD262_Group_V7_M1.pdf) for the full design documentation, ER diagram, and business requirements.

## Authors

DBD262 Group V7
