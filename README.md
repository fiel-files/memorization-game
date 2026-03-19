# 🧠 Memorization Trainer

A modern **memory training web app** that helps users improve recall by typing or speaking from memory. Built with **Next.js, React, and Web Speech API**, this app simulates real memorization practice with accuracy scoring and interactive feedback.

---

## ✨ Features

* 📝 **Custom Paragraph Input**
  Paste any text you want to memorize.

* 👀 **Preview Mode (Countdown)**
  Study the paragraph before it disappears.

* ✍️ **Typing Recall**
  Type what you remember with real-time feedback.

* 🎤 **Speech Recognition**
  Speak instead of typing using browser speech-to-text.

* 🔒 **Strict Mode**
  Prevents incorrect words while typing.

* 📊 **Accuracy Scoring**
  Calculates how accurate your recall is.

* 📈 **Progress Indicator**
  Visual progress bar while typing.

---

## 🧠 How It Works

### 1. Setup

* User inputs a paragraph.
* Optionally enables **Strict Mode**.

### 2. Preview

* Paragraph is shown for a few seconds.
* Countdown prepares the user for recall.

### 3. Recall (Typing / Speaking)

* User types or speaks from memory.
* Words are checked in real-time.

### 4. Result

* Accuracy is calculated based on correct words.
* User can restart and try again.

---

## 📊 Accuracy Logic

Accuracy is calculated using:

```
Accuracy = (Correct Words in Correct Position / Total Words) × 100
```

* Words are **cleaned** (lowercase, no punctuation).
* Matching is **position-based**.
* Extra words are ignored.
* Missing or incorrect words reduce the score.

---

## 🚀 Planned Improvements

### 🔤 Smarter Accuracy

* Typo tolerance (Levenshtein distance)
* Partial scoring per word
* Phrase-based matching

### 🔄 Learning Enhancements

* Spaced repetition system
* Memory strength feedback
* Mistake tracking

### 🎮 Gamification

* Difficulty levels (Easy / Medium / Hard)
* Speed-based scoring
* Streaks and XP system

### 🎤 Speech Improvements

* Better speech-to-text accuracy
* Phonetic matching

---

## 🛠️ Tech Stack

* ⚛️ React / Next.js
* 🎨 Tailwind CSS
* 🎤 Web Speech API
* 🧠 Custom Hooks (Speech Recognition)

---

## 📦 Installation

```bash
npm install
npm run dev
```

---

## ⚠️ Notes

* Speech recognition works best in **Chrome-based browsers**.
* Some browsers may not support the Web Speech API.
* Minor vulnerabilities from npm are normal — run:

```bash
npm audit fix
```

---

## 💡 Future Vision

This project aims to evolve into a **full learning system**, similar to:

* 🧠 Spaced repetition apps (like Anki)
* 📚 Study tools for students
* 🎯 Memory training platforms

---

## 👤 Author

Developed by **Janna Fiel de Guzman**

---

## ⭐ Contribute

Feel free to fork, improve, and suggest features!
