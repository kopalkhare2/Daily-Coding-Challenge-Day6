# Daily-Coding-Challenge-Day6

Welcome to Day 6 of my 50-day coding challenge! Today, I solved two LeetCode problems focused on **math** and **linked lists**. This repo contains clean, optimized Python solutions with explained approaches.


##  Problem 1: [202. Happy Number]

**Difficulty:** Easy  
**Tags:** Math, Hash Table

### Problem Statement:
A happy number is a number where the process of replacing the number with the sum of the squares of its digits eventually leads to 1. If it loops endlessly in a cycle that doesn’t include 1, it’s not a happy number.

###  Approach:
- Track cycles using a set or known unhappy cycle.
- Sum squares of digits using list comprehension.

## Problem 2: [203. Remove Linked List Elements]
**Difficulty:** Easy
**Tags:** Linked List, Recursion

### Problem Statement:
Remove all nodes from a linked list that have a specific value.

### Approach:
  -	Use a Node node to simplify edge cases.
	-	Traverse the list and unlink nodes matching the target value.
	-	Return the modified list starting at Node.next.


