Library Management System
Overview
This Library Management System is a console-based C++ application that allows librarians to manage books, borrowers, and transactions in a library. It includes features for adding, searching, and managing books, checking out and returning books, calculating fines for overdue returns, and managing tasks using a simple to-do list.

Features
1. Book Database Management
Add Book: Librarians can add new books to the library's collection, including the title, author, and ISBN.
Search Book: Users can search for books by title, author, or ISBN to find out their availability.
Book Availability: The system keeps track of whether a book is available or checked out.
2. Borrower Management
Checkout Book: Librarians can check out books to borrowers, recording the borrower's name and the date of the transaction.
Return Book: Borrowers can return books, and the system updates the book's availability.
3. Transaction Management
Fine Calculation: If a book is returned after the standard borrowing period of 14 days, the system automatically calculates a fine of $1 per day overdue.
Fine Notification: When returning a book, if a fine is due, the system notifies the librarian of the amount.
4. To-Do List Manager
Add Task: Users can add tasks to a to-do list, which might include library management activities.
View Tasks: Users can view the current list of tasks, with the total number of tasks displayed.
Mark Task as Completed: Users can mark tasks as completed, updating their status.
Remove Task: Users can remove tasks from the list once they are completed or no longer needed.
Usage
1. Running the Application
Compile the C++ source code using a C++ compiler (e.g., g++).
Run the compiled executable in a console or terminal.
2. Menu Options
Library Management System:

1. Add Book: Add a new book to the library's collection.
2. Search Book: Search for a book by title, author, or ISBN.
3. Checkout Book: Checkout a book to a borrower.
4. Return Book: Return a checked-out book and calculate fines if applicable.
5. Exit: Exit the application.
To-Do List Manager:

1. Add Task: Add a new task to the to-do list.
2. View Tasks: View the list of tasks, with status (completed or pending).
3. Mark Task as Completed: Mark a specific task as completed.
4. Remove Task: Remove a specific task from the list.
5. Exit: Exit the to-do list manager.
3. Sample Usage
Start by adding a few books to the library's collection.
Search for books by title, author, or ISBN to verify their availability.
Checkout books to borrowers and later return them to see the fine calculation in action.
Use the to-do list manager to keep track of tasks related to library operations.
Fine Calculation
Overdue Period: The standard borrowing period is 14 days. If a book is returned after this period, the system calculates a fine.
Fine Rate: The fine is $1 per day overdue. The system automatically calculates and displays the fine when the book is returned.
Example Scenario
Adding a Book:

Title: "The Great Gatsby"
Author: F. Scott Fitzgerald
ISBN: 9780743273565
Checking Out a Book:

ISBN: 9780743273565
Borrower Name: John Doe
Returning a Book:

ISBN: 9780743273565
The book is returned 20 days later.
Fine Due: $6 (20 days - 14 days = 6 days overdue)
Managing Tasks:

Add tasks like "Organize new arrivals" or "Update catalog".
Mark tasks as completed once done.
Remove tasks from the list as needed.
Requirements
C++ compiler (e.g., g++)
Basic understanding of C++ and console-based applications.
Future Enhancements
User Authentication: Implement user roles and authentication for librarians and borrowers.
Book Reservations: Allow users to reserve books that are currently checked out.
Detailed Reporting: Generate reports on book transactions, fines, and borrower activities.
Graphical User Interface (GUI): Develop a GUI version of the system for easier interaction.
Contribution
Feel free to contribute to this project by adding new features, fixing bugs, or improving the code structure.

License
This project is licensed under the MIT License - see the LICENSE file for details.
