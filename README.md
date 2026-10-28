# 💰 Python Tip Calculator

A simple command-line Tip Calculator built with Python. This project calculates the tip amount based on the meal cost and the tip percentage entered by the user.

## 📌 Project Overview

The Python Tip Calculator takes two inputs from the user:

* **Meal Cost:** The total cost of the meal in dollars.
* **Tip Percentage:** The percentage the user wants to leave as a tip.

It calculates the tip amount and displays the result formatted to two decimal places.

## ✨ Features

* 💵 Accepts meal costs in dollar format (e.g., `$50.00`).
* 📊 Accepts tip percentages (e.g., `15%`).
* 🧮 Calculates the tip amount automatically.
* 🔢 Converts string inputs into floating-point numbers.
* 🖥️ Displays the result with two decimal places.
* 🐍 Uses Python functions for clean and organized code.

## 🛠️ Technologies Used

* **Programming Language:** Python 3
* **Concepts:** Functions, string manipulation, type conversion, user input, arithmetic operations, and formatted output.

## 📂 Project Structure

```text
python-tip-calculator/
│
├── tip_calculator.py
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Install Python 3 on your computer.

### Installation

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

Replace `YOUR_REPOSITORY_URL` with your actual GitHub repository URL.

**2. Navigate to the project directory**

```bash
cd python-tip-calculator
```

**3. Run the program**

```bash
python tip_calculator.py
```

If your system uses the `python3` command, run:

```bash
python3 tip_calculator.py
```

## 💻 Example Usage

**Input:**

```text
How much was the meal? $50.00
What percentage would you like to tip? 15%
```

**Output:**

```text
Leave $7.50
```

### 🧮 How It Works

The program uses three functions and a simple calculation:

1. `main()` collects the meal cost and tip percentage from the user.
2. `dollars_to_float()` removes the dollar sign and converts the amount into a floating-point number.
3. `percent_to_float()` removes the percentage sign and converts the percentage into a decimal.
4. The program multiplies the meal cost by the decimal tip percentage.
5. The result is displayed with two decimal places.

**Formula:**

```text
Tip Amount = Meal Cost × (Tip Percentage / 100)
```

For example:

```text
Meal Cost = $50.00
Tip Percentage = 15%

Tip = 50.00 × 0.15
Tip = $7.50
```

## 🎯 Learning Objectives

This project helped me practise:

* Writing and calling Python functions.
* Working with strings and the `replace()` method.
* Converting strings into floating-point numbers using `float()`.
* Accepting user input with `input()`.
* Performing arithmetic calculations.
* Formatting numerical output using f-strings.

## 🔮 Future Improvements

Potential improvements for future versions include:

* Adding input validation and error handling.
* Calculating the total bill, including the tip.
* Supporting multiple currencies.
* Allowing users to split the bill among multiple people.

## 👨‍💻 Author

Created as part of my Python programming and problem-solving journey.

---

⭐ If you find this project useful, feel free to explore the code and share your feedback!

