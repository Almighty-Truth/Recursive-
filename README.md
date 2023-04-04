# Recursive-  

The problem is to write a recursive function that replaces all lowercase 'x' characters in a given string with 'y' characters. Here's how you can approach the problem:

Base case: If the input string is empty, return an empty string.
Recursive case: If the first character of the string is 'x', replace it with 'y' and recursively call the function with the remaining substring. If the first character is not 'x', simply concatenate it with the result of the recursive call on the remaining substring. 
