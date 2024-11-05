# Exception-handling
# App used: VS code
# Theory
## Definition
In C++, exception handling is amechanism that provides a way to manage errors and exceptional situations in a structured manner. The primary components involved in exception handling are:

## Key Concepts:

Exception: An event that disrupts the normal flow of a program. In C++, exceptions are typically represented as objects derived from the std::exception class.
Throwing an Exception: Use the throw keyword to signal that an error has occurred. This transfers control to a nearby catch block.
Catching an Exception: Use try blocks to enclose code that may throw exceptions. Corresponding catch blocks handle specific types of exceptions.
Multiple Catch Blocks: You can have multiple catch blocks to handle different exception types, allowing for more specific error handling.
Catch-All Handler: A catch-all handler (catch (...)) can be used to catch any exception that wasn’t previously caught.
Custom Exceptions: You can define your own exception classes by inheriting from std::exception, allowing for more meaningful error information.

# Algorithms
## Age Validation Algorithm
Start.
Initialize a variable age to store the user's input.
Prompt the user to "Enter your age:".
Read the user's input into the variable age.
Try the following:
Check if age is less than 0:
If true, throw an exception indicating an invalid age.
Check if age is less than 18:
If true, throw an exception indicating that the user is below 18.
If both checks are false, print "Accepted".
Catch any exceptions:
If the exception indicates an invalid age (less than 0), print "Invalid age".
If the exception indicates age below 18, print "You are below 18".
End.

## Zerodvision Error Algorithm
Start.
Declare variables n1, n2, and ans to store the two numbers and the result.
Prompt the user to "Enter the values of numbers 1 and 2:".
Read the user's input into the variables n1 and n2.
Try the following:
Check if n2 is equal to 0:
If true, throw an exception with the value of n2.
If the check is false, calculate ans as n1 / n2.
Print the result as "The answer is [result]".
Catch any exceptions:
If an exception occurs, print "ERROR: Division by [number]".
End.

# Conclusion
We learnt to use exception hndling blocks in this experiment.
