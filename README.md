**Library Management System**

A Java console-based application using SQLite to manage library books, members and borrowing records.

**Features:**
- Book management to add, view, update and delete book records.
- Member management to register members and manage their details.
- Membership types including Gold, Silver and Bronze.
- Borrowing record management to create, view, update and delete records.
- Book availability tracking when books are borrowed or returned.
- Borrowing status management to track records as Borrowed, Returned or Overdue.
- Search functionality to find books by title, author or ID.
- Member search by name or ID.
- Borrowing record search by member ID or book ID.

**Database Relationships:**
- **Books and Borrowing:** One book can be linked to multiple borrowing records over time.
- **Members and Borrowing:** One member can have multiple borrowing records.
- **Primary and Foreign Keys:** Primary keys uniquely identify records, while foreign keys link borrowing records to the relevant books and members.
- **Database Tables:** The database contains Books, Members and Borrowing tables to organise library information.

**Technologies Used:**
- Java
- SQLite for database storage and management.
- JDBC for connecting Java to the database.
- SQL for queries and database operations.
