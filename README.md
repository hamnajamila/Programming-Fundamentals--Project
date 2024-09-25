# Library Management System

## Project Overview
This project is a **Library Management System** developed as part of the **Programming Fundamentals** course. It is built using **Python** and provides separate portals for **students** and **administrators** to manage library resources efficiently.

### Key Features:
- **Student Portal:**
  - Search for available books by title, author, or genre.
  - View issued books and their due dates.
  - Request new book issues.
  - Return books.
  
- **Admin Portal:**
  - Add new books to the library.
  - Remove outdated or damaged books.
  - View and update student records.
  - Manage book issuing and return processes.

## Project Structure
The project contains two main sections: 
1. **Student Portal**: Allows students to interact with the system by browsing books, managing their issued books, and requesting new ones.
2. **Admin Portal**: Enables administrators to manage book inventories, student records, and the overall book-issuing process.

### Student Portal
1. Upon launching the program, select the **Student** option.
2. **Search for books** using the provided filters.
3. To issue a book, enter the book ID and confirm the request.
4. To return a book, enter the issued book ID.

### Admin Portal
1. Select the **Admin** option upon launching the program.
2. Use the menu options to **add** or **remove** books, view **student records**, or manage book issues and returns.

## Dependencies
No external libraries are required, only standard Python libraries are used.

## Future Enhancements
- Integration of a database for persistent data storage.
- Adding an authentication system for better security.
- Implementing book reservation features for students.

## License
This project is open-source and available under the MIT License.
