# Customised Database Management System (DBMS) in Java

A simple, in-memory Database Management System implemented in Java, designed to handle basic employee data. The project simulates fundamental database operations such as insertion, deletion, selection, aggregation, and update operations on employee records, providing a menu-driven console interface.

## Features

- **Insert Record:** Add a new employee to the database.
- **Display Records:** View all employee records or search by ID or name.
- **Delete Record:** Remove an employee entry by name or ID.
- **Update Record:** Update the address of a specific employee by ID.
- **Aggregation Functions:** Perform aggregate operations such as:
  - Count of employees
  - Summation of all salaries
  - Average salary
  - Maximum and minimum salaries
- **Delete Table:** Deallocate all employee records.
- **Interactive CLI:** User-friendly, text-based menu system.

## Technologies Used

- Java (OOP principles)
- Collections (LinkedList)
- Standard I/O (Scanner)

## Usage

1. **Compile:**
   ```bash
   javac Customised_DBMS.java
   ```
2. **Run:**
   ```bash
   java Customised_DBMS
   ```

3. **Follow the on-screen menu** to perform actions like adding, viewing, updating, or deleting employee records.

## Example Operations

- Add a new employee:
  - Option `1`, then input name, age, salary, address.
- Display all employees:
  - Option `2`
- Find an employee by ID:
  - Option `3`, then provide ID.
- Aggregate functions:
  - Options `6` to `10` for various count, sum, average, max, min queries.

## Code Structure

- `Employee` class: Represents individual employee records.
- `MarvellousDBMS` class: Core DBMS logic—manages storage and operations.
- `Customised_DBMS` class: Main entry point and user interaction.
