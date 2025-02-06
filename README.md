#Lab 3

Find All Duplicates
Write a function (or static method in the case of Java) that accepts a list of integers and returns a list of only
those integers that appear more than once.

Add to README.md
Describe Different Approaches to Solving This Problem
Describe the two different ways to figure out all of the duplicate values of a list of integers in english. 
The first solution is the nested loop solution. The second solution is to use a dictionary or a map 
(similar to the containsPair method we wrote in class. 
Describe both in as much detail as you can (with no code) and describe the trade-offs between the two solutions.

The nested loop solution goes through the array and checks each value with every other value in a nested loop. 
It has O(n^2) complexity. The second solution was much more efficient, using aspects of a data structure that 
treats duplicates differently, such as removing them. These solutions have O(n) complexity.
