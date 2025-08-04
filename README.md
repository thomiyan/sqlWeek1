# SQL Database Management Scripts

This repository contains basic SQL commands for creating and deleting databases. These scripts are useful for initializing and cleaning up database environments during development.

## 📄 Contents

### 1. `CREATE DATABASE saleDB;`
- **Purpose**: Initializes a new database named `saleDB`.
- **Use Case**: Ideal for setting up a fresh environment for sales-related data.
- **Note**: Ensure the database doesn't already exist to avoid errors.

### 2. `DROP DATABASE demo;`
- **Purpose**: Permanently deletes the database named `demo`.
- **Use Case**: Useful for removing outdated or unused databases.
- **Warning**: This operation is irreversible and will delete all data within `demo`.

## 🚀 Getting Started

To run these commands, use any SQL-compatible database management system (e.g., MySQL, PostgreSQL, SQL Server). Make sure you have the necessary permissions to create and drop databases.

## 🛡️ Best Practices

- Always back up your data before dropping a database.
- Use conditional clauses like `IF EXISTS` to prevent errors:
  ```sql
  DROP DATABASE IF EXISTS demo;
