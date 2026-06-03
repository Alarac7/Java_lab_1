# Laboratory Work No.1: Basic Java Algorithms

## Overview
This repository contains the implementation of Laboratory Work No.1 for the Moscow Technical University of Communications and Informatics (MTUCI). 

The primary focus of this project is to master fundamental data processing algorithms in Java. The work includes a mathematical algorithm for filtering number sequences and a string manipulation utility for text analysis.

## Tasks Description

### Task 1: Prime Number Finder (Primes)
A program designed to locate and print all prime numbers less than 100.
* Mechanics: Uses a loop to iterate through numbers from 2 to 100, passing each value to a helper verification method.
* Optimization: The prime check is optimized by limiting the divisor search to the square root of the number using the condition i * i <= n. This eliminates unnecessary operations and significantly improves algorithm performance.

### Task 2: Palindrome Checker (Palindrome)
A program that determines whether a given string reads the same backward as forward.
* Input Processing: Iterates through an array of input arguments using a for-each loop to check multiple strings sequentially.
* String Reversal: Features a custom reverseString method that builds an inverted version of the text by traversing characters in reverse order.
* Verification: Features an isPalindrome method that evaluates the original string against the reversed text using the equals method to determine identity.

## Technologies Used
* Language: Java
* Core Concepts: Basic Control Structures (for loops, if-else branches), Code Decomposition, String Manipulation, Mathematical Optimization

## Key Learnings and Conclusion
This project demonstrates the practical application of basic control structures and programmatic decomposition in Java. By splitting the core logic into targeted helper methods, code readability and maintainability were improved. Additionally, implementing classic mathematical optimization boundaries highlighted the importance of algorithmic efficiency when processing numerical datasets.

---

## Author
* Name: Pavel Petrovich Koshelev
* Group: BST 2401
* Institution: MTUCI
* Year: 2026
