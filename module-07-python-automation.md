# Module 7: Automate Cybersecurity Tasks with Python

## How to Use This Module

Use this module to understand Python from a cybersecurity automation point of view. The goal is not to become an advanced programmer immediately. The goal is to read simple scripts, write basic logic, process files, search text, and automate repetitive analyst tasks.

Practice by writing small scripts. Keep each script simple: input, process, output. Focus on clarity before complexity.

## Week 1: Python Basics, Data Types, Conditionals, and Loops

### What You Should Understand

Python is a programming language often used in cybersecurity because it is readable, flexible, and useful for automation. Analysts can use Python to parse logs, compare lists, check indicators, process files, and reduce repetitive work.

### Key Concepts

- A variable stores a value.
- Data types describe the kind of value being stored.
- Conditional statements let a program make decisions.
- Loops repeat actions.
- Comments explain important logic.
- Clear names make scripts easier to understand and troubleshoot.

### Important Terms

- Variable - A named storage location for a value.
- String - Text data.
- Integer - Whole number.
- Float - Decimal number.
- Boolean - True or false value.
- Conditional - Logic that runs when a condition is met.
- Loop - Repeats code.
- Syntax - Rules for writing valid code.

### Basic Example

```python
failed_logins = 7

if failed_logins >= 5:
    print("Review account for possible brute force activity")
else:
    print("Continue monitoring")
```

### What To Practice

- Create variables for username, IP address, login count, and alert status.
- Use `if`, `elif`, and `else` to classify alert severity.
- Use a `for` loop to print each item in a list of IP addresses.
- Use a `while` loop only when you clearly understand when it should stop.

### Quick Check

1. Why is Python useful for cybersecurity analysts?
2. What is a variable?
3. What is the difference between a string and an integer?
4. When would you use an `if` statement?
5. Why must loops have clear stopping conditions?

## Week 2: Functions, Libraries, Modules, and Code Style

### What You Should Understand

Functions make code reusable and easier to read. Libraries and modules provide existing code that can be imported instead of writing everything from scratch. Good code style matters because security scripts may be reused, reviewed, or handed to another analyst.

### Key Concepts

- A function groups steps into a reusable block.
- Parameters receive input into a function.
- Return values send output back from a function.
- Libraries provide prebuilt functionality.
- Modules organize Python code.
- Clear formatting and naming make scripts easier to maintain.

### Important Terms

- Function - Reusable block of code.
- Parameter - Variable listed in a function definition.
- Argument - Value passed into a function.
- Return - Sends a result back from a function.
- Library - Collection of reusable code.
- Module - Python file or package that can be imported.
- Style guide - Rules for writing readable code.

### Basic Example

```python
def classify_failed_logins(count):
    if count >= 10:
        return "high"
    if count >= 5:
        return "medium"
    return "low"

severity = classify_failed_logins(8)
print(severity)
```

### Useful Python Modules

- `os` - Work with operating system paths and environment details.
- `csv` - Read and write CSV files.
- `json` - Work with JSON data.
- `re` - Use regular expressions for pattern matching.
- `datetime` - Work with dates and times.

### What To Practice

- Write a function that accepts an IP address and prints a review message.
- Import `datetime` and print the current date.
- Read a short CSV file using the `csv` module.
- Rename unclear variables to readable names.

### Quick Check

1. Why are functions useful?
2. What is the difference between a parameter and an argument?
3. Why should analysts use existing libraries?
4. What module is used for regular expressions?
5. Why does code style matter?

## Week 3: Strings, Lists, Algorithms, and Regular Expressions

### What You Should Understand

Security data often appears as text: logs, usernames, file paths, domains, hashes, IP addresses, email addresses, and alert messages. Python can search, split, compare, and extract useful information from text.

### Key Concepts

- Strings can be searched, sliced, split, and converted.
- Lists store multiple values.
- Algorithms are step-by-step problem-solving procedures.
- Regular expressions search for patterns in text.
- Pattern matching is useful for logs, IP addresses, emails, domains, and indicators.

### Important Terms

- String method - Built-in action that can be used on text.
- List - Ordered collection of values.
- Index - Position of an item in a sequence.
- Algorithm - Step-by-step method to solve a problem.
- Regex - Regular expression used to match text patterns.
- Pattern matching - Finding text that follows a specific format.

### Basic Examples

```python
allowed_users = ["admin01", "analyst01", "analyst02"]
login_user = "guest"

if login_user not in allowed_users:
    print("Unauthorized user detected")
```

```python
import re

log_line = "Failed login from 192.168.1.25"
match = re.search(r"\d+\.\d+\.\d+\.\d+", log_line)

if match:
    print(match.group())
```

### What To Practice

- Use `.lower()` to normalize usernames before comparison.
- Split a log line into separate fields.
- Search a list of IP addresses for a specific value.
- Use regex to find an email address or IP address in text.

### Quick Check

1. Why is text processing useful in cybersecurity?
2. What does a list store?
3. What is an index?
4. What does regex help you find?
5. Why should input sometimes be normalized before comparison?

## Week 4: Files, Errors, Debugging, and Automation Workflows

### What You Should Understand

Automation often means reading data from a file, processing it, and writing useful output. Python scripts should also handle errors clearly so the analyst knows what went wrong.

### Key Concepts

- Files can be opened, read, written, and closed.
- `with open(...)` is a safe way to work with files.
- Exceptions handle errors without crashing unexpectedly.
- Debugging means finding and fixing problems in code.
- Automation should be tested with small data before being trusted with larger datasets.
- Scripts should avoid changing or deleting data unless the action is intentional and tested.

### Important Terms

- File handling - Reading from or writing to files.
- Exception - Error condition that can be handled.
- Debugging - Finding and fixing code issues.
- Automation - Using code to perform repeatable tasks.
- Input validation - Checking that input is safe and expected.
- Output - Result produced by a script.

### Basic Example

```python
suspicious_ips = []

with open("firewall-log.txt", "r") as log_file:
    for line in log_file:
        if "DENY" in line:
            suspicious_ips.append(line.strip())

print(suspicious_ips)
```

### What To Practice

- Read a text file line by line.
- Write filtered results to a new file.
- Add `try` and `except` around file-reading logic.
- Test a script with a small sample log before using larger data.
- Write comments only where the logic needs explanation.

### Quick Check

1. Why is `with open(...)` useful?
2. What is an exception?
3. Why should automation be tested first?
4. What is input validation?
5. What kinds of cybersecurity tasks can Python automate?

## Module Review Checklist

- I can explain why Python is useful for cybersecurity automation.
- I understand variables, data types, conditionals, and loops.
- I can write and use simple functions.
- I know the difference between parameters and arguments.
- I can work with strings, lists, and basic regex.
- I can read files and process lines of text.
- I understand basic debugging and error handling.
- I can design a small script for a repetitive analyst task.

## Quick Revision

Python helps analysts automate repetitive work, process logs, compare data, extract indicators, and create simple tools. Important foundations include variables, data types, conditions, loops, functions, libraries, strings, lists, regex, file handling, exceptions, and testing. Start small, write clearly, and verify output before relying on automation.