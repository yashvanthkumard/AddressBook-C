# AddressBook-C | Contact Management System

A menu-driven contact management application developed using C as part of the Emertxe Embedded Systems course.

## Overview

AddressBook-C is a console-based application designed to manage contact information. It allows users to create, search, edit, delete, and display contact records.

The project demonstrates fundamental C programming concepts such as structures, arrays, pointers, string manipulation, modular programming, and file handling.

## Features

- **Create Contact:** Add a contact with a name, phone number, and email address.
- **Search Contact:** Search for contacts using name, phone number, or email address.
- **Edit Contact:** Modify the name, phone number, or email address of an existing contact.
- **Delete Contact:** Delete a selected contact after confirmation.
- **List Contacts:** Display all stored contact records.
- **Phone Number Validation:** Accepts exactly 10 numeric digits.
- **Email Validation:** Checks for a basic email format, including one `@` symbol and a dot after it.
- **Duplicate Checking:** Prevents duplicate phone numbers and email addresses.
- **File Handling:** Saves contact records to a file and loads them during application initialization.

## Technologies Used

- **Programming Language:** C
- **Compiler:** GCC
- **Development Concepts:**
  - Structures
  - Arrays and Pointers
  - Functions and Modular Programming
  - String Manipulation
  - File Handling
  - Input Validation
  - Searching

## Project Structure

| File | Description |
|---|---|
| `main.c` | Main function and menu-driven program execution |
| `contact.c` | Contact creation, searching, editing, deletion, listing, and validation |
| `contact.h` | Contact structures, constants, and function declarations |
| `file.c` | Loading and saving contact records |
| `file.h` | File handling function declarations |
| `populate.c` | Sample contact population functionality, if included |
| `populate.h` | Sample population declarations, if included |
| `contacts.csv` | File used for storing contact records |

## Application Menu

The application provides the following menu options:

1. Create Contact
2. Search Contact
3. Edit Contact
4. Delete Contact
5. List All Contacts
6. Save Contacts
7. Exit

## C Programming Concepts Applied

- Structures for organizing contact information.
- Arrays for storing multiple contact records.
- Pointers for passing the address book to functions.
- String functions for manipulating and comparing contact details.
- Modular programming for separating contact operations.
- File handling using `fopen()`, `fscanf()`, `fprintf()`, and `fclose()`.
- Loops and conditional statements for implementing menu operations and validation.

## Current Implementation Notes

- Contact records are stored in a fixed-size array.
- Email validation uses basic format checks and is not a complete email-standard validation.
- Search supports case-insensitive partial matching.
- Contact listing displays records in their stored order; sorting is not currently implemented.
- The file storage uses a simple comma-separated format and does not handle commas within contact fields.

## Learning Outcomes

Through this project, I gained practical experience in:

- Developing menu-driven applications using C.
- Implementing CRUD operations.
- Working with structures, arrays, and pointers.
- Performing input validation and duplicate checking.
- Managing persistent records using file handling.
- Organizing code into multiple source and header files.

## Project Information

**Project:** AddressBook-C  
**Domain:** C Programming  
