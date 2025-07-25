# Day1-of-43-of-Teachersdaychallenge
1. Two Sum
Problem Description: Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

Approaches Discussed:

Brute Force (O(n 
2
 ) Time Complexity): Iterates through all possible pairs. Simple to understand but inefficient for large inputs.

Hash Map / Dictionary (O(n) Time Complexity): Leverages a hash map to store numbers and their indices, allowing for efficient lookups of the complement in a single pass. This is the optimal solution.

Key Learning Points:

Importance of choosing the right data structure (hash maps for quick lookups).

Optimizing from quadratic to linear time complexity.



Example (from LeetCode):
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

2. Remove Linked List Elements
Problem Description: Given the head of a linked list and an integer val, remove all the nodes of the linked list that has Node.val == val, and return the new head.

Approaches Discussed:

Iterative Approach with Dummy Node: The most robust way to handle this. A dummy node simplifies edge cases like removing the head of the list or consecutive matching values.

Key Learning Points:

Mastering pointer manipulation in linked lists.

Effective use of a "dummy" or "sentinel" node to simplify logic and avoid null pointer exceptions, especially when modifying the head.

Handling consecutive deletions.
