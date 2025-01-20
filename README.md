# Library Management System

A simple and user-friendly Library Management System built in Java. The system manages students, books, and their interactions using HashMaps, showcasing fundamental object-oriented programming principles.

## Features

- **Student Management**
  - Register new students.
  - Check if a student is already registered.

- **Book Management**
  - Add new books to the library.
  - Display available books in the library.

- **Issue and Return Books**
  - Issue books to registered students.
  - Return books and update availability.

- **Purpose-Based Workflow**
  - Choose between book issuance and return based on the user’s input.

## Code Structure

- **`Student` Class**: Handles student registration and maintains a record of registered students.
- **`Book` Class**: Manages the library's book collection.
- **`Issue` Class**: Handles book issuance and return processes, linking books to students.
- **`Main` Class**: Entry point for the application, providing a user interface via the console.

## Getting Started

### Prerequisites

- JDK 8 or higher
- Java IDE (e.g., IntelliJ IDEA, Eclipse) or a text editor with Java support
  
Usage
Run the program and enter your ID to check if you are a registered student.
If not registered, you can opt to register and proceed.
Choose between issuing or returning a book by following the prompts.
The system updates the available books and issued books accordingly.
