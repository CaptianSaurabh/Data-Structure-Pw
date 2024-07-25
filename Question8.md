Question no. 8 >> Discuss the importance of dictionary keys being immutable and provide example.

<<Answer>>

Importance of Immutable Dictionary Keys
In Python, dictionary keys must be immutable because they are used to identify and store values in the dictionary. Immutable keys ensure that the dictionary can efficiently store and retrieve values.

Why Immutable Keys are Important
Hashability: Immutable keys can be hashed, which allows dictionaries to store and retrieve values efficiently.
Uniqueness: Immutable keys ensure that each key is unique, preventing duplicate keys and ensuring correct value retrieval.
Predictability: Immutable keys guarantee that the dictionary's internal structure remains consistent, making it easier to predict and debug behavior.

>> Example: Mutable vs. Immutable Keys


Mutable Key (List)

my_dict = {[1, 2, 3]: 'value'}  # Error: unhashable type: 'list'

This will raise a TypeError because lists are mutable and cannot be used as dictionary keys.


Immutable Key (Tuple)

my_dict = {(1, 2, 3): 'value'}  # Valid
print(my_dict)  # Output: {(1, 2, 3): 'value'}

This is valid because tuples are immutable and can be used as dictionary keys.

In summary, immutable dictionary keys are essential for efficient and predictable dictionary behavior.