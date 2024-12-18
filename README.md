# Magic 8-Ball Program

## Overview
This program simulates the classic Magic 8-Ball toy, which provides answers to yes-or-no questions. The user can input a question, and the program will return a random response from a predefined list of possible answers.

## Features
- Allows users to ask any yes-or-no question.
- Provides a random answer from 9 possible responses.
- Simple and interactive user interface through the command line.

## How It Works
1. The program displays a welcome message.
2. The user is prompted to input a question.
3. A random number between 1 and 9 is generated using the `random.randrange` function.
4. Based on the generated number, a corresponding response is printed.

## Responses
The Magic 8-Ball can return one of the following answers:
1. Yes - definitely.
2. It is decidedly so.
3. Without a doubt.
4. Reply hazy, try again.
5. Ask again later.
6. Better not tell you now.
7. My sources say no.
8. Outlook not so good.
9. Very doubtful.

## Requirements
- Python 3.x

## How to Run
1. Save the code in a file named `magic_8_ball.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory where the file is saved.
4. Run the program using the command:
   ```
   python magic_8_ball.py
   ```
5. Follow the prompts to ask your question and receive a response.
