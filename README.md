Download Link: https://assignmentchef.com/product/solved-solvedassignment02
<br>
Instructions:

– You are required to turn in a hard copy of all problem solutions as a package stapled with a cover page. The cover page should include: your name, assignment number, and turn in and due dates. You are also required to turn in four files, prob1.c, prob2.c, prob3.c, and prob4.c for problems 1 through 4. Use Blackboard to turn in the files.

– All assignment work should reflect your own work.

1 Write a program that calculates and prints the Fibonacci number of a user specified rank. For example if the user enters the rank = 9 the program prints in a new line “The Fibonacci number at rank 9 is 21”.

2 Write a program that prompts a user for an integer value in the range 0 to 32,767 and then prints the individual digits of the numbers on a line with three spaces between the digits. The first line is to start with the leftmost digit and print all five digits; the second line is to start with the second digit from the left and print four digits, and so forth. For example if the user enters 1234, your program should print

0 1 2 3 4

1 2 3 4

2 3 4

3 4

4

3 Write a menu driven program that allows a user to enter five numbers and then choose between finding the smallest, largest, sum, or average. The menu and all the choices are to be functions. Use a switch statement to determine what action to take. Provide an error message if an invalid choice is entered.

4 Write a program to create a calendar for a year. The program reads the year from the keyboard. It then calculates which day of the week (SUN through SAT) is the first day of the year and prints the calendar for that year. After printing the year the program should ask if the user wants to continue. If the answer is yes, it will print the calendar for another year until the user is done. Below is an example of how a one month should look like when it is printed.

JANUARY 2000

SUN MON TUE WED THU FRI SAT

1

2 3 4 5 6 7 8

9 10 11 12 13 14 15

16 17 18 19 20 21 22

23 24 25 26 27 28 29

30 31

Hint1: To print the correct calendar for the requested year, you must first find which day of the week is the first day of that year. This can be done with the following formula.

DAY =

DAY=0: SUN

DAY=1: MON

DAY=2: TUE

DAY=3: WED

DAY=4: THU

DAY=5: FRI

DAY=6: SAT

Hint2: You must also calculate leap years. The formula for calculating leap years is:

(!(year % 4) &amp;&amp; (year % 100)) || !(year % 400)