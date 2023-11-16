# Safe Number Addition
 
 This JavaScript project aims to provide a secure environment for adding two numbers. The addTwoNums function takes two parameters, a and b, ensuring that both are valid numbers before performing the addition.

The addTwoNums function includes a try-catch block to handle potential errors:

If the type of a is not a number, it throws a ReferenceError with the message "the first argument is not a number."
If the type of b is not a number, it throws a ReferenceError with the message "the second argument is not a number."
If both parameters are valid numbers, it logs the result of the addition.