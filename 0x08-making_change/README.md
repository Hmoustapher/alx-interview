0x08. Making Change
Description
This project involves solving a classic algorithmic problem: the coin change problem. The goal is to determine the minimum number of coins required to make up a given total amount using the denominations provided. If it's not possible to achieve the total with the given coins, the function should return -1.

You will need to apply concepts of greedy algorithms and dynamic programming to implement an efficient solution.

Learning Objectives
By completing this project, you will learn to:

Apply greedy algorithms and understand their limitations.
Implement dynamic programming solutions for optimization problems.
Analyze the time and space complexity of your algorithms.
Utilize Python effectively for problem-solving with lists, loops, and conditional logic.
Project Requirements
All files should be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3.
All files should end with a new line.
The first line of all Python files should be #!/usr/bin/python3.
Your code should follow PEP 8 style guidelines.
A README.md file is mandatory in the project directory.
Files
0-making_change.py
This module contains the main function, makeChange(coins, total), which computes the fewest number of coins required to meet a given total.

Function Prototype
python
Copy code
def makeChange(coins, total):
    """
    Determines the fewest number of coins needed to meet a given total.

    Args:
        coins (list): List of coin denominations.
        total (int): The target total amount.

    Returns:
        int: Fewest number of coins needed, or -1 if the total cannot be met.
    """
0-main.py
This file contains test cases for the makeChange function to ensure it works as expected.

Usage
Clone the repository:
bash
Copy code
git clone https://github.com/<your-username>/alx-interview.git
Navigate to the project directory:
bash
Copy code
cd alx-interview/0x08-making_change
Run the test file:
bash
Copy code
./0-main.py
Example Output
bash
Copy code
$ ./0-main.py
7
-1
Concepts Covered
Greedy Algorithms:

Using the largest denominations first.
Understanding when a greedy approach works and its limitations.
Dynamic Programming:

Breaking the problem into smaller sub-problems.
Ensuring optimal solutions through recursion or iteration.
Algorithmic Complexity:

Optimizing runtime and memory usage.
References
GeeksforGeeks - Greedy Algorithm for Minimum Coins
Dynamic Programming - Coin Change Problem
Python Official Documentation
Author
This project is part of the ALX Interview Preparation program.
