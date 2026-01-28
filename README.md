# Lab-26---Files---Doubles
# Reading and Parsing Numeric Data from a File

## Background
In class, we read data from a file by reading each line as a **String** and converting that string into an **integer**.  
In this lab, you will apply the same idea, but the file may contain **both integers and decimal values**.  

The goal of this lab is to practice:

- Reading data from a file
- Converting strings into numeric values
- Storing numeric data in an array
- Using loops to process data

---

## Input File

You will be given a text file (`numbersList.txt`) containing numeric values, **one per line**.

- Each line will contain either:
  - an integer (e.g., `7`, `-3`)
  - or a decimal value (e.g., `4.5`, `-2.75`)
- Some lines may contain **leading or trailing spaces**.
- Some lines may be **blank**.
- You may assume there are **no non-numeric strings**.
- The file contains **fewer than 100 values**.

---

## Program Requirements

Write a Java program that:

1. Opens the input file
2. Reads each line as a **String**
3. Ignores blank lines
4. Trims extra spaces
5. Converts each value to a **double**
6. Stores the values in a `double` array
7. Tracks the total number of values read

---

## Output Requirements

After reading the file, your program should calculate and display:

- The **total number of values**
- The **sum** of the values
- The **average** value
- The **maximum** value
- The **minimum** value

Your output should be clearly labeled and neatly formatted.
Example:  *THESE ARE NOT THE RESULTS YOU WILL GET!!*

        Number of values: 9
      
        Sum: 10.25
      
        Average: 1.14
      
        Minimum value: -6.75
      
        Maximum value: 7.0


*(Your output will depend on the contents of your input file.)*

---

## Restrictions

- You **may not** use:  
  - `scanner.nextInt()` or `scanner.nextDouble()`
- You **must**:
  - read each value as a `String`
  - convert the value to a Double
  - handle blank lines and extra spaces
- You **may**
  - Change the values in the file to be sure it works on other cases
---

## Optional Extension (for fast finishers)

After completing the required output, optionally:

- Print how many values are **greater than the average**.
