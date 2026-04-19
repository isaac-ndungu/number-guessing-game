# Number Guessing Game

A command-line Python game where the computer picks a random number and you try to guess it — with difficulty levels, hints, and high score saving.

## Overview

This is an interactive number guessing game built in Python. The computer secretly picks a number between 1 and 100, and the player must figure it out using process of elimination. Each wrong guess comes with a directional clue, the game tracks your remaining attempts, and a hint unlocks after a few failed tries. Results are saved to a local file so scores persist across sessions.

## How to Run

Open main.ipynb in Jupyter or VS Code and run the cells.

### Gameplay
1. Enter your username when prompted.
2. Choose a difficulty level: Easy, Medium, or Hard.
3. Guess a number between 1 and 100.
4. After each guess, you'll get feedback:
    * higher — the target is larger than your guess
    * lower — the target is smaller than your guess
5. Keep guessing until you find the number or run out of attempts

## Features
* Random number generation using random.randint(1, 100)
* Difficulty selection — Easy, Medium, or Hard
* Attempt tracking — remaining guesses displayed after each wrong answer
* Hint system — after 3 wrong guesses, you get a hint about whether the number is even or odd
* High score saving — your username, number of remaining attempts, and difficulty are saved to high_scores.txt
