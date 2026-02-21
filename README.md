# project24
🪨📄✂️ Rock Paper Scissors (Python | wxPython GUI)

A simple yet elegant Rock Paper Scissors game built using Python and wxPython, featuring a modern GUI and clean game-logic design.
This project was developed during my 1st semester as a way to explore GUI programming, threading, and efficient decision-making logic.

✨ Features

🎨 Modern dark-themed GUI using wxPython

🧵 Non-blocking gameplay using multithreading

🤖 Randomized computer (engine) moves

📜 Real-time game logs displayed in the UI

❌ Quit button for graceful exit

🧠 Optimized game logic without nested if-else statements

🧠 Game Logic (Key Highlight)

Instead of using conventional deeply nested if-else conditions to determine the winner, this project uses a logical mapping approach inspired by cross-product style relationships.

wins = {
    '1': '3',  # Rock beats Scissor
    '2': '1',  # Paper beats Rock
    '3': '2'   # Scissor beats Paper
}
Why this approach?

✔️ Eliminates complex conditional branching

✔️ Makes the logic compact, readable, and scalable

✔️ Demonstrates conceptual thinking beyond beginner-level patterns

✔️ Easy to extend or modify

This design choice reflects an early understanding of mathematical relationships and clean code principles, rather than relying on brute-force condition checks.

🖥️ Technologies Used

Python 3

wxPython – GUI framework

threading – for non-blocking UI

random – CPU move generation

time – delay simulation

🚀 How to Run

Install dependencies:

pip install wxPython

Run the game:

python rps.py
📚 What I Learned

Building desktop GUIs with wxPython

Managing UI responsiveness using threads

Writing cleaner logic using mapping instead of nested conditionals

Structuring a complete Python application

🎓 Academic Context

This project was created during my first semester as part of my learning journey in Python programming and GUI development.
