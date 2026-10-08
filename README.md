# Hangman Game

A simple terminal-based Hangman game built in Python. The player tries to guess a hidden word letter by letter, with a limited number of incorrect guesses before the game ends.

## Project Overview

This project is a beginner-friendly Python game designed to practice core programming concepts such as:

- Variables and data storage
- Lists and loops
- Conditional logic
- User input handling
- Random selection
- Basic game flow control

The game chooses one random word from a predefined list and displays underscores for unguessed letters. The player must guess letters one at a time until they either solve the word or run out of allowed wrong attempts.

## How the Game Works

1. A random word is chosen from the list of predefined words.
2. The word is displayed as underscores, such as `_ _ _ _ _`.
3. The player enters one letter at a time.
4. If the letter is in the word, it is revealed in the correct position.
5. If the letter is not in the word, the count of wrong guesses increases.
6. The player wins if they guess the full word before using all allowed attempts.
7. The player loses if they reach the maximum number of wrong guesses.

## Features

- Random word selection
- Limited number of incorrect guesses
- Letter tracking to prevent repeated guesses
- Real-time display of the current progress
- Win/loss messages at the end of the game

## Rules

- You may only guess one letter at a time.
- Repeating a guessed letter is not allowed.
- You have 6 incorrect guesses before the game ends.
- The game ends when the word is fully guessed or the maximum mistakes are reached.

## Project Files

- `Hangman.py` - Main game logic
- `README.md` - Project documentation

## How to Run

Open a terminal in the project folder and run:

```bash
python Hangman.py
```

## Example Gameplay

```text
Welcome to Hangman!
Guess the word one letter at a time.
You have 6 incorrect guesses.

Word: _ _ _ _ _
Enter a letter: p
Correct guess!
```

## Technologies Used

- Python 3
- Standard Python libraries only

## Future Improvements

This project could be expanded with features such as:

- A larger word list
- Difficulty levels
- Hangman ASCII art
- Score tracking
- Replay option
- Multiplayer or timed mode

## Conclusion

This Hangman game is a great beginner Python project that demonstrates how simple games can be created using basic logic and user interaction. It is easy to understand, easy to run, and a solid foundation for building more advanced games later.
