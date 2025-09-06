# Sales-Analytics
CSV to MySQL Data Pipeline
📌 Project Overview

This project automates the process of loading multiple CSV files into a MySQL database using Python and Pandas. It dynamically creates database tables based on the structure of each CSV file and inserts the data efficiently.

The pipeline supports handling missing values, automatic data type mapping, and works for multiple datasets like customers, orders, sales, products, delivery, and payments.

⚡ Features

Reads multiple CSV files and maps them to MySQL tables.

Dynamically generates CREATE TABLE statements based on Pandas column data types.

Handles missing values (NaN) by converting them to NULL in MySQL.

Automatically cleans column names (replaces spaces, hyphens, and dots with underscores).

Inserts data into the database row by row.

Commits changes per CSV file to ensure data consistency.

🛠️ Technologies Used

Python (pandas, mysql-connector, os)

MySQL Database

CSV Files (as input datasets)
