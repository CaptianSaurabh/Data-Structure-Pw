Qustion no. 4 >> Compare the contrast tuple and list with example.

<<Answer>>

<< Tuple vs List in Python >>
Similarities
Both tuples and lists are data structures that can store multiple values.
Both can be indexed and sliced.
Both can be used to store heterogeneous data (i.e., different data types).
Differences

## 1. Immutability
Tuple: Immutable, cannot be modified after creation.
List: Mutable, can be modified after creation.

## 2. Syntax
Tuple: Defined using parentheses () and elements are separated by commas.
List: Defined using square brackets [] and elements are separated by commas.

## 3. Use Cases
Tuple: Use when you need an immutable collection of values, such as a point in 2D space (x, y).
List: Use when you need a dynamic collection of values that can be modified, such as a list of items in a shopping cart.


<< Examples >>


## Tuple
my_tuple = (1, 2, 3)
print(my_tuple[0])  # Output: 1
my_tuple[0] = 10  # TypeError: 'tuple' object does not support item assignment



## List
my_list = [1, 2, 3]
print(my_list[0])  # Output: 1
my_list[0] = 10
print(my_list)  # Output: [10, 2, 3]
In summary, tuples are immutable and used for fixed collections, while lists are mutable and used for dynamic collections.