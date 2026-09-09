# Python Programming Practice

A collection of beginner-to-intermediate Python exercises built while learning core programming concepts — data structures, control flow, and simple interactive programs.

## 📂 Contents

| File | Description |
|---|---|
| `dictionary_tasks.ipynb` | A set of exercises covering Python dictionaries — creation, key/value operations, iteration, and common dictionary methods. |
| `smart_atm.ipynb` | A simple ATM simulator that models basic banking operations (deposit, withdraw, check balance) using functions and conditionals. |
| `smart_atm_while_loop.ipynb` | A refactored version of the ATM simulator that uses a `while` loop to keep the menu running until the user chooses to exit, simulating a more realistic continuous session. |

> **Note:** The two ATM notebooks represent two stages of the same project — the first is the initial logic, and the second improves on it with a persistent loop-driven menu.

## 🎯 What This Repo Demonstrates

- Working with core Python data structures (dictionaries)
- Writing functions with clear, single responsibilities
- Using conditionals (`if`/`elif`/`else`) to handle multiple user choices
- Using `while` loops to build interactive, menu-driven programs
- Basic input validation and user interaction via `input()`

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Alimohamed2099/python-programming.git
   cd python-programming
   ```
2. Open any notebook with Jupyter:
   ```bash
   jupyter notebook
   ```
3. Run the cells in order (`Shift + Enter`) to follow the logic step by step.

**Requirements:** Python 3.x and Jupyter Notebook (`pip install notebook`).

## 🧠 Example: Smart ATM

The ATM simulator lets a user:
- Check their current balance
- Deposit money
- Withdraw money (with a check against insufficient funds)
- Exit the session

The `while`-loop version keeps this menu running in a loop until the user explicitly chooses to quit, rather than executing once and stopping.

## 📌 Roadmap

- [ ] Add input validation for non-numeric entries
- [ ] Add a simple PIN/login step to the ATM simulator
- [ ] Convert notebooks into a single `.py` script version for each project
- [ ] Add unit tests for the dictionary exercises
- [ ] Add more exercises (lists, string manipulation, file handling)

## 👤 Author

**Ali Mohamed**
Learning Python through hands-on practice — feedback and suggestions are welcome!

## 📄 License

This project is open for learning purposes. Feel free to fork and build on it.
