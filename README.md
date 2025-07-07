"# Group-6-Big-data-assignment" 

# Python Programming Projects

This repository contains two Python programs demonstrating fundamental programming concepts including user input handling, data processing, and string manipulation.

## 📋 Table of Contents
- [Projects Overview](#projects-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)

## 🚀 Projects Overview

### 1. Student Management System
A console-based application for managing student information including name, age, and grades for multiple courses.

### 2. Palindrome Checker
An interactive program that checks whether a given string is a palindrome, with support for continuous checking until the user chooses to exit.

## 💻 Installation

### Prerequisites
- Python 3.6 or higher
- No additional libraries required (uses built-in Python modules)

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/mugisha19/Group-6-Big-data-assignment.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Group-6-Big-data-assignment
   ```

3. Run the programs:
   ```bash
   python student_management.py
   python palindrome_checker.py
   ```

## 🎯 Usage

### Student Management System

The program will prompt you to enter:
- Student's name
- Student's age
- Number of courses (2 or 3)
- Grades for each course

**Example Run:**
```
Enter student's name: John Doe
Enter student's age: 20
Enter number of courses (2 or 3): 3
Enter grade for course 1: 85.5
Enter grade for course 2: 92.0
Enter grade for course 3: 78.5

--- Student Information ---
Name: John Doe
Age: 20
Grades: 85.5, 92.0, 78.5
Average Grade: 85.33
```

### Palindrome Checker

The program runs in a loop, allowing you to check multiple strings:
- Enter any string to check if it's a palindrome
- Type 'exit' to stop the program
- The checker ignores spaces and case sensitivity

**Example Run:**
```
Enter a string to check if it's a palindrome (or type 'exit' to stop): racecar
Yes, it is a palindrome

Enter a string to check if it's a palindrome (or type 'exit' to stop): A man a plan a canal Panama
Yes, it is a palindrome

Enter a string to check if it's a palindrome (or type 'exit' to stop): hello
No, it is not a palindrome

Enter a string to check if it's a palindrome (or type 'exit' to stop): exit
Goodbye!
```

## ✨ Features

### Student Management System
- ✅ Input validation for number of courses (2 or 3 only)
- ✅ Automatic grade average calculation
- ✅ Clean, formatted output display
- ✅ Error handling for invalid inputs

### Palindrome Checker
- ✅ Case-insensitive palindrome detection
- ✅ Ignores spaces in palindrome checking
- ✅ Continuous loop for multiple checks
- ✅ Graceful exit option
- ✅ User-friendly interface

## 🏗️ Code Structure

### Student Management System Functions

| Function | Description |
|----------|-------------|
| `input_student_info()` | Collects student name, age, and grades |
| `calculate_average(grades)` | Calculates average of given grades |
| `display_student_info()` | Displays formatted student information |
| `student_management_system()` | Main function that orchestrates the program |

### Palindrome Checker Functions

| Function | Description |
|----------|-------------|
| `check_palindrome()` | Main loop for palindrome checking with user interaction |

## 🔧 Technical Details

### Input Validation
- **Student Management**: Validates course count (2-3 only)
- **Palindrome Checker**: Handles exit condition and string processing

### String Processing
- **Palindrome Logic**: Removes spaces and converts to lowercase before comparison
- **Reverse String**: Uses Python slice notation `[::-1]` for efficient reversal

### Error Handling
- Type conversion protection for age and grade inputs
- Loop-based validation for course number input
- Clean exit mechanism for palindrome checker

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👥 Authors

- **Group 6** - *Big Data Assignment*
- Repository: [Group-6-Big-data-assignment](https://github.com/mugisha19/Group-6-Big-data-assignment)

## 🆘 Support

If you encounter any issues or have questions, please:
1. Check the existing issues in the repository
2. Create a new issue with detailed description
3. Include steps to reproduce any bugs

---

*Happy Coding! 🐍*
