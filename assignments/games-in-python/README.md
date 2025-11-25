

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build the classic Hangman word-guessing game in Python. Practice string manipulation, loops, conditionals, and random selection while creating an interactive game.

## 📝 Tasks

### 🛠️ Hangman Game Logic

#### Description
Create a Python program that lets a player guess letters to reveal a hidden word. The game should track guesses, display progress, and end with a win or loss message.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Accept single-letter guesses from the user
- Display current progress using underscores for unguessed letters (e.g., _ a _ _ m a n)
- Track and display the number of incorrect guesses remaining
- End the game when the word is fully guessed or attempts run out
- Show a win message if the player guesses the word, or a lose message if attempts are exhausted

Example:
```
Word: _ a _ _ m a n
Guesses left: 4
Guessed letters: a, m, n, h
Enter a letter: g
...etc...
```

### 🛠️ Word List & Replay Feature

#### Description
Enhance your game by allowing replay and using a larger, more interesting word list.

#### Requirements
Completed program should:

- Use a list of at least 10 words for random selection
- Ask the player if they want to play again after each game
- Reset the game state for each new round
