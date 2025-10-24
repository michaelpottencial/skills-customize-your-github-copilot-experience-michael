
# 🎮 Hangman Game Challenge

## 🎯 Objective

Build a playable command-line Hangman game to practice Python strings, loops, conditional logic, user input, and basic program structure.

## 📝 Tasks

### 🛠️ Implement the Hangman core

#### Description
Create a command-line program (suggested filename: `hangman.py`) that runs a full game loop: choose a secret word, accept letter guesses from the player, reveal correct letters, and track remaining attempts. 

#### Requirements
Completed program should:

- Randomly select a secret word from a predefined list (in-code list or a `words.txt` file).
- Display the current progress using underscores for unknown letters and the revealed letters for correct guesses (e.g., `_ a _ _ m a n`).
- Accept single-letter guesses (case-insensitive) and update the display when guesses are correct.
- Track incorrect guesses and remaining attempts (configurable, e.g., 6 attempts).
- Prevent duplicate penalties when the player repeats a previously guessed letter.
- End the game when the player guesses the full word (win) or uses all attempts (lose), and display an appropriate message including the secret word.
- Use clear, user-friendly prompts and messages.

Example interaction (example lines shown for clarity):
```text
Secret word: python
_ _ _ _ _ _    Attempts left: 6
Guess a letter: p
p _ _ _ _ _    Attempts left: 6
Guess a letter: x
p _ _ _ _ _    Attempts left: 5  (incorrect)
...
Congratulations — you guessed the word: python
```

---

### 🛠️ Optional extras (extra credit)

#### Description
Add one or more user-facing improvements to make the game more engaging or robust.

#### Examples / Requirements (optional)

- Add ASCII-art for the hangman state that updates with each incorrect guess.
- Provide difficulty levels that change the word list or number of attempts.
- Allow guessing the full word at once.
- Persist a high-score or win/loss record across runs.

---

### Submission notes

- Submit a Python script (suggested `hangman.py`) that implements the game and includes a `if __name__ == "__main__":` entry point for running the game.
- If you store words in a separate file, include that file (e.g., `words.txt`) and document its location in a comment at the top of `hangman.py`.
- Keep the program CLI-only and avoid external dependencies so it is easy to run with `python3 hangman.py`.
- Keep the code small and well-commented; include a short usage example in the file header or this README.

