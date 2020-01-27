# Environmental Informatics

## Assignment 03 - Using Files with Python

### Reading Assignment

- [Think Python 2e](https://greenteapress.com/wp/think-python-2e/), Chapters 8 & 14
- .

### Practical Practice

- If you are new to GitHUB, check out the [Hello World](https://guides.github.com/activities/hello-world/) tutorial from GitHUB to learn the basics.

#### Helpful Hints

- The turtle graphics package is a standard module for current versions of Python (specifically, Anaconda).  There should no longer be a need to follow the instructions for installing the Think Python swampy tools. 
- For most anaconda installations, the turtle graphics package should work correctly without any environment changes.  

### The Lab Assignment

#### Getting Started

- Use GitHUB Classroom to download this assignment, and use "git push" to submit your programs.
- I suggest that you work through Chapters 5, 6 and 7 prior to working on Chapter 4.  The Chapter 4 assignment can be completed without completing those chapters, but information on conditionals (Chapter 5), fruitful functions (Chapter 6), and iteration (Chapter 7) will increase your understanding of the process of program development in Chapter 4.

#### What to turn in...

1. **Think Python Chapter 4: Exercise 4.2.**

   - **Note** uses function developed in the Chapter to draw a set of three flowers on a single canvas.
   - Program should draw the three flowers shown in the problem statement.
   - The turtle package does not work with Jupyter Notebooks by default, instead you need to install the Notebook extension (nbextension) ipyturtle and start your program will a call to the module before you will see output from your program.  I have provided instructions to help at [How do I get turtle graphics to work in my Jupyter Notebook?](https://wiki.itap.purdue.edu/pages/viewpage.action?pageId=139460761).
   - Submit as program_4.2.py

2. **Think Python Chapter 5: Exercise 5.2.** 

   - Submit a program that solves Part 2 of the problem.
   - Check out the Python raw_input() function for a way to prompt the user for input.
   - Submit as program_5.2.py
   
3. **Think Python Chapter 6: Exercise 6.5.**

   - Submit a program that prompts the user for two values and then computes the greatest common divisor (GCD).
   - Submit as program_6.5.py
   
4. **Think Python Chapter 7: Exercise 7.1.**

   - Submit a program that produces a table similar to that shown in the problem statement.
   - It is not necessary to match the formatting of the table, but the numbers should be similar.
   - Submit as program_7.1.py

1. Complete the Introduction to Working with Files in Python tutorial at the Environmental Informatics Wiki site.
2. Write a Python code to do the following
   - Read the data file 2008Male00006.txt (available through the assignment link).  This file contains output from a Raccoon behavior model which describes the movement of a simulated raccoon named George over the course of a day.  The file is comma separated, expect for the last line which contains only one field that provides George's status at the end of the model simulation.
   - Write the contents to a new TAB delimited file in the same directory.  The new file should include:
   - The Date, Time, X and Y coordinates, the Asleep flag and the behavior mode (in that order). 
   - Also the final state of the Raccoon.
3. Submit the program needed to complete the assignment, the input file used and the output file created. 
  - Also include a file named README.txt that indicates the name of the processing script, a description of the processing being completed by the script, and the names of the input (required) and output (created) files.  This is a preliminary Metadata file, these will get more important as we progress with assignments.
  - To submit, you should archive (e.g., create a zip, 7z, tar, tgz, gz file) the entire directory with the README.txt, Python script, and the input and output files into a single submission file.  In this case, the directory should include your username so that when the archive file is uncompressed your submission directory does not get overwritten.  
