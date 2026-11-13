# AddressBook-C | Contact Management System

A console-based contact management application developed using C as part of the Emertxe Embedded Systems course.

## Overview

AddressBook-C is a menu-driven application designed to store and manage contact information. It allows users to create, search, edit, delete, and display contacts through a simple command-line interface.

The project demonstrates core C programming concepts, including structures, arrays, pointers, string manipulation, modular programming, and file handling.

## Features

- **Create Contacts:** Add new contacts with name, phone number, and email address.
- **Search Contacts:** Search for contacts using name, phone number, or email.
- **Edit Contacts:** Modify the details of existing contacts.
- **Delete Contacts:** Remove unwanted contact records.
- **List Contacts:** Display stored contacts with sorting functionality.
- **Input Validation:** Validate phone numbers and email addresses.
- **Duplicate Checking:** Prevent duplicate phone numbers and email addresses.
- **File Handling:** Save contact records to a file and load them when the application starts.

## Technologies and Concepts

- **Programming Language:** C
- **Compiler:** GCC
- **Core Concepts:**
  - Structures
  - Arrays and Pointers
  - Functions and Modular Programming
  - String Manipulation
  - File Handling
  - Searching and Sorting
  - Input Validation

## Project Structure

The project is organized into multiple source and header files:

| File | Purpose |
|---|---|
| `main.c` | Main program and menu handling |
| `contact.c` | Contact management operations |
| `contact.h` | Contact-related declarations and structures |
| `populate.c` | Contact population functionality |
| `populate.h` | Population-related declarations |
| `file.c` | File loading and saving operations |
| `file.h` | File handling declarations |
| `contacts.csv` | File used to store contact records |

## Learning Outcomes

Through this project, I gained practical experience in:

- Developing modular applications using C.
- Working with structures, arrays, pointers, and strings.
- Implementing CRUD operations.
- Performing input validation and duplicate checking.
- Managing persistent data using file handling.
- Applying searching and sorting techniques.
