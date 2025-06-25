# Student Management System (Java Console App)

## Overview

This is a simple **Java console-based application** designed to manage student records. It provides basic operations such as **adding**, **viewing**, **updating**, and **deleting** students using a menu-driven interface. The project demonstrates core concepts of object-oriented programming such as classes, objects, encapsulation, and list manipulation.

## Features

- Add new student details (ID, Name, Course)
- View a list of all students
- Update existing student information by ID
- Delete a student record by ID
- User-friendly command-line interface with a simple menu

## Project Structure

- **Main.java**  
  Contains the main method and acts as the entry point of the application. It uses a `Scanner` for user input and drives the menu system to interact with the user.

- **Student.java**  
  A plain Java class (POJO) representing a student. It contains fields for `id`, `name`, and `course`, along with getter/setter methods and a `toString()` override for display formatting.

- **StudentService.java**  
  This class handles all student-related operations like adding, listing, updating, and deleting students. It maintains an internal list of `Student` objects.

## How to Run

1. Compile all three Java files:
   ```bash
   javac Main.java Student.java StudentService.java
