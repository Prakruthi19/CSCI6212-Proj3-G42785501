**Overview**

This project provides a Java solution to the partition problem, where the goal is to check if a given set of integers can be divided into two subsets with equal sums. The approach uses dynamic programming, achieving a pseudo-polynomial time complexity of O(ns), where 
n is the number of elements and 
s is the sum of all elements.

**Problem Statement**

Given a set of integers [a1, a2, ..., an], determine if it can be partitioned into two subsets with equal sums. If the total sum of elements, 
s, is even, we check if a subset with sum 
s/2 exists.

**Solution Approach**

Calculate the total sum of the set. If the sum is odd, return false.
Use a dynamic programming (DP) array to track achievable subset sums up to s/2.
Check if the subset sum s/2 is possible, returning true if it is, and false otherwise.

**Running the Code**

To run:
bash
Copy code
javac PseudoPolynomialPartition.java
java PseudoPolynomialPartition

**Requirements**
Java 8 or higher
