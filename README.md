# Statement
Consider an algorithm that takes as input a positive integer n. If n is even, the algorithm divides it by two, and if n is odd, the algorithm multiplies it by three and adds one. The algorithm repeats this, until n is one. For example, the sequence for n=3 is as follows:
3 10 5 16 8 4 2 1  
Your task is to simulate the execution of the algorithm for a given value of n.  

Input  
The only input line contains an integer n.

Output  
Print a line that contains all values of n during the algorithm.

Constraints  
1 < n < 10^6

# Example
Input:  
3

Output:  
3 10 5 16 8 4 2 1

# Explanation
Used long long for worst cases like big number multiplies with 3. finally using the condition using ternary operator. then printing the desired outputs while n!=1(not equals to 1).

# Tests
Check tests.zip file inside the zip file you will find the tests with .in / .out extentions so open this files using notepad then you'll see all the tests results.
