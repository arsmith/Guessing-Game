# Guessing-Game
Python:

import random
correct_answer = random.randint(1, 10)
guess = input("Please input a random integer between 1 and 10 ")
guess = int(guess)
if guess > 10:
  print("Your guess is too high")
if guess == correct_answer:
  print("Correct!")
else:
  print(f"The correct answer was {correct_answer}")
