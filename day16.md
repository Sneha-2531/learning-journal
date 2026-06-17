# Day 16 – June 17, 2026  
**Topic: Python Tuples**

## Topics Covered
- Difference between List and Tuple  
- Tuple characteristics:  
  - Ordered collection  
  - Immutable (cannot be modified after creation)  
  - Allows duplicate values  
- Creating tuples  
- Creating a tuple with a single element using a trailing comma  
- Accessing tuple elements using indexing  
- Tuple slicing  
- Tuple operations:  
  - Concatenation (`+`)  
  - Repetition (`*`)  
- Using `len()` function with tuples  

## Key Learnings
- Tuples are useful when data should remain unchanged throughout the program.  
- They provide better performance and data safety compared to lists.  

## Code Examples
```python
# Creating a tuple
my_tuple = (1, 2, 3, 4)
print(my_tuple)

# Tuple with a single element (note the comma)
single_tuple = (5,)
print(single_tuple)

# Accessing elements
print(my_tuple[0])   # First element
print(my_tuple[-1])  # Last element

# Tuple slicing
print(my_tuple[1:3])  # Elements from index 1 to 2

# Concatenation
tuple1 = (1, 2)
tuple2 = (3, 4)
print(tuple1 + tuple2)

# Repetition
print(tuple1 * 3)

# Length of tuple
print(len(my_tuple))
