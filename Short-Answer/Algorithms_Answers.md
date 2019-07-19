Add your answers to the Algorithms exercises here.

Excercise 1
a) O(n)
b) O(n^n)
c) O(n)

Exercise 2
A good solution for the egg drop would be to use a binary search, which is O(log n)
Step 1: find the midpoint of the building by dividing the total number of floors in half
Step 2: compare midpoint to __f__ 
        if equal return index of __f__ 
        if midpoint > __f__, __f__ must be in left sub-array
        if midpoint < __f__, __f__ must be in right sub-array

Step 3: repeat on subsequent sub-arrays until midpoint == __f__
