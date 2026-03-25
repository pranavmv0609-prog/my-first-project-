# my-first-project-
This program is a basic calculator written in C that performs four operations: addition, subtraction, multiplication, and division.

First, the program includes the standard input-output library so it can take input from the user and display output on the screen.

Inside the main function, it declares variables: one character variable to store the operator (+, -, *, /) and three float variables to store the two input numbers and the result.

The program then asks the user to enter an operator and reads it using scanf. After that, it asks for two numbers and stores them.

Next comes the main logic using a switch statement. Based on the operator entered:

If the operator is +, it adds the two numbers.
If it is -, it subtracts the second number from the first.
If it is *, it multiplies the numbers.
If it is /, it divides the numbers, but first checks if the second number is not zero to avoid division error.

If the user enters an invalid operator, the program shows an error message.

Finally, the program displays the result and ends successfully.
