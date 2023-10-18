# Library-Management-System
1. Introduction

The Library Management System is a Java console application designed to manage a library's book inventory.
It allows users to add new books, display available books, and check out books. This system provides basic
functionalities for a library environment, enabling librarians or users to interact with the library's collection.

2. Classes and Functions

Book Class:

Attributes:
title: Represents the title of the book.
author: Represents the author of the book.
checkedOut: Indicates whether the book has been checked out by a user.
Methods:
Book(String title, String author): Constructor to initialize the book with a given title and author.
getTitle(): Returns the title of the book.
getAuthor(): Returns the author of the book.
isCheckedOut(): Returns true if the book is checked out, false otherwise.
setCheckedOut(boolean checkedOut): Sets the checkedOut status of the book.
Library Class:

Attributes:
books: A list to store Book objects representing the library's book collection.
Methods:
Library(): Constructor to initialize an empty list of books.
addBook(String title, String author): Adds a new book to the library's collection.
displayAvailableBooks(): Displays a list of available books that have not been checked out.
checkOutBook(String title): Checks out a book with the given title if it is available.
LibraryManagementSystem Class:

Methods:
main(String[] args): The entry point of the application. Displays a menu and handles user input to perform library operations. The available operations include adding books, displaying available books, checking out books, and exiting the system.
3. How to Use

Adding a Book:

Choose option 1 from the menu.
Enter the book's title and author when prompted.
The system will confirm the addition of the book.
Displaying Available Books:

Choose option 2 from the menu.
The system will list all available books (not checked out) in the library.
Checking Out a Book:

Choose option 3 from the menu.
Enter the title of the book you want to check out.
If the book is available, it will be checked out, and a confirmation message will be displayed. If not,
an appropriate message will indicate the unavailability.
Exiting the System:

Choose option 4 from the menu.
The system will display a goodbye message and terminate.
4. Notes

The system is case-insensitive regarding book titles.
The Library Management System operates in the console interface and expects user input via keyboard.
This Library Management System provides essential functionalities for managing a library's book inventory. 
It can be further enhanced with additional features such as book return, user management, and database integration for a complete library management solution.
