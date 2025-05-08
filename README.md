# algorithm-and-programming
This mandatory course is taken in the first semester of the Computer Science Department at BINUS University. The programming language used here is C/C++.

# Assessment
This assessment was completed in January 2023.

A modified version of the assessment is created in May 2025.

## Instruction
- The assessment is done individually.
- There will be a total of 4 files that need to be submitted
  - A file that contains an explanation of the solution. Including a flowchart will grant a higher score.
  - 3 files with the extension '.c' which answer the questions.

## Case Study
### File description
A Comma-Separated Value (CSV) file is provided. The file consists of 3939 rows of housing data in Malaysia. There will be no missing values in each row.

The file will contain a header. Therefore, the program should be able to skip the header before passing the data into the record variable.
### Questions
1. Create a script that, when it is run, prompts the user to input the column name that the user wants to know about.
a. For column 'loc1', 'loc2', 'room', 'bathrooms', 'carparks', 'type', or 'furnish', display the following:
   - Frequency for each unique value
   - Maximum frequency
   - Minimum frequency
b. For column 'area' or 'price', display only the following:
   - Minimum price
   - Maximum price
   - Average value
2. Create a script that, when it is run, prompts the user to input a search query in the format "DataX in ColumnName". Do not use 3-string inputs for this one. The program should also handle a substring search.
- If the query does not exist in the record, inform the user.
- The search column that can be queried is all columns except the column 'area' and 'price'.
3. Please refer to the textbook by Paul J. Deitel (2016). C how to program: with an introduction to C++, Chapter 8, Exercise 8.21 (page 404).  Alphabetizing a List of Strings. In the original question, you are asked to alphabetize a list of strings using 10 to 15 names of towns. For this case, implement what is being asked using column Location 1.

### Note
1. All solutions should be built using the C programming language.
2. In the flowchart, if the solution contains more than 1 subprogram, each subprogram should also be drawn.
