# Library Management System

A Java console based application using SQLite to manage library books, members and borrowing records.

## Features

- **Book Management:** Add, view, update and delete book records.
- **Member Management:** Register members and manage their details and membership types.
- **Borrowing Management:** Create, view, update and delete borrowing records.
- **Availability Tracking:** Update book availability when books are borrowed or returned.
- **Search Functionality:** Search books, members and borrowing records.
- **Status Management:** Track borrowing records as Borrowed, Returned or Overdue.

## Technologies Used

- Java
- SQLite
- JDBC
- SQL

## Database Relationships

- **Books and Borrowing:** One book can be linked to multiple borrowing records over time.
- **Members and Borrowing:** One member can have multiple borrowing records.
- **Foreign Keys:** Connect borrowing records to the relevant books and members.

## How to Run

1. Install the Java Development Kit (JDK).
2. Add the SQLite JDBC driver to the project.
3. Run `Main.java` to start the application.
4. Use the console menu to manage records.

## Project Structure

- `Main.java` — Handles the main menu and user navigation.
- `LibrarySystem.java` — Contains the library management operations and SQL queries.
- `DatabaseConnection.java` — Manages database connections and initialises the database tables.
- `library.db` — SQLite database that stores the records.
