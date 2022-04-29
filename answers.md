# CMPS 2200 Assignment 5
## Answers

**Name:**____Riley Martin_____________________


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**

A greedy algorithm would select the coin with the highest value and then the next highest until N dollars are produced. The amount of money needed, N, is fixed so the greedy algorithm is optimal. 

   1b.

  Work and Span are both O(log(n))

   2a. 

  If there are 1, 5, and 6 dollar denominations and you need 10  dollars, a greedy algorithm would use 5 coins: 6,1,1,1,1. While, non greedy algorithms would use two coins: 5,5. 


- **2b.**

A bottom up dynamic approach could be taken by filling a table with denominations and powers of each denomination. The work is O(nk) where n is the length of the denomination set and k is the highest power. The span is O(n), the longest path in DAG.

