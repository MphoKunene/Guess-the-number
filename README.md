# Guess-the-number
Write a programme where the computer randomly generates a number between 0 and 20. The user needs to guess what the number is.

#will be using data produced from the random function
import random

#generates random numbers between 0 and 20
randNumbers = random.randrange(0, 20)
print(randNumbers)

#takes in user input
numbers = int(input("Guess a number "))


#checks if randNumbers is equal to numbers then prints the output
if randNumbers == numbers:
    print("You guessed right!!!")
else:
    print("Your guess was incorrect!")

