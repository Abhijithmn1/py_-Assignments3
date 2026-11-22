Python Assignment 3: While Loop, For Loop, and Functions

This repository contains simple Python programs covering loops, loop control statements, and user-defined functions.

📋 What Was Done

1. Number Guessing Game (while Loop & Control Statements)

   ​Generate a secret number: Use Python's random module to pick a secret number between 1 and 10.
  ​Set up the loop: Create a while loop that gives the user three valid attempts to guess the number.
  ​Validate input with continue: If the user enters a number outside the 1–10 range, use continue to skip the rest of the loop body so they don't lose an attempt.
  ​Handle a win with break: If the user guesses the correct number, congratulate them and use break to immediately exit the loop.
  ​Handle a loss with else: Attach an else block to the while loop that runs only when all three attempts are used without hitting break, displaying a message like "Better luck next time."

2. Multiplication Table Generator (for Loop)

   Get user input: Prompt the user to enter a number and convert it to an integer.
  Create a for loop: Iterate through range(1, 11) to cover numbers from 1 to 10.
  Filter for even numbers: Check if the current iteration number is even (e.g., i % 2 == 0).
  Multiply and print: Multiply the user's number by the even iteration number and print the output formatted as number * iteration = result.

3. BMI Calculator (Functions)Custom Function: Defined calculate_bmi(weight, height) to calculate Body Mass Index using the formula:
BMI = (WEIGHT (KG) / HEIGHT (M))
User Input & Output: Took the user's weight and height, passed them into the function, and displayed the final BMI rounded to 2 decimal places.

