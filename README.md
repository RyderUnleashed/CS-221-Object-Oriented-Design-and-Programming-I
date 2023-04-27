# CS-221-Object-Oriented-Design-and-Programming-I

These are rudimentary projects provided by Hannah Hillberg, that I coded and submitted in my CS-221 class.

To prevent anyone, and myself for that matter, from violating University of Wisconsin - Oshkosh's Academic Honesty Policy,
I do not condone or grant the reuse and resubmission of these projects under another student's name. This repository is here to serve as a portfolio. That being said, these projects are licensed under **agpl-3.0**. Follow github's licensing policy and copyright laws.

Feel free to download and test my submitted code. These were coded in Java using BlueJ.

Alex

## Lab1 ##

### FirstLab ###

This class simply outputs the text, "Hello World!" followed by my name. Very Simple.

### Face ###

This class outputs an ASCII tiki head of sorts. Also simple.

## Lab2 ##

### TicketBot ###

This class simulates the purchase of travel tickes. It'll ask for the user's full name, how many tickets they need, where they'd like to go, and their desired budget. It'll then summarize the information at the bottom and the program ends with the output, "Loading options...".

## Lab3 ##

### ColorMixer ###

This class will ask the user for two RGB values as a single integer (Ex. 255,255,255) and a mixing ratio (out of 100). It'll then mix the two colors using the formula, *rv*<sub>1</sub> + (1 - *r*)*v*<sub>2</sub>, with *v*<sub>1</sub> being the user's first RGB value, *v*<sub>2</sub> being the user's second RGB value, and *r* being the mxing ratio. It'll then output the mixed color's R, G, and B values.

## Lab4 ##

### RandoFibo ###

This class will ask the user for a minimum value and a maximum value and then proceed to randomly pick a number between, and including, those two values. With the new random number, it'll use the formula, F<sub>N</sub> = [φ<sup>N</sup> - (1 - φ<sup>N</sup>)] / √5, to calculate the random number's approximate fibonacci number. F<sub>1</sub> = 1, F<sub>2</sub> = 1, F<sub>3</sub> = 2, F<sub>4</sub> = 3, F<sub>5</sub> = 5, and so on.

### RandoCharLeader ###

This class will simply pick a random uppercase character (A-Z), a random lowercase character (a-z), a random special character (@#$%^&*()), and output it as a single string in the form of a cheer. Requires no user input.

### AccountInfo ###

This class asks the user for their full name and "credit card number" (Don't actually put your real CC#). It'll greet the user by their given name and give them a username consisting of their last name and the first letter of their first name. It'll then state your credit card number, masking 12 out of the 16 digits with asteriks (*), regardless of whether or not the user put dashes (-) between their CC# or not.

## Lab5 ##

### TitanTreats ###

This class simulates the purchase of cupcakes based on a variety of conditions using **if** statements. It'll ask the user for how many cupcakes they want, additional frosting, sprinkles, or filling, and if they'd like it delievered. The program will then sum up the order info and display the user's delivery address, if inputted, separating the street, city, state, and zip code from the user's address.

## Lab 6 ##

### Zodiac Sign (A & B) ###

This class simply asks the user for their birth date (month & day) and figures out what their zodiac sign is based on their input. Part A uses **if** statements and part B uses **switch** statements.

### Alphabetize ###

This class asks the user to give three words of their choosing, arranging and displaying the words in alphabetical order. The program uses the string **compareTo()** method.

## Project 1 ##

### Infant Weight Evaluator ###

This class determines if an infant is in a healthy age/weight range while also offering the choice between different measurements. The user can choose between:
1 - months and kg, 2 - years and kg, 3 - months and lbs, 4 - years and lbs. It'll then apply either one of the formulas: weight(kg) >= age(months) / 3 + 2 **OR**  weight(kg) <= 5 * age(months) / 12 + 5, to determine if the infant is healthy or not.

## Lab 7 ##

### Regular Factor Finder ###

This class prompts the user to enter a number and proceeds to output every factor of the inputted number. If a number is prime, it'll only output the number one and the user's inputted number.

### Smallest Factors Finder ###

This class prompts the user to enter a number and proceeds to output the smallest factors of the inputted number, such that when multiplied together, will make up the inital inputted value.

## Lab 8 ##

### Letter Occurences ###

This class will prompt the user to enter a string and a letter to find in that string. The program will then output the amount of times the user's inputted letter occurs throughout their string.

### Duplicate Letters? ###

This class will prompt the user to enter a string. The program will then output whether or not their inputted string contains any duplicate letters or not.

## Lab 9 ##

### Count Most-Occurring Letter ###

This class will prompt the user to enter a string. It'll then find which letter occurs the most throughout the string and print it.

### Halloween Candy ###

This class will prompt the user to enter the amount of candy that they received and what kind of candies they got. It'll then print out the different combinations of candies they could do, avoiding duplicates unless there's explicitly multiple of that candy, i.e Candy 1: m&ms and Candy 2: m&ms.

## Project 2 ##

### Grade Point Average Computer ###

This class simply calculates the user's GPA by prompting the user to enter a letter grade and the amount of credits for the course. The program uses switch statements and printf to calculate and output the results for the term and cumulatively.

## Lab 10 ##

### Methods ###

This class works with methods. The first method, "generateUsername", takes three hardcoded calls and generates a username from the inputted string of text. The second method, "charNTimes", takes three more hardcoded calls and prints the inputted character the specified number of times. The third and final method, "maskN", takes three more hardcoded calls and outputs a string of text masked with the specified character the specified amount of times.

## Project 3 ##

### Utilarries ###

This class also works with methods. The first method, "toString", returns a string representation of a character or string array. The second method, "isSorted", determines if the array given is in the correct order, return a boolean value of true or false. The third method, "subArray" returns an array of characters that represents the portion of a given array of characters from a given starting point to a given end point, if provided. The fourth method, "compare", compares two character arrays and determines which one comes before the other alphabetically. '1' if the second one, '-1' if the first one. The fifth method, "areEqual", compares two character arrays and returns a boolean value of true or false determined by whether or not the two arrays are equal. The sixth method, "locationIn", returns an integer that represents the index of where a given character array sequence appears within another given character array sequence, or -1 if it doesn't appear. The user may provide a start index if they wish. The seventh method, "appearsIn", returns a boolean value determined by whether or not a given character array sequence appears within another given character array sequence. The final method, "drawItems", takes an array of strings, a number of how many to draw from the given array, and returns a string representation of the array with that many elements drawn at random from the given array. This method avoids drawing duplicates unless multiple of the same string is present.

## Lab 11 ##

### Baseball Scoreboard ###

This project emulates a baseball scoreboard using methods and multiple classes.

## Project 4 ##

### Yahtzee ###

This project emulates a game of Yahtzee using methods and multiple classes that are instantiated in Main.
