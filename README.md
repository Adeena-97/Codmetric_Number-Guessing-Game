# 🎯 Number Guessing Game – C++ Console Application

A beginner-level console-based game developed in C++ as part of an internship task at **Codmetric**. The game challenges users to guess a randomly generated number between 1 and 100 with real-time feedback.

## 🕹️ Game Summary

- System randomly picks a number between **1 and 100**
- User guesses the number until it’s correct
- Real-time feedback:
  - “Too high” or “Too low”
- Tracks and displays number of attempts
- Ends with a success message and stats

## 💡 Features

- Random number generation using `rand()` and `time(0)`
- Input validation using `cin.fail()` and `cin.clear()`
- Clean command-line interface
- Tracks user attempts
- Easy to extend with difficulty levels or scoreboards

## 🛠 Tech Stack

- **Language:** C++
- **Concepts Used:** Loops, Conditionals, Random number generation, Input validation

## 📂 File

- `guessing_game.txt`: Full source code of the game

## 🧾 Project Context

This project was developed as an **internship task** at **Codmetric** to demonstrate understanding of basic control structures, user input handling, and logic building in C++.

## 🖥️ Gameplay Preview

```txt
=== Number Guessing Game ===
I have picked a number between 1 and 100.
Can you guess it?

Enter your guess: 40
Too low! Try a higher number.
Attempts so far: 1

Enter your guess: 75
Too high! Try a lower number.
Attempts so far: 2

Enter your guess: 63
Congratulations! You guessed it right!
The number was: 63
You took 3 attempts.

Thanks for playing!
