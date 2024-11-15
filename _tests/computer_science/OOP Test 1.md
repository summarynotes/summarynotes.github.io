---
layout: test
title: OOP Test 1
subject: computer_science
level: AS
time: 50min
---
## Object-Oriented Programming (27 marks)

You are required to design a simple library management system using Object-Oriented Programming (OOP) principles. The system should be able to manage books and members. Each book has a title, author, and ISBN number. Each member has a name, membership ID, and a list of borrowed books.

### Class Descriptions:

#### Book Class

| Attribute/Method | Description |
|------------------|-------------|
| **title**          | **str**: The title of the book |
| **author**         | **str**: The author of the book |
| **isbn**           | **str**: The ISBN number of the book |
| **get_title()**    | Returns the title of the book |
| **set_title(title)** | Sets the title of the book |
| **get_author()**   | Returns the author of the book |
| **set_author(author)** | Sets the author of the book |
| **get_isbn()**     | Returns the ISBN number of the book |
| **set_isbn(isbn)** | Sets the ISBN number of the book |

#### Member Class

| Attribute/Method | Description |
|------------------|-------------|
| **name**           | **str**: The name of the member |
| **membership_id**  | **str**: The membership ID of the member |
| **borrowed_books** | **list**: A list of books borrowed by the member |
| **get_name()**     | Returns the name of the member |
| **set_name(name)** | Sets the name of the member |
| **get_membership_id()** | Returns the membership ID of the member |
| **set_membership_id(membership_id)** | Sets the membership ID of the member |
| **borrow_book(book)** | Adds a book to the member's list of borrowed books |
| **return_book(isbn)** | Removes a book from the member's list of borrowed books using pop() method after linear search|

### Tasks:

1. **Declare the *Book* Class (5 marks)**
   - Write program code to declare the **Book** class, its attributes, and constructor.
   - Do not write program code for the get methods.
   - Use your programming language's appropriate constructor.
   - All attributes must be private. If you are writing in Python, include attribute declarations using comments.
   - Save your program code.

2. **Define **Book** Class Methods (6 marks)**
   - Write program code for the class methods **get_title()**, **set_title(title)**, **get_author()**, **set_author(author)**, **get_isbn()**, and **set_isbn(isbn)**.
   - Save your program code.

3. **Declare the **Member** Class (5 marks)**
   - Write program code to declare the **Member** class, its attributes, and constructor.
   - Do not write program code for the get methods.
   - Use your programming language's appropriate constructor.
   - All attributes must be private. If you are writing in Python, include attribute declarations using comments.
   - Save your program code.

4. **Define **Member** Class Methods (6 marks)**
   - Write program code for the class methods **get_name()**, **set_name(name)**, **get_membership_id()**, **set_membership_id(membership_id)**, **borrow_book(book)**, and **return_book(isbn)**.
   - Save your program code.

5. **Main Program (5 marks)**
   - Write a main program to demonstrate the use of these classes and methods.
   - The program should create instances of **Book** and **Member**, and demonstrate borrowing and returning books.
   - Save your program code.

---
