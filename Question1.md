Question no. 1 Discuss string slicing and provide example. ?

<<Answer>>

<< String Slicing >>
String slicing is a powerful feature in programming that allows you to extract a subset of characters from a string. It's a common operation used in text processing, data manipulation, and more.

Basic Syntax
The basic syntax for string slicing is:

string[start:stop:step]
Where:

start: The starting index of the slice (inclusive).
stop: The ending index of the slice (exclusive).
step: The increment between indices (default is 1).
Example 1: Basic Slicing
Let's extract the first three characters from the string "Hello, World!":

my_string = "Hello, World!"
print(my_string[0:3])  # Output: "Hel"
In this example, we start at index 0 and stop at index 3 (exclusive), so we get the first three characters.

Example 2: Slicing with Step
Let's extract every other character from the string "abcdef":

my_string = "abcdef"
print(my_string[::2])  # Output: "ace"
Here, we start at index 0, stop at the end of the string, and step by 2, so we get every other character.

Example 3: Negative Indices
Let's extract the last three characters from the string "Hello, World!":

my_string = "Hello, World!"
print(my_string[-3:])  # Output: "ld!"
In this example, we start at index -3 (which means 3 characters from the end) and stop at the end of the string.

Example 4: Reversing a String
Let's reverse the string "Hello, World!":

my_string = "Hello, World!"
print(my_string[::-1])  # Output: "!dlroW ,olleH"
Here, we start at the end of the string, stop at the beginning, and step backwards by 1.

These examples demonstrate the power and flexibility of string slicing. By adjusting the start, stop, and step indices, you can extract specific parts of a string or perform more complex text manipulations