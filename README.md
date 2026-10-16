# Python File Handling: Text Files, CSV and JSON

A beginner-friendly learning project covering Python file handling from fundamental operations to structured data processing with CSV and JSON files.

This repository is part of my Python learning roadmap and contains three batches of practical questions designed to develop programming skills through hands-on implementation. It serves as a learning resource for beginners who want to understand how Python reads, writes, updates, validates, and processes files.

## Project Overview

File handling is an essential Python skill for working with persistent data. Instead of keeping information only in variables, programs can store data in files, retrieve it later, update existing records, and generate reports.

This project covers three areas:

- **Batch 1 — File Handling Fundamentals:** Understanding text files, file modes, reading, writing, appending, and context managers.
- **Batch 2 — Advanced File Operations:** Working with directories, checking file existence, searching and replacing text, handling file errors, and combining files.
- **Batch 3 — CSV and JSON:** Reading and writing structured data, filtering records, validating values, and generating reports.

The project contains 30 structured coding questions, with 10 questions in each batch, progressing from foundational concepts to practical data-processing tasks.

## Objectives

- Understand how file handling works in Python.
- Learn to create, read, write, append, and update files.
- Understand the differences between common file modes.
- Use context managers to manage file resources safely.
- Process text files efficiently.
- Check file and directory existence using `pathlib`.
- Handle file-related exceptions and invalid input.
- Read and write structured data using CSV and JSON.
- Validate records and handle missing or malformed data.
- Develop reusable solutions for common file-processing problems.

## Topics and Questions Covered

### Batch 1: File Handling Fundamentals

**Questions 1–10**

This batch introduces the basic operations required to work with text files.

Topics and exercises include:

1. Opening, reading, and closing text files.
2. Writing data into files.
3. Understanding `r`, `w`, `a`, and `x` file modes.
4. Comparing `read()`, `readline()`, and `readlines()`.
5. Saving lists as individual lines in a file.
6. Overwriting existing file contents.
7. Appending new records without deleting previous data.
8. Using `with open()` as a context manager.
9. Counting lines, words, and characters.
10. Building a simple file-based expense tracker.

**Learning outcome:** Understand the fundamental file operations required to store and retrieve information using Python.

### Batch 2: Advanced File Operations

**Questions 11–20**

This batch focuses on reliable file processing, text manipulation, and error handling.

Topics and exercises include:

11. Checking whether a file exists using `pathlib`.
12. Creating directories and files.
13. Copying file contents into a backup file.
14. Processing large text files line by line.
15. Searching for keywords and displaying matching line numbers.
16. Replacing text and saving modified contents.
17. Handling `FileNotFoundError`, `PermissionError`, and other relevant file exceptions.
18. Creating log files and appending messages.
19. Combining multiple text files into one output file.
20. Building a text-file analyzer.

The text-file analyzer combines several operations to calculate line, word, and character counts, identify frequently occurring words, and search for specific keywords.

**Learning outcome:** Develop safer and more efficient file-processing programs while understanding common file-access errors and text-manipulation techniques.

### Batch 3: CSV and JSON File Handling

**Questions 21–30**

This batch introduces structured file formats commonly used in data analysis and application development.

Topics and exercises include:

21. Creating CSV files using the `csv` module.
22. Reading CSV records using `csv.reader()` and `csv.DictReader()`.
23. Filtering records and exporting selected rows.
24. Calculating department-wise average salaries.
25. Appending records using `csv.DictWriter()`.
26. Reading JSON data and calculating inventory value.
27. Writing dictionaries to formatted JSON files.
28. Understanding `json.load()`, `json.loads()`, `json.dump()`, and `json.dumps()`.
29. Handling malformed JSON, missing keys, and invalid data types.
30. Building a sales-report generator that exports revenue summaries to JSON.

**Learning outcome:** Understand how to work with tabular and hierarchical data formats and use them to create practical data-processing workflows.

## Techniques Mastered

The following techniques are covered through the three batches:

- **File access:** Opening, reading, writing, appending, and closing files.
- **File modes:** Choosing the appropriate mode for each operation.
- **Context managers:** Using `with open()` for safe resource management.
- **Text processing:** Splitting content, searching keywords, replacing text, and counting words and lines.
- **Path management:** Checking file existence and creating directories with `pathlib`.
- **Exception handling:** Managing missing files, permission errors, malformed input, and other expected failures.
- **Efficient reading:** Processing files line by line instead of loading all contents into memory.
- **CSV processing:** Reading, filtering, validating, and exporting tabular records.
- **JSON serialization:** Converting between Python objects and JSON data.
- **Data validation:** Identifying invalid records and handling missing or incorrectly typed values.
- **Report generation:** Summarizing processed information and saving results to output files.

## Tools and Technologies

- Python 3
- Jupyter Notebook
- Visual Studio Code
- Python standard library
  - `pathlib`
  - `csv`
  - `json`
  - `os`
  - `shutil`
  - `datetime`

## Repository Structure

A suggested structure for organizing the exercises is:

```text
python-file-handling/
|
|-- batch-1-fundamentals/
|   |-- q01_read_file.py
|   |-- q02_write_file.py
|   |-- ...
|   |-- q10_expense_tracker.py
|
|-- batch-2-advanced-operations/
|   |-- q11_check_file.py
|   |-- q12_create_directory.py
|   |-- ...
|   |-- q20_text_analyzer.py
|
|-- batch-3-csv-json/
|   |-- q21_create_csv.py
|   |-- q22_read_csv.py
|   |-- ...
|   |-- q30_sales_report.py
|
|-- README.md
```

This structure is a suggested organization. The filenames can be adjusted to match the actual files in the repository.

## Who Is This Project For?

This repository is intended for:

- Beginners learning Python file handling for the first time.
- Students practising Python through structured coding questions.
- Learners who want practical examples beyond basic syntax.
- Aspiring data analysts and data scientists who need to work with CSV and JSON files.
- Developers looking for simple references to common file-processing operations.

No advanced Python knowledge is required, although familiarity with variables, lists, dictionaries, functions, loops, and exception handling will be helpful.

## How to Use This Repository

1. Start with Batch 1 and understand each file operation.
2. Write your own solution to each question before reviewing examples.
3. Move to Batch 2 and practise reliable file access, text processing, and exception handling.
4. Complete Batch 3 to learn CSV and JSON processing.
5. Modify the examples with your own data to strengthen your understanding.

## Learning Approach

This project follows a hands-on learning approach. Each question focuses on a specific concept, while the later exercises combine multiple techniques into practical programs.

The objective is not just to learn file-handling syntax, but to understand how to use it to build reliable Python applications that can work with persistent data.

## Author

**Shorya Dev Bisht**

Data Analyst | Data Science and Machine Learning Enthusiast | Web Analytics Learner

- **LinkedIn:** https://www.linkedin.com/in/shorya-bisht-a20144349/
- **GitHub:** https://github.com/datascientistshorya
- **Medium:** https://medium.com/@its.shoryabisht


