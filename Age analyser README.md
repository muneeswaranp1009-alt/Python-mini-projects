# Age Analyzer

A Python command-line application that analyzes a list of ages and generates a summary report. The program classifies individuals into adults and minors while calculating useful statistics such as the highest age, lowest age, and average age.

## Features

- Accepts multiple ages as comma-separated input
- Counts adults (18 years and above)
- Counts minors (below 18 years)
- Finds the highest age
- Finds the lowest age
- Calculates the average age
- Input validation
- Exception handling for invalid inputs

## Technologies Used

- Python 3

## Project Structure

```
age-analyzer/
│
├── age_analyzer.py
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/age-analyzer.git
```

Navigate to the project directory:

```bash
cd age-analyzer
```

Run the application:

```bash
python age_analyzer.py
```

## Usage

Enter multiple ages separated by commas.

Example:

```
23,54,12,45,18,9
```

## Sample Output

```
--- Age Analyzer Report ---

Total Ages Analyzed : 6
Adults              : 4
Minors              : 2
Highest Age         : 54
Lowest Age          : 9
Average Age         : 26.83
```

## Input Validation

The application validates:

- Non-numeric values
- Negative ages
- Ages greater than 150
- Incorrect input format

Example:

```
23,45,abc,67
```

Output:

```
Use only numeric values separated by commas.
```

## Learning Outcomes

- User Input Handling
- Lists and Loops
- Conditional Statements
- Data Analysis
- Exception Handling
- Python Functions
- Report Generation

## Future Improvements

- Categorize ages into children, teenagers, adults, and senior citizens
- Display age distribution charts
- Export reports to CSV or Excel
- Build a graphical interface using Tkinter
- Develop a web version using Streamlit or Flask

## Author

Developed as a Python project to practice data analysis, input validation, exception handling, and report generation.

## License

This project is intended for educational and learning purposes.
