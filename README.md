# Sangeet Satpathy
This Github (SangeetSatpathy) has private code from exercises, labs and assignments from the following Foothill College courses:

CS1A (Object-Oriented Methodologies in Java) <br>
CS1B (Intermediate Software Design in Java) <br>
CS2A (Object-Oriented Methodologies in C++) <br>
CS3A (Object-Oriented Methodologies in Python) <br>
CS3B (Intermediate Software Design in Python) <br>
CS22A (Javascript for Programmers) <br>

## CS1A (Object-Oriented Methodologies in Java) Assignments
In this course, we learned OOP in Java through the use of a robot simulator.
### Assignment 1: Making New Robot Classes with New Methods
Makes a robot walk down a set of given "walls" in the simulator by definining and using functions.

### Assignment 2: Advanced Robots
Utilizes loops to make the robot run a course and pick up "points" at the end of each part of the course.

### Assignment 3: Robot Maze
A program that lets the robot run any solvable maze.

### Assignment 4: Guessing Game
A game that prompts the user to guess a number between -64 to 64. The program keeps repeating till the user guesses the right number or they run out of their 7 allowed attempts, notifying them each time whether the number is larger or smaller than the guessed number.

### Assignment 5: Graphical User Interfaces and Events
A simple applet to display different movie posters which the user can choose from in a drop-down menu, utilizing JavaFX.

## CS1B (Intermediate Software Design in Java) Assignments

## CS2A (Object-Oriented Methodologies in C++)
This course served as an introduction to C++ and its various features.
### Assignment 1:
###### Part 1: 
Formatting and printing outputs <br>
###### Part 2: 
storing variables.
### Assignment 2:
###### Part 1:
Simple program that asks the user for a number of cents and calculates the number of each coin that would be required (assuming the smallest number of coins is preferred). <br>
###### Part 2:
A program that converts an inputted Celsius value into Fahrenheit. <br>
###### Part 3:
Practice with various string functions in C++.
### Assignment 3:
###### Part 1:
A simple program which calculates the area of either a triangle or square. The user is asked if the shape they want is a triangle or square, then accordingly asks them for inputs and calculates the area. <br>
###### Part 2:
This program asks the user for the number of years of school they have been in. It then utilizes if-else statements to print out the school level they are in. <br>
###### Part 3:
This program serves as a basic calculator. It asks the user for a number, then the operator, then a second number.
It then prints out the answer, rounded to 2 decimal places. <br>
###### Part 4:
This program calculates the cost of calls made, depending on the start time of the call and its duration. It also takes into account a tax, which is assumed to be 4%.
### Assignment 4:
###### Part 1:
This program is a revision of the program in Assignment 1, which converts pounds to ounces. However, it will ask the user after every conversion whether they have another value they would like to convert. <br>
###### Part 2:
This program is a revision of the program in Assignment 1, which converts pounds to ounces. However, it will keep prompting the user to input a pound value until they enter a negative value, which exits the program. <br>
###### Part 3:
This program accounts for the ages of several attendees to an event. Each attendee's age and
food preference (choices being popcorn, soda, or both) are recorded. The program then counts and prints the number
of attendees in each age group, the average age (rounded to the tenth place), the oldest person, the youngest
person, and the number of attendees who prefer each food preference.

### Assignment 5:
###### Part 1:
This program first prompts the user to enter in how many numbers they will be entering for the set. It then prompts
them to enter each of the numbers. Once enterred, the program then prints out the position of the first and last
7 in the dataset. If there are no 7's in the dataset, it says so.
###### Part 2:
This program keeps asking the user to enter a number. The program then calculates the sum of all the squares of the numbers
below the inputted number. Inputting a number less than 1 into the prompt exits the program.
###### Part 3:
This program counts the number of words in several text files. It will keep asking the user to enter the name of the file.
If they enter 'quit', it will exit the program. After each inputted filename, the number of words will be printed. If
there was an error in opening the file, i.e the file doesn't exist, the program says so.

### Assignment 6:
This program draws a rocket, consisting of 2 cones at the top and bottom and several boxes called "phases".

### Assignment 7:
This is a simple math program which allows the user to customize their problem sets. There are 3 problem sets,
one for addition, one for subtracting, and one for multiplication. The user can change the number of problems
per set and the maximum number that can be generated. The program keeps track of the number of correct answers
and prints out a report at the end of all 3 sets.

### Assignment 8:
Programmed a class called Fraction, which represents a non-reducable fraction. Fractions can be set, added, subtracted,
multiplied, divided, and can they can be checked for if 2 fractions are equal.

### Assignment 9:
Built upon Assignment 8. Removed the set() function from the Fraction class and replaced it with a constructor. In this Assignment, I split the class into a header file and an implementation file. The professor provided us with the client program to test if it worked.

### Assignment 10:
This program prompts the user to input several numbers to store into an array. If the number is already stored in
the array, then it will not be added again. The program will keep asking the user to input numbers till they enter
a negative number. The program finally prints out the array, excluding all the extra empty spaces that haven't been
filled.

## CS3A (Object-Oriented Methodologies in Python)

### Temperature Mini-App
Assignments 1-11 (with the exception of Assignment 5) were built on top of each other to make a Temperature App. This application allows users to perform queries on a temperature dataset provided through a .csv file. The temperatures are organized such that each reading is paired with a location of where the sensor is, the sensor number, and whether the sensor is active or not.
These queries include finding the minimum, maximum, and average of all active temperatures. The program allows the user to pick from several options relating to the temperature, including: <br>
selecting a new temperature file to process, changing the units in which all the data is processed in, toggling which sensors are active, and various ways of presenting the data.

### Assignment 5
A program to reverse a list using recursion.

## CS3B (Intermediate Software Design in Python)
### Assignment 1:
#### Question 1:
Class implementation of a Circle. Includes instance variables of the x-value, y-value, radius. 
Circle contains several methods listed below:
min-x(): returns the minimum x-value of the circle
min-y(): returns the minimum y-value of the circle
max-x(): returns the maximum x-value of the circle
max-y(): returns the maximum y-value of the circle
getArea(): returns the area of the circle
getPerimeter(): returns the circumference of the circle
containsPoint(x, y): Returns true if the point inputted is within the circle, false if not.
containsCircle(circle): Returns true if the circle inputted is completely contained within the current circle object.
overlaps(circle): Returns true if the circle overlaps with the circle inputted.

#### Question 2:
Implementating of a Triangle Class. Triangle has 3 instance variables: the lengths of each side of the triangle (side1, side2, side3). Methods:
getArea(): returns area of the triangle
getPerimeter(): returns the perimeter of the triangle.
toString(): returns a string containing each of the side lengths of the triangle.

#### Question 3:
Implementing an Employee Class and its child class, ProductionWorker. The Employee class has attributes employee_name and employee_number. The ProductionWorker class has 2 additional attributes, shift_number and pay_rate.

### Assignment 2:
#### Question 1: 
Implemented 2 functions - list_to_listofdicts(), which takes in 2 lists and 2 names, and returns a list of dictionary values based on this.
The second function creates a dictionary of matching indeces of 2 lists.
#### Question 2:
match_key_value_pairs(dict1, dict2): returns all the matching key-value pairs in both the dictionaries.
sort_counter(dict): Sorts a dictionary and prints out the sorted values as tuples.
#### Question 3:
Reverses a string.

## CS22A (Javascript for Programmers)
### Assignment 2:
An HTML page which prompts the user to input a Fahrenheit temperature, converts it to Celsius, and displays it.
### Assignment 3:
A web application that prompts the user to input data for the amount of sales that their company has had for 4 quarters from 2 regions. The app then displays the results, both sorted by quarter and by region. Finally, it displays the total sales.
### Assignment 4:
A simple website in which the user can input the amount of change they have, from 0-99 cents. The program provides an error if the number entered is not within that range. The program them prints out the number of Quarters, Dimes, Nickels, and Pennies needed to make that change, using the fewest number of coins.
### Assignment 5:
Program for a simple sales tax calculator. The user enters their subtotal($0-$1000) and their tax percentage(0% - 12%). Once they click the calculate button, the program will output the sales tax and the total amount. The user also has the option to clear all the textboxes on the site. If the user inputs a value outside of the  acceptable range, then the program will throw an alert message.
### Assignment 6:
A web app that keeps track of test scores. The user enters their name and their score. This can be inputted numerous times, with each value stored into an array. The user can then choose to display the results, showing the highest scorer along with their score. The user can also choose to show every person and their associated score.
### Assignment 7:
A web app that keeps track of the time (down the millisecond). The website additionally has a stopwatch embedded into it.
### Assignment 8:
This is the first JQuery Assignment. This Assignment is a simple information website on a book. The user can click on links on the page to show and hide related information.
### Assignment 9:
A program that displays the different book covers for the different editions of Murach's Javascript books utilizing animations. The user can click on different covers in the slide panels below, and the main image above it will fade out, moving left, change depending on what the user clicked, and fade in once the image has changed, moving right.
