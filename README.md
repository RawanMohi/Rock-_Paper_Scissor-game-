# Rock, Paper & Scissor Game

This repository contains a Jupyter Notebook that implements the classic Rock, Paper, Scissor game using Python. Below is a detailed description of the code in the notebook.

## Notebook: Rock, Paper & Scissor game.ipynb

### Overview
This Jupyter Notebook allows users to play a Rock, Paper, Scissor game against the computer. The game tracks scores and determines the winner after a specified number of rounds.

### Code Breakdown

1. **Importing Libraries**
   - The `random` library is imported to allow the computer to make random choices, ensuring the unpredictability of the game.

2. **Function: get_computer_choice**
   - This function generates a random choice for the computer from the list `['rock', 'paper', 'scissors']`.
   - It uses the `random.choice` method to randomly select and return one of the three options.

3. **Function: get_winner**
   - This function determines the winner of a single round based on the classic rules of Rock, Paper, Scissor.
   - It takes two parameters: `player_choice` (the player's choice) and `computer_choice` (the computer's choice).
   - The function compares the choices and returns 'player', 'computer', or 'draw' based on the rules:
     - Rock beats Scissors
     - Scissors beat Paper
     - Paper beats Rock

4. **Function: play_game**
   - This function manages the overall game flow, including score tracking and determining the overall winner.
   - It initializes scores for the player and computer and prompts the user to enter the number of rounds to play.
   - For each round:
     - Prompts the user to enter their choice.
     - Calls `get_computer_choice` to get the computer's choice.
     - Calls `get_winner` to determine the round winner.
     - Updates scores based on the round winner.
     - Prints the round result and the current score.
   - After all rounds are played, it prints the final scores and the overall winner.

### How to Use

1. **Jupyter Notebook**:
   - Ensure you have Jupyter installed.
   - Start Jupyter by running `jupyter notebook` in your terminal.
   - Navigate to the `Rock, Paper & Scissor game.ipynb` file and open it.
   - Run all the cells in the notebook sequentially.
   - Follow the prompts to play the game.

## Example Gameplay

1. Enter the number of rounds you want to play.
2. For each round, enter your choice (rock, paper, or scissors).
3. The computer will make its choice, and the winner of the round will be displayed.
4. The scores will be updated after each round.
5. After all rounds, the final scores and the overall winner will be displayed.

## Prerequisites

- **Python**: Ensure you have Python installed on your system.
- **Jupyter Notebook**: You need Jupyter Notebook to run and interact with the `.ipynb` file.

## Installation

### Python
Install Jupyter using pip:
```bash
pip install jupyter
