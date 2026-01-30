# French Flashcards Application

An interactive flashcard application built with **Python** and **Tkinter** to help users learn French vocabulary efficiently.

The app displays a French word, flips the card after a short delay to reveal the English translation, and tracks your learning progress over time.

---

## Features

- Randomized French vocabulary flashcards
- Automatic card flip after a short delay
- Mark words as *known* or *unknown*
- Progress is saved between sessions
- Clean and intuitive graphical interface

---

## Application Preview

![App Preview](screenshots/screenshot.jpg)


## Technology Used

- **Python 3** – Core programming language
- **Tkinter** – Graphical user interface (GUI)
- **Pandas** – CSV data loading and persistence
- **Random** – Flashcard randomization

---

## How It Works

1. A French word is displayed on a flashcard.
2. After 3 seconds, the card flips to show the English translation.
3. Click:
   - ❌ if you don’t know the word
   - ✅ if you know the word
4. Known words are removed from the learning pool and saved automatically.

---

## How to Run

1. Clone the repository:
   ```bash
    git clone https://github.com/MichelleRunning/french-flashcards.git
    ```

2. Install dependencies:
  ```bash
  pip install pandas
  ```

3. Run the application:
```bash
  python main.py
  ```
