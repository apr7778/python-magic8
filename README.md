# python-magic8
Write a magic8.py Python program that can answer any “Yes” or “No” question with a different fortune each time it executes.

import random "imports the Python built-in library 'random' which is used to generate random numbers. "


random_num = random.randint(1,9) "this generates a random number between 1 and 9"


answer = ""   "Python creates a variable named `answer` and assigns it an empty string. This means that `answer` contains no data currently. However, you're now able to assign a string value to the variable `answer` later in your code."

import random

name = "Joe"
question = "Will I win the lottery?"
answer = ""

random_number = random.randint(1, 9)
# print(random_number)

if random_number == 1:
  answer = "Yes - definitely"
elif random_number == 2:
  answer = "It is decidedly so"
elif random_number == 3:
  answer = "Without a doubt"
elif random_number == 4:
  answer = "Reply hazy, try again"
elif random_number == 5:
  answer = "Ask again later"
elif random_number == 6:
  answer = "Better not tell you now"
elif random_number == 7:
  answer = "My sources say no"
elif random_number == 8:
  answer = "Outlook not so good"
elif random_number == 9:
  answer = "Very doubtful"
else:
  answer = "Error"
  
print(name + " asks: " + question)
print("Magic 8 Ball's answer: " + answer)
