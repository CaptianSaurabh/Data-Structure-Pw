Question No. 3 >> Describe how to acsess , modifi and delete element in list with example ? 


<<Answer>>

<< Accessing, Modifying, and Deleting Elements in a List >>

## 1 Accessing Elements
Use indexing to access an element: my_list[index]
Example: my_list = [1, 2, 3, 4, 5]; print(my_list[0]) # Output: 1


## 2 Modifying Elements
Use indexing to modify an element: my_list[index] = new_value
Example: my_list = [1, 2, 3, 4, 5]; my_list[0] = 10; print(my_list) # Output: [10, 2, 3, 4, 5]


## 3 Deleting Elements
Use the del statement: del my_list[index]
Example: my_list = [1, 2, 3, 4, 5]; del my_list[0]; print(my_list) # Output: [2, 3, 4, 5]

Use the remove() method: my_list.remove(value)
Example: my_list = [1, 2, 3, 4, 5]; my_list.remove(3); print(my_list) # Output: [1, 2, 4, 5]


Note: remove() method removes the first occurrence of the specified value. If the value is not found, it raises a ValueError.