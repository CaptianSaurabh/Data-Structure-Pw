Question no. 7 >> Describe how to add, modify, and delete items in a dictionary with examples.

<<Answer>>

Working with Dictionaries in Python

>> Adding Items
To add an item to a dictionary, you can use the assignment operator (=) to assign a value to a new key.

Example

my_dict = {'name': 'John', 'age': 30}

# Add a new item
my_dict['city'] = 'New York'

print(my_dict)  # Output: {'name': 'John', 'age': 30, 'city': 'New York'}


>> Modifying Items
To modify an existing item in a dictionary, you can use the assignment operator (=) to assign a new value to an existing key.

Example

my_dict = {'name': 'John', 'age': 30}

# Modify an existing item
my_dict['age'] = 31

print(my_dict)  # Output: {'name': 'John', 'age': 31}

>> Deleting Items
To delete an item from a dictionary, you can use the del statement or the pop() method.

Example (using del statement)
my_dict = {'name': 'John', 'age': 30, 'city': 'New York'}

# Delete an item
del my_dict['city']

print(my_dict)  # Output: {'name': 'John', 'age': 30}

Example (using pop() method)
my_dict = {'name': 'John', 'age': 30, 'city': 'New York'}

# Delete an item and return its value
city = my_dict.pop('city')

print(my_dict)  # Output: {'name': 'John', 'age': 30}

print(city)  # Output: New York


>> Additional Methods
update(): Updates a dictionary with new key-value pairs.
setdefault(): Sets a default value for a key if it doesn't exist.
get(): Returns the value for a key if it exists, or a default value if it doesn't.


1. Example (using update() method)
my_dict = {'name': 'John', 'age': 30}

# Update the dictionary with new key-value pairs
my_dict.update({'city': 'New York', 'country': 'USA'})

print(my_dict)  # Output: {'name': 'John', 'age': 30, 'city': 'New York', 'country': 'USA'}
These are the basic operations you can perform on a dictionary in Python.