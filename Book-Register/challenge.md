# Challenge: Book Registry in Go

## Objective

Create a command-line application in Go that allows users to register books, authors, and publishers. This challenge is designed to help you improve your skills in Go programming, user input handling, and data organization.

## Requirements

1. The program should display a menu with the following options:
   - 1: Register a book
   - 2: Register a publisher
   - 3: Register an author
   - 4: List authors
   - 5: List publishers
   - 6: List books
   - 7: Stop the program

2. Based on the user's selection, implement the following functionalities:
   - **Register a Book**: Prompt the user for book details (e.g., title, author, publisher) and store them.
   - **Register a Publisher**: Prompt the user for publisher details (e.g., name, year) and store them.
   - **Register an Author**: Prompt the user for author details (e.g., name, email) and store them.
   - **List Authors**: Display a list of all registered authors.
   - **List Publishers**: Display a list of all registered publishers.
   - **List Books**: Display a list of all registered books.
   - **Stop Program**: Exit the application.

3. Implement data validation and error handling:
   - Ensure that user inputs are valid (e.g., non-empty strings for names, valid years).
   - Display appropriate error messages for invalid inputs.

4. Organize your code:
   - Create a separate package (e.g., `utils`) to contain functions for registering and listing authors, publishers, and books.
   - Each function should be well-structured and modular.

## Bonus Challenge

- Add functionality to allow users to search for a book by title or author.
- Implement unit tests for the registration and listing functions in your `utils` package.

