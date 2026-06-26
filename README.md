
# 🎯 Guess the Number Game

A simple command-line **Guess the Number Game** built with Python. The computer randomly selects a number between **1 and 100**, and the player has to guess it with the help of hints.

## 📌 Features

- Random number generation
- Unlimited guesses until the correct number is found
- Hints after every guess
  - 📉 "Lower number please!" if the guess is too high
  - 📈 "Higher number please!" if the guess is too low
- Displays the total number of attempts

## 🛠️ Technologies Used

- Python 3
- `random` module


## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Guess-The-Number.git
   ```

2. Open the project folder:
   ```bash
   cd Guess-The-Number
   ```

3. Run the program:
   ```bash
   python guess_number.py
   ```

## 💻 Sample Output

```
Guess the number: 50
Higher number please!

Guess the number: 75
Lower number please!

Guess the number: 63
Higher number please!

Guess the number: 68

🎉 You guessed the number 68 correctly in 4 attempt(s).
```

## 📖 How It Works

1. The computer generates a random number between **1 and 100**.
2. The player enters a guess.
3. The program compares the guess with the secret number.
4. The player receives a hint:
   - Guess is too high → Lower number.
   - Guess is too low → Higher number.
5. The game continues until the correct number is guessed.
6. The total number of attempts is displayed.

---

⭐ If you like this project, consider giving it a star on GitHub!
