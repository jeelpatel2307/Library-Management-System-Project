# Library Management System

The Library Management System is a simple Java console-based application that allows users to manage a library by performing operations such as adding books, displaying the list of books, and removing books.

## Project Structure

### 1. `Book.java`

- Represents the `Book` class with attributes such as book ID, title, and author.
- Provides a constructor and getter methods.

### 2. `Library.java`

- Represents the `Library` class managing a list of books using `ArrayList`.
- Provides methods to add books, display all books, find a book by ID, and remove a book.

### 3. `LibraryManagementSystem.java`

- Main class implementing the user interface for the Library Management System.
- Uses a `Library` instance to perform operations based on user input.
- Provides a simple console-based menu for adding, displaying, and removing books.

## How to Run

1. Save each class in separate `.java` files (e.g., `Book.java`, `Library.java`, `LibraryManagementSystem.java`).
2. Compile the classes using the `javac` command:
    
    ```bash
    javac Book.java Library.java LibraryManagementSystem.java
    
    ```
    
3. Run the program:
    
    ```bash
    java LibraryManagementSystem
    
    ```
    

## Usage

1. Choose options from the menu to add books, display the list of books, remove books, or exit the system.
2. Follow the prompts to input book details or select options.
3. The system provides feedback on successful operations or errors.

## Customization

Feel free to customize and expand upon this project based on your requirements. Potential enhancements include implementing file handling for data persistence, adding user authentication, and incorporating a graphical user interface (GUI).

---
