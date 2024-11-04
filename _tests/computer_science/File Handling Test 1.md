---
layout: test
title: File Handling Test 1
subject: computer_science
level: AS
time: 40min
---

## File Handling (20 marks)

You are required to write a Python program that reads from a text file containing student names and their scores in various subjects, processes the data, and writes the results to another text file. The input file **students.csv** should have the following format:

### Tasks:

1. **Create the CSV File (3 marks)**
   - Write program code to create a text file **students.csv** with the given header and data.
   - Save your program code.

```
Name, English, Computer, Maths, Physics
John Doe, 85, 90, 78, 92
Jane Smith, 88, 85, 91, 89
Alice Johnson, 79, 92, 84, 87
Bob Brown, 90, 88, 85, 91
Charlie Davis, 82, 87, 89, 85
```
2. **Read Data from File (5 marks)**
   - Write a Python function **read_file()** to read the data from **students.csv** and store it in a 2D array.
   - Use appropriate exception handling to manage file reading errors.
   - Save your program code.

3. **Calculate and Display Averages and Percentages (6 marks)**
   - Using the array from part 2, write a Python function **calculate_averages()** to calculate and display the average score and percentage for each student.
   - The percentage should be calculated as the average of the scores in all subjects.
   - Save your program code.

4. **Write Results to New File (6 marks)**
   - Write a Python function **write_results()** to create a new file **results.csv** and add the calculated averages and percentages for each student.
   - The new file should have the following format:

     ```
     Name, English, Computer, Maths, Physics, Average, Percentage
     John Doe, 85, 90, 78, 92, 86.25, 86.25%
     Jane Smith, 88, 85, 91, 89, 88.25, 88.25%
     Alice Johnson, 79, 92, 84, 87, 85.5, 85.5%
     Bob Brown, 90, 88, 85, 91, 88.5, 88.5%
     Charlie Davis, 82, 87, 89, 85, 85.75, 85.75%
     ```

   - Save your program code.

5. **Main Program (5 marks)**
   - Write a main program to demonstrate the use of these functions.
   - The program should create the **students.csv** file, read the data, calculate the averages and percentages, and write the results to **results.csv**.
   - Save your program code.

---