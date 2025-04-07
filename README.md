# 🕹️ Assembly: Endgame

> _"Guess the word... or the world falls to Assembly!"_  
A word-guessing game where every wrong guess wipes out a programming language. Save your favorite languages and defeat the Assembly takeover!

---

## ✨ Features

- 🔠 **Word Guessing Logic** — A classic Hangman-style word game with a tech twist.
- 💻 **Programming Languages as Lives** — Each incorrect guess eliminates a programming language!
- 🎉 **Win Celebrations** — Confetti flies when you win.
- 😭 **Game Over Screens** — Dramatic endings when you lose.
- 🌐 **Farewell Messages** — Each eliminated language says goodbye in its own style.
- ♿ **Accessibility Friendly** — Uses ARIA labels and polite screen reader notifications.
- 🔄 **Replayability** — Easily start a new game and try again.

---

## 🧠 How It Works

- You start with 8 lives (represented by popular programming languages).
- Guess letters to figure out the hidden word.
- Each incorrect letter costs one language.
- Guess the word before all languages are lost... or face **Assembly**!

---

## 🛠️ Tech Stack

- ⚛️ **React** – Component-based UI and state management.
- 🎨 **clsx** – For dynamic className composition.
- 📦 **React Confetti** – To celebrate your glorious wins!
- 🧠 **Custom Utility Functions** – For random word selection and dynamic farewell messages.
- 🧪 **Vanilla CSS** – Simple but expressive styling.

---

## 🔍 Game Logic Summary

- `currentWord` is randomly selected at the start.
- `guessedLetters` tracks the player’s inputs.
- The game checks:
  - ✅ Win: All letters guessed.
  - ❌ Loss: 8 wrong guesses = game over.
- On each letter click:
  - Correct guesses reveal letters.
  - Incorrect guesses remove a language chip.
- UI updates dynamically based on game state.

---

## 👨‍🏫 Acknowledgements

📚 This project was built as part of the **Scrimba Frontend Developer Career Path**.  
A big thank you to the Scrimba team for providing such an engaging, hands-on way to learn React and game logic! 🙌

---

## 🚀 Getting Started

Wanna run it locally?

1. Clone this repo  
2. Run `npm install`  
3. Start the app with `npm run dev` or `npm start`  
4. Enjoy saving the programming world 😎
