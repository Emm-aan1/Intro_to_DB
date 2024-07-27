# 📚 Intro to DB

Welcome to the **Intro to DB** project repository! This repository contains scripts and files to help you set up and manage a database for an online bookstore using MySQL. Follow the steps below to get started with creating, populating, and managing your `alx_book_store` database.

![Database](https://i.pinimg.com/originals/af/47/44/af4744395b2f9487748518341ea4a4a1.png)

## 📂 Files and Directories

### 🐍 MySQLServer.py
- **Description:** This Python script creates the `alx_book_store` database in your MySQL server. 
- **Usage:** Run this script to initialize the database. If the database already exists, the script will not fail.
- **Note:** Ensure you handle database connections and errors properly while running this script.

### 📄 alx_book_store.sql
- **Description:** This SQL script contains the commands to create the `alx_book_store` database.
- **Usage:** Run this script to create the database structure for the online bookstore.
- **Note:** This script should be executed after `MySQLServer.py`.

### 📝 task_2.sql
- **Description:** This SQL script creates all necessary tables (`books`, `authors`, `customers`, `orders`, and `order_details`) in the `alx_book_store` database.
- **Usage:** Execute this script to set up the tables after creating the database.

### 🗃️ task_3.sql
- **Description:** This SQL script lists all the tables in the `alx_book_store` database.
- **Usage:** Run this script to verify that all tables have been created successfully.

### 📋 task_4.sql
- **Description:** This SQL script prints the full description of the `books` table.
- **Usage:** Execute this script to get detailed information about the `books` table.
- **Note:** This script does not use the `DESCRIBE` or `EXPLAIN` statements.

### 📚 task_5.sql
- **Description:** This SQL script populates the `books` table with initial data.
- **Usage:** Run this script to insert sample data into the `books` table.

### 📊 task_6.sql
- **Description:** This SQL script populates additional tables with more data for a richer dataset.
- **Usage:** Execute this script to insert more sample data into other tables like `authors`, `customers`, `orders`, and `order_details`.

## 🚀 How to Use

1. **Initialize the Database:**
   - Run the `MySQLServer.py` script to create the `alx_book_store` database.
   - Ensure your MySQL server is running and accessible.

   ```bash
   python MySQLServer.py
   ```

2. **Create the Database Structure:**
   - Execute the `alx_book_store.sql` script to set up the database.
   - Use a MySQL client or command line:

   ```bash
   mysql -u your_username -p < alx_book_store.sql
   ```

3. **Set Up Tables:**
   - Run the `task_2.sql` script to create all necessary tables.

   ```bash
   mysql -u your_username -p alx_book_store < task_2.sql
   ```

4. **Verify Tables:**
   - Execute the `task_3.sql` script to list all the tables.

   ```bash
   mysql -u your_username -p alx_book_store < task_3.sql
   ```

5. **Describe the `books` Table:**
   - Run the `task_4.sql` script to get a full description of the `books` table.

   ```bash
   mysql -u your_username -p alx_book_store < task_4.sql
   ```

6. **Populate Initial Data:**
   - Execute the `task_5.sql` script to insert initial data into the `books` table.

   ```bash
   mysql -u your_username -p alx_book_store < task_5.sql
   ```

7. **Populate More Data:**
   - Run the `task_6.sql` script to insert more data into other tables.

   ```bash
   mysql -u your_username -p alx_book_store < task_6.sql
   ```

## 📝 Notes

- Ensure you have the necessary permissions to create databases and tables in your MySQL server.
- Customize the scripts as needed to fit your specific requirements.
- Handle all database connections and error messages appropriately for a smooth experience.

Enjoy your journey into database management with **alx_book_store**!