# RockPaperScissors-Js-only
Rock Paper Scissors Javascript Code Only 

Rock, Paper, Scissors Game

This is a simple Rock, Paper, Scissors game implemented in JavaScript. Players can choose between two modes: single-game mode and best-of-three mode. In single-game mode, the player plays a single round of Rock, Paper, Scissors against the computer. In best-of-three mode, the player and computer play multiple rounds, and the player needs to win two out of three rounds to win the game.
How to Play

    When you start the game, you will be prompted to choose a mode:
        Type 1 for single-game mode.
        Type 2 for best-of-three mode.

    In single-game mode, you will be prompted to enter your choice: "rock," "paper," or "scissors." You can also cancel the prompt to exit the game.

    In best-of-three mode, the game will continue until one side wins two rounds. The scores will be displayed after each round, and the winner will be determined at the end of the game.

    The game will display the results of each round and announce the winner.

Code Structure

The code is divided into several functions:

    getPlayerChoice: Prompts the player to choose "rock," "paper," or "scissors" and handles input validation.
    getComputerChoice: Generates a random choice for the computer.
    getWinner: Determines the winner of a single round based on the player's and computer's choices.
    singleGame: Runs a single round of the game, allowing the player to make a choice and then determining the winner.
    bestOfThree: Implements the best-of-three game mode and keeps track of the player and computer's scores.
    The game starts by asking the player to choose a mode and then calls either singleGame or bestOfThree accordingly.

Usage

To play the game, simply open the HTML file in a web browser and follow the on-screen instructions. Choose your mode and make your selections when prompted.
