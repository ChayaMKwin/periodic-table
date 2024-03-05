# Periodic Table Database and Information Script

This repository contains a PostgreSQL database dump with information about chemical elements from the periodic table, along with a Bash script to retrieve and display data from this database.

## Database Dump

The PostgreSQL database dump (`periodic_table_dump.sql`) creates a database named `periodic_table` and fills it with tables and sample data related to chemical elements.

## Periodic Table Information Script

The Bash script (`script.sh`) lets users fetch details about chemical elements from the database. Users can input an element's symbol or name, and the script returns information such as atomic number, symbol, type, atomic mass, melting point, and boiling point.

## Usage

1. **Database Setup**: Execute the PostgreSQL database dump script (`periodic_table_dump.sql`) to create and populate the `periodic_table` database.

2. **Running the Script**: Execute the Bash script (`script.sh`) and provide an element symbol or name as an argument to retrieve information about the specified element.

## Dependencies

- **PostgreSQL**: Ensure PostgreSQL is installed on your system to interact with the database.
