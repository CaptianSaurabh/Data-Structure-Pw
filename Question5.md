Question no. 5 >> Describe the key features of sets and provide examples of their use 


<<Answer>>

<< Key Features of Sets in Python >>
1. Unordered Collection
Sets are an unordered collection of unique elements.
2. No Duplicates
Sets automatically remove duplicates.
3. Fast Membership Testing
Sets provide fast membership testing using the in operator.
4. Mathematical Operations
Sets support mathematical operations like union, intersection, and difference.

<< Examples >>

Creating a Set
my_set = {1, 2, 3, 2, 4}  # duplicates are removed
print(my_set)  # Output: {1, 2, 3, 4}

1. Membership Testing
my_set = {1, 2, 3}
print(2 in my_set)  # Output: True
print(4 in my_set)  # Output: False

2. Mathematical Operations
set1 = {1, 2, 3}
set2 = {3, 4, 5}

# Union
print(set1 | set2)  # Output: {1, 2, 3, 4, 5}

# Intersection
print(set1 & set2)  # Output: {3}

# Difference
print(set1 - set2)  # Output: {1, 2}
Use Cases
Removing duplicates from a collection
Fast membership testing
Performing mathematical operations on collections
Note: Sets are mutable, but they cannot contain mutable elements like lists or dictionaries.