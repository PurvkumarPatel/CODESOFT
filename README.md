# CODESOFT C++ Programming Internship
Welcome to the CODESOFT C++ Programming Internship repository! This repository contains the solutions to the tasks assigned during the internship program
## About CODESOFT
CODESOFT is a vibrant and diverse community that brings together individuals with similar objectives and ultimate goals. The main focus of the organization is on creating opportunities that span various areas, including leadership development, learning, student engagement, and fostering shared interests.

We believe in the power of leadership and its ability to drive positive change. That's why we provide platforms and resources for our community members to develop their leadership skills. Through mentorship programs, workshops, and collaborative projects, we empower individuals to take on leadership roles and make a difference in their respective fields.
## Task 1 - Number Guessing Game
This program generates a random number between 1 and 10 and asks the user to guess it. The user will receive feedback on whether the guess is too high or too low until they guess the correct number.
### Approach
1) The code generates a random number between 1 and 10 (inclusive) using the rand() function.
2) The program then asks the user to guess the number.
3) Depending on the user's input, the program provides feedback:
    - If the user guesses the correct number, it displays "You guessed the correct number."
    - If the user's input is out of the range (1 to 10), it displays "Invalid Input !!"
    - If the user's guess is within one number difference from the correct number, it displays "Too close try again."
    - If the user's guess is greater than the correct number, it displays "Try a smaller number."
    - If the user's guess is smaller than the correct number, it displays "Try a greater number."
4) The user continues guessing until they get the correct number, and the loop continues until that happens.
## Task 2 - Simple Calculator
Develop a calculator program that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The user will be prompted to input two numbers and choose an operation to perform.
### Approach
1) The program displays a simple calculator menu with the available operations: Addition (+), Subtraction (-), Multiplication (*), Division (/), and an option to Exit the calculator (dot '.').
2) The program takes the user's input for the desired operation.
3) If the user enters an invalid operation, the program displays "Invalid operation !!" and continues to the menu.
4) If the user chooses the Exit option, the program ends.
5) For valid operations, the program asks the user to input two numbers and validates that the input is a valid number.
6) After getting the numbers, the program performs the chosen operation and displays the result with fixed precision.
7) The loop continues until the user decides to exit.
## Task 3 - Student Grading System
Create a program that manages student grades. The user can input student names and their corresponding grades. The program will calculate the average grade and display it, along with the highest and lowest grades.
### Approach
1) The program asks the user to enter student details, including first name, last name, and letter grade.
2) The program validates the entered letter grade against a predefined GPA grade system.
3) If an invalid letter grade is entered, the program asks for valid input.
4) The student information is stored in a vector of structures called students.
5) The program calculates the average grade based on the GPA grade system.
6) It finds the highest and lowest grades among the students.
7) The program then displays the student details in tabular form and the average, highest, and lowest grades.
## Task 4 - Word Count
Develop a program that counts the number of words in a given text file. The user will be prompted to enter the file name, and the program will display the total word count.
### Approach
1) The program prompts the user to enter the name of a text file.
2) It opens the specified file and reads its contents into a string.
3) The program uses a stringstream to extract individual words from the file content and counts them.
4) It then displays the total number of words in the file.
## Task 5 - Movie Ticket Booking System
This program simulates a movie ticket booking system. Users can view movie listings, select seats, make bookings, and calculate the total cost. Seat availability and seat selection validation are implemented.
### Approach
1) The program sets up a 3x5 array to represent three different movies, each with 25 seats.
2) It displays the movie listings along with their details (time and cost) to the user.
3) The user is asked to select a movie and enter the number of tickets they want to purchase.
4) If the selected movie or number of tickets is invalid (e.g., not enough available seats), the program prompts the user to try again.
5) The program displays the seat map for the selected movie, and the user is asked to input the row and column numbers for each ticket.
6) If the selected seat is already booked or the input is invalid, the program prompts the user to choose another seat.
7) The program calculates the total cost of the tickets based on the movie choice and the number of tickets.
8) It then marks the selected seats as booked in the seat map.
9) The loop continues until the user decides to exit (by selecting movie 0).
## How to Run the Programs
To run any of the tasks, follow these steps:

1) Make sure you have a C++ compiler installed on your machine.
2) Copy the code from the respective task and save it with the appropriate file name and extension (e.g., task1.cpp).
3) Compile the code using the C++ compiler.
4) Execute the compiled program in the terminal or command prompt.
## Contributions and Feedback
This repository is a collection of my internship tasks. Feel free to enhance the code, add more functionality, or optimize the solutions further. Additionally, you are welcome to share your feedback, suggestions, or ideas to improve the internship program further.

Happy coding and learning! 🚀
