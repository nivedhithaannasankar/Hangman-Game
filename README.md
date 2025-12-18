# Hangman-Game (Python)


## 📘 Overview

This project is a **console-based Hangman game** implemented in Python. The player must guess a randomly selected word letter by letter within a limited number of lives. Visual stages of the hangman are displayed after each incorrect guess, making the gameplay interactive and engaging.

---

## 🚀 Features

* 🎲 Random word selection from a predefined word list
* ❤️ Limited lives system with visual hangman stages
* 🔁 Prevents repeated letter guesses
* 🧠 Real-time word progress display using placeholders
* 🎨 ASCII art for game logo and hangman stages
* 🏁 Clear win and loss messages

---

## 🧩 Module Dependencies

* **main.py** – Contains the core game logic, handles user input, game flow, and win/loss conditions.
  **Dependencies:** `random`, `hangman_words`, `hangman_art`

* **hangman_words.py** – Stores a list of words used for random word selection.
  **Dependencies:** Used by `main.py`

* **hangman_art.py** – Contains ASCII art for the game logo and hangman stages based on remaining lives.
  **Dependencies:** Used by `main.py`

---

## 🌟 Future Enhancements

* Add difficulty levels (easy, medium, hard) with varying word lengths
* Track and display player scores across multiple games
* Allow full-word guessing along with letter guessing
* Add graphical user interface (GUI) using Tkinter or Pygame
* Improve input validation for non-alphabet characters
* Add multiplayer or timed gameplay modes

---


