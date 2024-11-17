## Dice Game 🥳🎲


# Overview

This is a simple Python-based dice rolling game that lets you roll one or two dice based on user input. The game is interactive and continues running until the user decides to quit. It keeps track of the total number of rolls made during the session.


# Features:

- Roll the Dice: Prompts the user to roll dice and displays the result of each roll.
- Rolling Options: User can choose to roll either one or two dice.
- Track Rolls: Keeps a count of the number of rolls made during the game.
- Exit Option: Allows the user to quit the game anytime.


# How to Play

1. The game will ask if you want to roll the dice. Enter y for yes or n for no.
- If you choose y, you'll be prompted to enter the number of dice you want to roll (1 or 2).
- If you choose n, the game will display the total number of rolls and end with a thank-you message.
- If you enter anything else, the game will inform you that your input is invalid.
2. For each roll, the game will generate a random number between 1 and 6 (inclusive) for each die.
3. The game continues until you decide to quit by entering n.


# Code Explanation

Part 1: Basic Dice Rolling
The first part of the code implements a simple dice rolling mechanism using the Python random module. The user is prompted to roll the dice, and if they choose 'y', two random numbers (representing two dice) are printed. If they choose 'n', the game ends. Any other input is considered invalid.

Part 2: Enhanced Game with Roll Count and Multiple Dice
In this section, a roll counter is added, and users can choose to roll either one or two dice. The game tracks the total number of rolls and displays it when the user decides to quit.


## How to Run

# Requirements

Python 3.x


# Running the Game

1. Clone the repository:
   git clone https://github.com/docmischa990/Dice.git
2. Navigate to the project directory:
   cd Dice
3. Run the script:
   python3 Dice.ipynb


# Sample Output
Roll the dice? (y/n): y
How many dice would you like to roll? (1 or 2): 2
You rolled: (4, 3)

Roll the dice? (y/n): y
How many dice would you like to roll? (1 or 2): 1
You rolled: (6)

Roll the dice? (y/n): n
Thanks for playing! You rolled the dice 3 times.


# Future Enhancements

- Add support for rolling more than two dice.
- Implement a graphical interface using tkinter or PyQt.
- Allow users to save their scores.


# Author

Mischa Doctor
GitHub: docmischa990
