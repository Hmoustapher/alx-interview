0x0A. Prime Game
Project Overview
The Prime Game is a competitive game where two players, Maria and Ben, take turns choosing prime numbers from a set of consecutive integers starting from 1 up to and including n. For each chosen prime number, the player removes the prime and all its multiples from the set. The player who cannot make a move loses the game. This game is played over x rounds, where the value of n may differ for each round.

In this project, you are tasked with determining the winner of multiple rounds of the game, assuming both players play optimally.

Goal
Your goal is to create a function isWinner(x, nums) that calculates the player who wins the most rounds of the game, based on the value of n in each round. Maria always goes first.

Concepts Covered
Prime Numbers: Understanding prime numbers and identifying them efficiently using algorithms.
Game Theory: Strategy for optimal play in competitive games.
Algorithm Optimization: Efficiently handling prime number removal and game state management.
Dynamic Programming/Memoization: Using previous results to speed up future calculations.
Python Programming: Implementing loops, conditionals, and lists for algorithmic solutions.
Requirements
Allowed editors: vi, vim, emacs
Interpreter: All files should be interpreted or compiled on Ubuntu 20.04 LTS using Python 3 (version 3.4.3).
PEP 8: Your code should follow PEP 8 style guidelines (version 1.7.x).
File Format: All files must end with a newline and have the following shebang at the top: #!/usr/bin/python3.
Executable: All your Python files must be executable.
Project Structure
Directory: 0x0A-primegame
Main File: main_0.py (entry point for testing)
Implementation File: 0-prime_game.py (your solution for the Prime Game)
Tests: None provided, but you can use the example and implement additional test cases.
Task Description
0. Prime Game (mandatory)
Maria and Ben are playing a game with consecutive integers from 1 to n. In each round:

Maria and Ben take turns picking a prime number from the set.
After a number is picked, it and its multiples are removed from the set.
The player who cannot make a move loses the round.
You are asked to:

Implement a function isWinner(x, nums) where:
x is the number of rounds played.
nums is an array containing the value of n for each round.
Return the name of the player who won the most rounds, or None if there’s a tie.
Example:
python
Copy code
x = 3
nums = [4, 5, 1]
isWinner(x, nums)
Game Breakdown:

Round 1 (n=4):

Maria picks 2, removing [2, 4], leaving [1, 3].
Ben picks 3, removing [3], leaving [1].
Ben wins because Maria cannot pick a prime number.
Round 2 (n=5):

Maria picks 2, removing [2, 4], leaving [1, 3, 5].
Ben picks 3, removing [3], leaving [1, 5].
Maria picks 5, removing [5], leaving [1].
Maria wins because Ben cannot pick a prime number.
Round 3 (n=1):

Ben wins because Maria cannot pick any prime numbers.
Result: Ben wins 2 rounds, Maria wins 1 round. So, the output should be:

text
Copy code
Winner: Ben
Function Prototype
python
Copy code
def isWinner(x, nums):
    pass
Resources
To better understand the concepts necessary to solve this problem, you can explore the following resources:

Prime Numbers - Khan Academy
Sieve of Eratosthenes in Python
Game Theory Basics
Dynamic Programming with Python Examples
Python Lists
Setup
1. Clone the Repository
To get started, clone the project repository:

bash
Copy code
git clone https://github.com/your-username/alx-interview.git
cd alx-interview/0x0A-primegame
2. Running the Project
To run the project, you can execute the main test file:

bash
Copy code
./main_0.py
3. Testing
You can modify the values of x and nums in main_0.py to test different scenarios for the Prime Game.

License
This project is licensed under the MIT License - see the LICENSE file for details.
