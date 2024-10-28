"""
Write a code in python that asks for the users age
- use the get input function (explained below)
- the age must be an integer between 0 and 80

2) Determine the guessing range based on age
- If the age is between 0 and 12(inclusive), set max range = to 5
- If the age is between 13 and 18(inclusive), set max range = to 10
- If the age is above 18, set max range = to 20

3) Generate a random number
- Use randint function from random module to generate a random number between 0 and max_range

4) Prompt the user the guess the number
- prompt the user to guess the number
- use the get_user_input() function (explained below)
- the guess must be between 0 and max_range

5) provide feedback
- if the guess is correct, print: Congratulations! You guessed the correct number.
- If the guess is incorrect, print: Not correct. The number was {secret_number}
"""