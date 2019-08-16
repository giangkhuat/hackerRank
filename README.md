# HackerRank

Problems solved on HackerRank

**1. Minimum Bribes Problem**

  * Link: [Question Description](https://www.hackerrank.com/challenges/new-year-chaos/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=arrays)
  
  ---

**2. RansomNote Problem**: 

   * Link: [Question Description](https://www.hackerrank.com/challenges/ctci-ransom-note/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=dictionaries-hashmaps)
   
   ---
   
 **3. Greedy Method Problem**
 
   * Link: [Problem description](https://www.hackerrank.com/challenges/mark-and-toys/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=sorting)
   
   ---
   
  **4. Luck Balance Problem**
   * Link: [Problem Description](https://www.hackerrank.com/challenges/luck-balance/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=greedy-algorithms)
    
---
   **5. Ice Cream Parlor Search Problem**
   
   * 3 approaches included: HashMap, Sort and Binary Search, Moving Pointers
   * Link: [Question description](https://www.hackerrank.com/challenges/ctci-ice-cream-parlor/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=search)
    
---
   **6. Maximize Minimum Greedy Algorithm Problem**
   * Link: [Question description](https://www.hackerrank.com/challenges/angry-children/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=greedy-algorithms)
   * Passed all test cases

---
   **7. Maximum Sum of Subarray (using Dynamic Programming)**
   * This problem is a variation of Kadane's algorithm problem Maximum Sum of Subarray as the numbers in all subsets are non-adjacent in the original array
   * **Problem Statement**: Given an array of integers, find the subset of non-adjacent elements with the maximum sum. Calculate the sum of that subset.
   * The solution has time complexity O(N) and passed 32/32 test cases
   * Link: [Question Description](https://www.hackerrank.com/interview/interview-preparation-kit)
  
---
   **8. Alice Candies Dynamic Programming**
   *   **Problem Statement**: Alice is a kindergarten teacher. She wants to give some candies to the children in her class.  All the children sit in a line and each of them has a rating score according to his or her performance in the class.  Alice wants to give at least 1 candy to each child. If two children sit next to each other, then the one with the higher rating must get more candies. Alice wants to minimize the total number of candies she must buy.
   * Link: [Question Description](https://www.hackerrank.com/challenges/candies/problem?h_r=profile)
   * Work in progress: Passed 11/16 test cases 

---
  
   **9. Check Balanced Brackets**
   * **Problem Statement**: Given  strings of brackets, determine whether each sequence of brackets is balanced. If a string is balanced, return YES. Otherwise, return NO.
   * Link: [Question description](https://www.hackerrank.com/challenges/balanced-brackets/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=stacks-queues)
   * Passed all test cases
---

   **10. Largest Rectangular Area in Histogram using stack (Medium)**
   * **Problem Statement**: Given n non-negative integers representing the histogram's bar height where the width of each bar is 1, find the area of largest rectangle in the histogram.
   * Link: [Question Description](https://www.hackerrank.com/challenges/largest-rectangle/problem)
   * Passed 15/15 test cases
   * Time Complexity: O(n)
   * Solution using stack data structure
---
   **11. Min Max Riddle (Medium)**:
   * **Problem Statement**: Given an integer array of size , find the maximum of the minimum(s) of every window size in the array. The window size varies from 1 to n .
   * Work in progress
---
   **12. Castle On The Grid (Hard)**: 
   * **Problem Stateement**: You are given a square grid with some cells open (.) and some blocked (X). Your playing piece can move along any row or column until it reaches the edge of the grid or a blocked cell. Given a grid, a start and an end position, determine the number of moves it will take to get to the end position.
   * Link: [Problem Description](https://www.hackerrank.com/challenges/castle-on-the-grid/problem?filter=Vietnam&filter_on=country&h_l=interview&page=1&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=stacks-queues)
   * Work in progress: Passed 11/12 test cases (1 test case did not pass due to timed out)
---
   **13. BFS Shortest Path too all nodes in graph (Hard)**
   * **Problem Statement**: Consider an undirected graph consisting of n nodes where each node is labeled from 1 to n and the edge between any two nodes is always of length . We define node  to be the starting position for a BFS. Given a graph, determine the distances from the start node to each of its descendants and return the list in node number order, ascending. If a node is disconnected, it's distance should be -1 
   * Link: [Problem Description](https://www.hackerrank.com/challenges/ctci-bfs-shortest-reach/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=graphs).
   * Passed 8/8 Test Cases
   * Solution used Adjacency List and Queue
---
   **14. Connected Cells In a Grid (Hard)**
   * **Problem Statement**: Given an  matrix, find and print the number of cells in the largest region in the matrix.(region is defined as connected cells containg 1)
   * Link: [Description](https://www.hackerrank.com/challenges/ctci-connected-cell-in-a-grid/problem)
   * Passed 7/7 Test cases
   * Solution used Recursion, DFS concepts
---
   **15. Binary Tree Height (Easy)**
   * **Problem statement**: Find the height of a binary tree
   * Passed 7/7 test cases
   * Solution Using recursion
   * Time complexity: O(n)
---
   **16. Binary Search Tree Lowest Common Ancestor (Easy)**
   * **Problem Statement**: Find the lowest common ancestor of two nodes in a binary search tree
   * Passed 9/9 test cases
   * Solution used recursion concept 
   * Time complexity: O(n) with n is number of edges
   * Link: [Description](https://www.hackerrank.com/challenges/binary-search-tree-lowest-common-ancestor/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=trees)
---
   **17. Permutations of a list of numbers using Recursion (Medium)**
   * **Problem Statement**: Find all permutations of a list of integers
   * Approach: bottom-up. Starting with the base case, when list is empty or size 1, all permutations possible is just that list
   Else to create permutations for a list of size n, we producce permutations for the sublist size n-1, combine it with the n-th element. 
---
   **18. Fibonacci Sequence using Dynamic Programming (Easy)**
   * **Problem statement**: Given n, return nth element in the sequence
   * Passed 9/9 test cases
   * Time Complexity: O(n) (with dynamic programming)
   * Space Complexity: O(n) (can be optimized to be O(1) by initializing array of size 2
---
   **19. Missing element in the array**
   * **Problem Statement**: Given an array containing elements from 1 to n, find the missing element.
   * This is a problem outside HackerRank
   * Time Complexity: O(n)
---
   **20. Optimize with Greedy Algorithm**
   * **Problem Statement**: Given an array consisting of cost of toys. Given an integer K depicting the amount of money available to purchase toys. Write a program to find the maximum number of toys one can buy with the amount K.
   * Time Complexity: O(n)
   
   

   


