# Python Guesss the Number

<img class="fragment" src="../images/Python-logo.png" width="400" height="400">



## Guessing Game

Write a program that selects a random number between 1 and 100 and asks the user to guess the number. Provide feedback if the guess is too high or too low.  <!-- .element: class="fragment" data-fragment-index="1" -->


example:
```python
## pick a random number to guess

##print("the number is", number) as a test.

## ask the player to guess a number

## compare the guessed number to the number.
    
# if the guessed number is too low, inform the user and ask for another guess.

# if the guessed number is too high, inform the user and ask for another guess.

# end the game when the user guesses the number.
```

NOTE:
```
## pick a random number to guess

import random

the_number = random.randint(1,100)

##print("the number is", number) as a test.

print("The number is:", the_number)

## ask the player to guess a number

guessed_number = input("Try to guess the number between 1, and 100: ")
guessed_number = int(guessed_number)

## compare the guessed number to the number.

while the_number != guessed_number:
    
# if the guessed number is too low, inform the user and ask for another guess.
    if guessed_number < the_number:
        guessed_number = input("Too low, guess again!")
        guessed_number = int(guessed_number)
# if the guessed number is too high, inform the user and ask for another guess.
    elif guessed_number > the_number:
        guessed_number = input("Too high, guess again!")
        guessed_number = int(guessed_number)

## end the game when the user guesses the number.
print("Congratulations, you guessed the number", the_number)

```


[Jupyter Notebooks](http://localhost:8888/notebooks/Desktop/intro_python/09_guessingGame.ipynb)