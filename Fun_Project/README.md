Dice Simulator (Python)

A simple Python-based dice simulator that generates random numbers between 1 and 6, mimicking a real dice roll. This is a beginner-friendly project demonstrating the use of loops, user input, and random number generation in Python.

📌 Features
Simulates rolling a dice 🎲
Generates a random number between 1 and 6
Allows multiple rolls in a loop
User-friendly console interaction
Option to exit anytime
🛠️ Technologies Used
Python
Built-in random module
📂 Project Structure
fun_project.ipynb   # Jupyter Notebook containing the code
README.md           # Project documentation
▶️ How to Run
Make sure Python is installed on your system.
Run the script in a Python environment or Jupyter Notebook.
Execute the program.
💻 Sample Code
import random

print("Welcome to the Dice Simulator!")

while True:
    input("Press Enter to roll the dice...")
    print("You rolled:", random.randint(1, 6))

    again = input("Roll again? (y/n): ")
    if again.lower() != "y":
        print("Goodbye!")
        break
🚀 How It Works
The program uses random.randint(1, 6) to generate dice values.
A while loop keeps the game running.
User input controls whether to continue or stop.
📖 Learning Outcomes

This project helps you understand:

Loops (while)
Conditional statements (if)
User input handling
Random number generation
📌 Future Improvements
Add graphical interface (GUI)
Simulate multiple dice rolls
Track roll history
Add sound effects 🎵
👩‍💻 Author

Siri Varshitha
