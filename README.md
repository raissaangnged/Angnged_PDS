# Python for Data Science Assignments - Esade University
This repository contains the code for my Python for Data Science assignments. The exercises cover various topics designed to enhance learning and practical application.

## Instructions for Executing the Code
1. Download and install Python version 3.10 or above
2. Clone this repository locally: git clone https://github.com/raissaangnged/Angnged_PDS.git
3. Open the notebook using Jupyter notebook
4. Install the following libraries
   * numpy: pip install numpy
   * matplotlib: pip install matplotlib
   * seaborn: pip install seaborn

For reference, these are the other libraries used. No installation is needed since these are already part of Python's built-in library.
* calendar
* os
* re
* json
* pickle

## Python for Data Science: Assignment 1

Assignment 1 includes 18 exercises on basic Python basic, focusing on the following topics:

* Exercises 1-3: Syntax and Variables
* Exercises 4-5: Lists and Dictionaries
* Exercises 6-7: Tuples and Sets
* Exercises 8-11: Control Flow
* Exercises 12-14: Function
* Exercises 15-17: Combination of the functions

Note: To run this code, you need to have at least Python 3.10+ to use the match statement in exercise 11. 

## Python for Data Science: Assignment 2

Assignment 2 includes 4 exercises, focusing on the following topics:**

* Exercise 1: Creating a function
* Exercise 2: Basic data filtering
* Exercise 3: Creating a to-do list
* Exercise 4: Temperature converter <br/>

## Python for Data Science: Assignment 3

Assignment 3 revolves around Object Oriented Programming. There are 4 exercises centered on creating a course registration system, specifically as follows:

**Exercise 1: Creating a course class**
* In this class, each course has the following attributes: a) a name, b) a description and c) a list of enrolled students.
* The following methods are implemented:
   * Add a student to the course.
   * Remove a student from the course.
   * Display all students in the course. 
 
**Exercise 2: Creating a student class**
* In this class, each student has the following attributes: a) a name, b) ID number, c) address and d) a list of enrolled courses.
* The following methods are included:
  * Enroll in a course.
  * Drop a course.
  * Display all registered student courses.
 
**Exercise 3: Creating a central registration class**
* This class has a list of students and a list of courses
* The following methods are implemented:
  * Enroll in a course.
  * Drop a course.
  * Display all the enrolled courses.
  * Display all the students.
    
**Exercise 4: Adding students' course grades and GPA**
* This exercise adds each student's grades per course.
* This exercise also calculates the GPA of each student, which can be called using either the student's name or ID number. 

## Python for Data Science: Assignment 4

Assignment 4 revolves around exploring Basic Libraries, such as numpy, os, re, and shutil. There are 7 exercises that analyze the filenames in an annotations subfolder, specifically as follows: 

1. Exercise 1: Counting the number of annotation files
   * Kindly note to change the 'folder' variable to your respective folder path
3. Exercise 2: Counting the files that follow the specified naming convention 
4. Exercise 3: Counting the annotation by month and year, and identifying the month with the most annotations
5. Exercise 4: Creating a new annotations folder with multiple folders corresponding to a month
6. Exercise 5: Printing the annotations from the most recent to oldest one
7. Exercise 6: Getting data on the satellite numbers, specifically:
   * Counting the number of different satellites
   * Counting the number of annotations per satellite number
   * Identifying the satellite number in the most recent annotation
8. Exercise 7: Counting the number of unique regions

**Important tasks:** 
  * You need to download the "session_4" folder that can be found inside the "Assignment 4" folder, as this includes the annotation files used.
  * In Exercise 1, make sure to change the "folder" variable to your respective folder path

## Python for Data Science: Assignment 5

Assignment 5 is about exploring more functionalities of Basic Libraries, such as os, re, json, and pickle. There are 3 exercises that use the same data as the previous Assignment 4, on analyzing the filenames in an annotations subfolder. Specifically, these exercises include:

1. Exercise 1: Count the annotation by month and year. Determine which month with the most annotations
   * Kindly note to change the 'folder' variable to your respective folder path
2. Exercise 2: Create a dictionary where each key is a month, and the corresponding value is a list containing all the annotation names with where their date corresponds to the month.
   * Subexercises
       * a. Save it following the json format, and load it again to check that everything is ok.
       * b. Save it this time using Pickle.
       * c. Instead of storing a list of all the annotation names happening that month, let's create for each annotation a dictionary with keys: name and date (using a datetime object). 
4. Exercise 3: Print all the annotations from the oldest ones to the newest one during the seconf half of the 2024. 

**Important tasks:** 
  * Same with Assignment 4, you need to download the "session_4" folder that can be found inside the "Assignment 5" folder, as this includes the annotation files used.
  * In Exercise 1, make sure to change the "folder" variable to your respective folder path

## Python for Data Science: Assignment 6

Assignment 6 is about exploring the functionalities of the Pandas library. This assignment uses two datasets on 1) Netflix and 2) Titanic. Specifically, these exercises include:

On the Netflix dataset,
1. Exercise 1: Count the missing ratings
2. Exercise 2: Count the number of films in 2021 that correspond to a country
3. Exercise 3: Count the number of movies in 2020 with full information
4. Exercise 4: Determine the year with the most number of titles released
5. Exercise 5: Calculate the average yearly releases since 2010

On the Titanic dataset,
1. Exercise 1: Calculate the gender-based survival percentage
2. Exercise 2: Calculate the survival percentage based on gender and class

**Important tasks:** 
  * Make sure to download the "netflix_titles.csv" and "train_and_test2.csv" files that can be found inside the "Assignment 6" folder, as these datasets are used in the exercise.

## Python for Data Science: Assignment 7

Assignment 7 covers more advanced functionalities of the Pandas library, focusing on data transformation. This assignment uses data on professors and their course details. Specifically, these exercises include:

1. Exercise 1: Create a new column that stores the professors' initials
2. Exercise 2: Join a course dataframe with the original dataframe, based on the professor column
3. Exercise 3: Combine the original professor dataframe and the course dataframe
4. Exercise 4: Create a new column that extracts the professors' last names using string operations

## Python for Data Science: Assignment 8

Assignment 8 is about exploring plotting techniques and customizations, specifically using Matplotlib and Seaborn. This assignment uses data on students and their study time. Specifically, these exercises include:

1. Exercise 1: Create a **lineplot** showing how Study Time varies by Student Name. Determine which student has the highest study time.
2. Plot a **histogram** (*histplot*) of Grade. Determine which grade range has the highest frequency of students.
3. Create an **ECDF plot** (*ecdfplot*) for Grade. Calculate the percentage of students who scored less than 85.
4. Create a **stripplot** showing Grade distribution for each Course. Determine which course has the most spread in grades.
5. Create a **swarmplot** to show the relationship between Gender and Study Time. Determine which gender has a higher average study time.
6. Plot a **pointplot** to show the average Grade for each Course. Determine which course has the highest average grade.
