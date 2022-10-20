# CS-221-Object-Oriented-Design-and-Programming-I

These are rudimentary projects that I coded and submitted in my CS-221 class.

To prevent anyone, and myself for that matter, from violating University of Wisconsin - Oshkosh's Academic Honesty Policy,
these projects are my own intellectual property and are to not be reused and resubmitted under someone else's name.
These projects will remain UNLICENSED. Follow github's licensing policy and copyright laws.

That being said, feel free to download and test my submitted code. These were coded in Java using BlueJ.

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
1 - months and kg, 2 - years and kg, 3 - months and lbs, 4 - years and lbs. It'll then apply either one of the formulas: weight(kg) >= age(months) / 3 + 2 **or**  weight(kg) <= 5 * age(months) / 12 + 5, to determine if the infant is healthy or not.
