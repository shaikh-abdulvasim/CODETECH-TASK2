# CODETECH-TASK2

NAME: SHAIKH ABDULVASIM

COMPANY: CODTECH IT SOLUTIONS

ID: CT08DS6266

DOMAIN: PYTHON PROGRAMMING

DURATION: Aug TO September 2024

MENTOR: SANTHOSH KUMAR

# OVERVIW OF PROJECT
The code defines a Student class to manage a student's grades and calculate their average. It prompts the user to input the student's name, subjects, and grades, and then displays the student's grades along with the average and overall letter grade. The program continues taking input until the user finishes by typing "done."

* Student Class:
The Student class is designed to store and manage a student's grades.

# Attributes:

* name: Stores the student's name.
  
* grades: A dictionary where keys are subject names and values are grades.
  
*Methods:
add_grade(subject, grade): Adds or updates the grade for a given subject.
calculate_average(): Calculates and returns the average grade across all subjects. If no grades are available, it returns 0.
display_info(): Prints the student's name, each subject with its corresponding grade, the overall average grade, and the overall letter grade (A, B, C, D, F) based on the average.

# Main Program (main Function):
> Purpose:
The main function handles user input and interaction with the Student class.

# Steps:

* Student Name Input:
The program prompts the user to enter the student's name, which is then used to create an instance of the Student class.
Input Loop for Subjects and Grades:
The program enters a loop where it repeatedly asks the user to input a subject name and its corresponding grade.
The loop continues until the user types "done" as the subject name.
If the user enters a non-numeric value for the grade, an error message is displayed, and the user is prompted to re-enter the grade.
Display Information:
After the user has finished entering all the subjects and grades, the program calls display_info() to show the student's details, including each subject's grade, the overall average, and the letter grade.
* Program Execution:
The program begins execution in the main() function, where it manages user input and interactions.
The program continues to take input until the user signals they are finished by typing "done".
Example Interaction:

*User Input:
The user is prompted to enter the student's name and then repeatedly prompted to input subject names and grades until they choose to stop.

* Output:
After all input is received, the program outputs the student's name, each subject with its grade, the calculated overall average, and a corresponding letter grade.

# Key Features:
User-Driven Input: The program dynamically accepts input for any number of subjects and grades.
Error Handling: It checks that grades are numeric, ensuring valid input.
Detailed Display: The program calculates and displays detailed information, including the overall grade and corresponding letter grade.
