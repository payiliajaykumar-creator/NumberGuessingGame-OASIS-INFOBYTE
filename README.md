# 🎯 Number Guessing Game (Java)

## 📌 Project Overview

The **Number Guessing Game** is a simple, interactive console-based application developed using Java. The computer generates a random number between 1 and 100, and the player must guess the correct number within a limited number of attempts.

This project was developed as part of the **OASIS INFOBYTE Java Development Internship**.

## ✨ Features

- 🎲 Random number generation between 1 and 100
- 💡 Hints to help the player guess higher or lower
- 🔢 Limited attempts to make the game challenging
- 🏆 Displays a success message when the correct number is guessed
- ❌ Reveals the correct number when the player runs out of attempts
- 🔁 Option to play again
- ⌨️ Input validation for invalid entries

## 🛠️ Technologies Used

- **Programming Language:** Java
- **Concepts:** Loops, conditional statements, methods, exception-free input validation, and random number generation
- **Libraries:** `java.util.Scanner`, `java.util.Random`
- **IDE:** Eclipse IDE

## ⚙️ How to Run the Project

### Prerequisites

- Java Development Kit (JDK 21 or compatible version)
- Eclipse IDE or another Java-compatible IDE

### Steps

1. Clone or download this repository.
2. Open Eclipse IDE.
3. Import the Java source file into a Java project.
4. Ensure the source file is in the `byted` package, matching its package declaration.
5. Run `NumberGuessingGame.java` as a Java Application.
6. Follow the instructions displayed in the console.

## 🎮 How to Play

1. Start the program.
2. Enter an integer between 1 and 100.
3. Read the hint:
   - **Too low:** Guess a higher number.
   - **Too high:** Guess a lower number.
4. Guess correctly within the allowed seven attempts to win.
5. Choose `yes` when prompted to play another round.

## 💻 Sample Output

```text
=== Number Guessing Game ===
Guess a number between 1 and 100.
You have 7 attempts.

Attempt 1: 40
Too low! Try a higher number.
Attempts remaining: 6

Attempt 2: 65
Too high! Try a lower number.

Attempt 3: 52
Congratulations! You guessed correctly.

Play again? (yes/no): no
Thanks for playing!
```

*Note: The number and hints shown above are examples. Each game generates a new random number.*

## 📚 Learning Outcomes

- Understanding Java's `Random` and `Scanner` classes
- Applying loops and conditional statements
- Validating user input
- Developing interactive console applications
- Practicing basic programming logic and problem-solving

## 👨‍💻 Author

**Ajay Kumar**

Java Development Intern — OASIS INFOBYTE

## 📄 License

This project was developed for educational and internship purposes.
