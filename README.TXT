# Hangman Game with Tkinter UI

## Project Description
This project is a graphical implementation of the classic Hangman game using Python and the Tkinter library. The game allows players to guess a randomly chosen word by suggesting letters, with the aim to complete the word before running out of attempts. Incorrect guesses result in a Hangman figure being drawn progressively.

## Features
- **Interactive User Interface**: A clean and intuitive GUI created with Tkinter, including input fields and display labels.
- **Dynamic Hangman Animation**: The canvas displays a Hangman drawing that updates with each incorrect guess.
- **Word Selection**: A random word is selected from a predefined list, ensuring a fresh experience each time.
- **Error Handling**: Invalid or repeated inputs are handled gracefully, with appropriate user feedback.

## How to Play
1. The game starts with a hidden word displayed as dashes.
2. The player guesses letters by typing them into the input field and clicking the "Guess" button.
3. Correct guesses reveal the letter in the word, while incorrect guesses result in a part of the Hangman being drawn.
4. The game continues until the player either guesses the entire word or the Hangman drawing is completed.

## Installation and Setup
1. **Clone the repository**:

## Requirements
- Python 3.x
- Tkinter (usually included with Python installations)

## Files
- `hangman.py`: The main script containing the game logic and UI implementation.
- `words.py`: A module containing a list of words used in the game.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Special thanks to the contributors of the Python and Tkinter communities for their invaluable resources and support.

