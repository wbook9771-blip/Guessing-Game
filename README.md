import random

# Secret number generate karna (1 se 100 ke beech)
secret_number = random.randint(1, 100)

print("--- Guessing Game in Python ---")
print("I have chosen a number between 1 and 100. Can you guess it?")

while True:
    guess = int(input("Enter your guess: "))
    
    if guess == secret_number:
        print("🎯 Congratulations! You guessed the correct number!")
        break
    elif guess > secret_number:
        print("📉 Too High! Try a lower number.")
    else:
        print("📈 Too Low! Try a higher number.")

    Project Name: Guessing Game
Language: Python
Description: A simple console-based number guessing game.
How to run: Run the script in a Python environment and input your guesses.
