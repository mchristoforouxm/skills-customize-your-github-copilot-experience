
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic word-guessing game using Python strings, loops, and user input. Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Initialize the game by setting up the word list and randomly selecting a word for the player to guess.

#### Requirements
Completed program should:

- Load or define a list of words to choose from
- Randomly select a word from the list
- Initialize game state variables (attempts remaining, guessed letters, word progress)


### 🛠️ Player Input and Guessing

#### Description
Accept letter guesses from the player and validate the input, updating the game state accordingly.

#### Requirements
Completed program should:

- Prompt the player to guess a letter
- Validate that the input is a single letter
- Track guessed letters to prevent duplicate guesses
- Update the word progress display (_ _ _ format)
- Decrease remaining attempts for incorrect guesses


### 🛠️ Game Logic and Win/Lose Conditions

#### Description
Implement the core game loop that checks win/lose conditions and manages game flow.

#### Requirements
Completed program should:

- Display the current word progress after each guess
- Show the number of incorrect guesses remaining
- Detect when the word is completely guessed (win condition)
- End the game when attempts are exhausted (lose condition)
- Display appropriate win/lose messages
- Allow the player to play again or quit
