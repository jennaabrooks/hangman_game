
# Hangman Game
This is a simple command-line Hangman game implemented in Python. The game randomly selects a word from a list, and the player has to guess the word letter by letter within a limited number of attempts (lives). If the player guesses all the letters correctly before running out of lives, they win! If they run out of lives before completing the word, they lose.

# How to Run
Clone the Repository or download the project files:

Install Dependencies: If you're running this game in a Jupyter Notebook or similar environment, ensure the following dependencies are installed:

- IPython.display (usually included in Jupyter environments)
- Random module (standard in Python)


Run the Game: To start the game, simply run the play_hangman() function in your Python environment.

# Files:

- `hangman_words.py`: Contains the list of words (word_list) from which the game randomly selects.
- `hangman_art.py`: Contains ASCII art for the hangman stages and the game logo.

# Game Rules
1. The computer randomly selects a word from the word list.
1. The player tries to guess the word letter by letter.
1. The player has 6 lives. Each wrong guess reduces a life.
1. If the player guesses all the letters before running out of lives, they win.
1. If the player loses all their lives, the game is over, and the correct word is revealed.
