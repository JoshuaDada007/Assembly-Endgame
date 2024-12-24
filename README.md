# Assembly EndGame 🎮

## Overview

A React-based word guessing game focused on programming concepts. Players must guess programming-related keywords while avoiding too many wrong guesses. Each incorrect guess eliminates a programming language from the display.

---

## ✨ Game Features

* 🎲 Random selection from programming keywords like "function", "variable", "array", etc.
* 🔄 Visual feedback with programming language icons that fade out with wrong guesses
* 🎯 Interactive letter buttons that change color based on guess accuracy
* 🏆 Win/lose states with game reset functionality
* 📝 Maximum 8 attempts per word

---

## 🎯 Gameplay Rules

### Getting Started
1. A random programming keyword is selected at the start of each game
2. Players click letter buttons to make guesses

### Mechanics

#### ✅ Correct Guesses
* Reveal the letter in the word
* Button turns green

#### ❌ Incorrect Guesses
* A programming language icon fades out
* Button turns red

### Game End Conditions
The game concludes when either:
* 🌟 The word is successfully guessed (Win)
* 💔 8 wrong guesses are made (Lose)
