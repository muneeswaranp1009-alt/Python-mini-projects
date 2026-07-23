# Student Search System

A simple Python command-line application that searches for a student's name from a predefined list. The program validates user input, performs case-insensitive searches, and provides appropriate messages based on the search result.

## Features

- Search for a student by name
- Case-insensitive search
- Removes unnecessary whitespace from user input
- Input validation
- Prevents empty input
- Rejects numbers and special characters
- Simple command-line interface

## Technologies Used

- Python 3

## Project Structure

```
student-search-system/
│
├── student_search.py
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/student-search-system.git
```

Navigate to the project folder:

```bash
cd student-search-system
```

Run the program:

```bash
python student_search.py
```

## Sample Input

```
Enter the student name:
Priya
```

### Sample Output

```
Student Priya was Found
```

### Student Not Found

```
Enter the student name:
David
```

Output:

```
Student David was Not Found
```

### Invalid Input

```
Enter the student name:
Rahul123
```

Output:

```
Invalid Input: Numbers or Symbols are not allowed!
```

### Empty Input

```
Enter the student name:
```

Output:

```
Error: Input cannot be empty!
```

## Learning Outcomes

- Lists
- String Manipulation
- User Input Validation
- Conditional Statements
- Case-Insensitive Search
- Error Handling
- Python Fundamentals

## Future Improvements

- Store student records in a file or database
- Search by student ID
- Add student records
- Update and delete student information
- Build a graphical interface using Tkinter
- Develop a web version using Flask or Streamlit

## Author

Developed as a Python practice project to strengthen programming fundamentals, input validation, and search algorithms.

## License

This project is intended for educational and learning purposes.
```
