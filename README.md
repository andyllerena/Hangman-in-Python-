# Hangman Game

This is a simple Hangman game implemented in Python. In this game, the player has to guess a word by suggesting letters within a certain number of guesses.

## How to Play

1. Run the game by executing the `main.py` file.
2. You will be shown a series of underscores representing the letters in the word to be guessed.
3. Enter a letter to guess. If the letter is correct, it will be revealed in the word. If not, you will lose a life.
4. Continue guessing letters until you either guess the word correctly or run out of lives.

## Game Features

- The game uses a predefined list of words from `hangman_words.py`.
- ASCII art representing the Hangman figure is displayed as you make incorrect guesses, showing the progress of the game.

## Files

- `hangman.py`: The main game file.
- `hangman_art.py`: Contains ASCII art for the Hangman figure.
- `hangman_words.py`: Contains the list of words to be used in the game.
