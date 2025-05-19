# Hangman Game in Python

A classic Hangman game implemented in Python, where players guess letters to uncover a hidden word before running out of lives.

## Features

- Random word selection from a custom word list
- Visual hangman display that updates with each wrong guess
- Input validation for letters only (no numbers/symbols)
- Case-insensitive gameplay (accepts both upper/lowercase)
- Tracks used letters to prevent duplicate guesses
- 7 lives system with visual feedback

## How to Play

1. Run the Python script (`hangman.py`)
2. You'll see dashes representing the letters of the hidden word
3. Guess one letter at a time
4. Correct guesses reveal the letter's position(s) in the word
5. Wrong guesses reduce your remaining lives and progress the hangman drawing
6. Win by guessing all letters before running out of lives

## Files

- `hangman.py`: Main game logic
- `words.py`: Contains the word list for the game
- `hangman_visual_dict.py`: Stores the ASCII art for the hangman visuals

## Requirements

- Python 3.x
- No external dependencies (uses only built-in modules: `random`, `string`)

## Installation & Usage

1. Clone the repository or download the files
2. Ensure all files are in the same directory
3. Run the game:
   ```bash
   python hangman.py


Example of the game

   You have 7 lives left and you have used these letters: 
  _______
  |     
  |     
  |     
  |     
  |     
__|__
Current word:  - - - - -

Guess a letter: e
...

[Game continues until win/loss]
