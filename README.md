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

PsuedoCode:

SET mystNumb TO 3
SEND 'Enter you guess' TO DISPLAY
RECEIVE guess FROM KEYBOARD

if guess > 10:
  SEND 'You guessed too high'
elif guess = mystNumb
  SEND 'You guessed correctly'
else:
  SEND 'Wrong, correct answer was ' + mystNumb
  
