# Python Number Guessing Game

## Description
This Python program is a simple number guessing game where the player tries to guess a randomly selected number within a specified range (1 to 100 by default). After each guess, the program provides feedback to help the player zero in on the correct answer, indicating whether the guess was "Too low" or "Too high." The game continues until the player guesses the correct number, at which point the program displays the total number of guesses.

## Features
- Randomly generates a target number between the specified lowest and highest values.
- Accepts only numeric inputs and checks if they are within the specified range.
- Provides feedback on whether the guess is too high or too low.
- Counts the total number of guesses and displays it upon successful completion.
- Validates the user's input to ensure it is a digit within the range.

## How to Use
1. **Clone or download this repository** to your local machine.
2. **Run the program** in a Python environment.
3. The program will display the following:
   - The number range in which to guess.
   - A prompt for the user to input a guess.
4. **Follow the instructions**:
   - Enter a number between the specified range.
   - If the guess is correct, the program will congratulate the player and display the total number of guesses.
   - If the guess is incorrect, the program will indicate if the guess was too high or too low.
   - If the input is invalid (not a number or out of range), the program will prompt the user to enter a valid number.

## Example Usage
```bash
Python Number Guessing Game
Select a number between 1 & 100
Enter your guess: 50
Too low! Try Again!
Enter your guess: 75
Too high! Try Again!
Enter your guess: 62
CORRECT!! The answer was 62
Number of guesses: 3
