# Assignment-02-Challenge-Question


Question:
1. Write a python program to sort the list of heterogeneous data. 
e.g. 
L = ["Ram", 1, "Shyam", 2, "Aman", 3]
print(L)
L.sort()
print(L)

Solution:

The sorted() function can be used with the key parameter. The key parameter specifies a function that is called for each element in the list and returns a value based on which the elements are sorted.
A lambda function can be used as the key function. It converts each element x to a string using the str() function. By converting all elements to strings, they can be compared and sorted correctly.
