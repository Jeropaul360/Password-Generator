# 🔐 Password Generator

A simple Python-based password generator that creates random passwords using uppercase letters, lowercase letters, numbers, and symbols. Customize your password by specifying how many letters, numbers, and symbols you want.

## ✨ Features

* 🔤 Generate passwords using uppercase and lowercase letters.
* 🔢 Include numbers from 0–9.
* 🔣 Add symbols for extra variety.
* 🔀 Shuffle password characters randomly.
* 📏 Customize password length and composition.
* 💪 Display a basic password-strength message based on length.
* ⚠️ Validate user input to ensure numeric values are entered.

## 🛠️ Technologies Used

* **Language:** Python
* **Module:** `random` (Python standard library)

## 📂 Project Structure

```text
Password-Generator/
│
├── main.py
└── README.md
```

## 🚀 Getting Started

### Prerequisites

* Python 3.x installed on your computer.

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Jeropaul360/Password-Generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Password-Generator
   ```

3. Run the Python program:

   ```bash
   python main.py
   ```

## 💻 How to Use

1. Run the program.
2. Enter the number of letters you want in your password.
3. Enter the number of symbols you want.
4. Enter the number of numbers you want.
5. The program generates and displays your password.
6. A basic strength message is displayed based on the password length.

### Example Output

```text
Welcome to the Password Generator!
How many letters would you like in your password?
8
How many symbols would you like?
2
How many numbers would you like?
2

Here is your password: aB7#kP2!mX5$
Your password is strong.
```

*Note: The generated password in this example is illustrative.*

## 📊 Password Strength

The program displays a basic strength message based on the total number of characters:

| Password Length       | Message |
| --------------------- | ------- |
| 6 characters or fewer | Weak    |
| 7 characters          | Medium  |
| 8 or more characters  | Strong  |

**Note:** This is a simple length-based indicator, not a comprehensive password-security assessment.

## 🎯 Project Objective

The objective of this project is to practice Python programming fundamentals, including loops, lists, conditional statements, user input, random selection, and string manipulation.

## 🔮 Future Improvements

* Use Python's `secrets` module for security-sensitive password generation.
* Add stronger password-strength validation.
* Improve input validation and error handling.
* Create a graphical user interface (GUI).
* Allow users to save generated passwords securely.

## 🎥 Live Demo

Watch the Password Generator in action!

<img width="548" height="296" alt="Image" src="https://github.com/user-attachments/assets/d34464ca-84d7-4010-b606-debe0a456e1e" />

### ✨ Demo Features

* Generate random passwords using letters, numbers, and symbols.
* Customize password composition.
* View the generated password.
* Check the basic password-strength message.

## 👨‍💻 Author

**Paul Jero**

* GitHub: [Jeropaul360](https://github.com/Jeropaul360)
* Portfolio: [View My Portfolio](https://jeropaul360.github.io/Portfolio/)

---

⭐ If you find this project useful, consider giving the repository a star!
