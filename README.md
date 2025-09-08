# Python-mini-project6-WPM-words-per-minute-
A terminal-based Speed Typing Test built with Python and the curses library. 
# ⌨️ Speed Typing Test (WPM)

This project measures your typing speed in **Words Per Minute (WPM)** and highlights mistakes in real time.  
The sentences are customized to reflect my journey as a student and programmer.

---

## 📌 Features
- Welcome screen before starting
- Random text loaded from `text.txt`
- Real-time WPM calculation
- Correct characters shown in **green**
- Incorrect characters shown in **red**
- Option to **play again** or **quit (q / Esc)**

---

## 📂 Project Files
- `wpm.py` → Main program  
- `text.txt` → Typing text (customized for Sam’s journey)  

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/wpm-typing-test.git
   cd wpm-typing-test
Make sure you have Python 3.x installed.

Run the program:

bash
Copy code
python wpm.py
📐 WPM Formula
ini
Copy code
WPM = (characters typed / 5) / (time in minutes)
👉 Assumes 1 word = 5 characters.

🎮 Example Gameplay
pgsql
Copy code
Welcome to the Speed Typing Test!
Press any key to begin!

Hello world, my name is Sam and I am a student as well as a programmer.
WPM: 37

You completed the text! Press any key to play again, or 'q' to quit.
