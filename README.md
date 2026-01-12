# Simple Chat Bot with Java

A simple console-based chat bot written in Java. This bot can engage in a basic conversation, guess your age, count numbers, and test your programming knowledge.

## Features

- **Greeting**: The bot introduces itself and asks for your name.
- **Age Guesser**: The bot guesses your age using the remainders of dividing your age by 3, 5, and 7.
- **Counter**: The bot counts from 0 to a number you specify.
- **Quiz**: The bot asks a programming-related question and verifies your answer.

## How to Run

1.  Ensure you have Java installed.
2.  Navigate to the `src/bot` directory.
3.  Compile the code:
    ```bash
    javac SimpleBot.java
    ```
4.  Run the bot:
    ```bash
    java bot.SimpleBot
    ```

## Usage Example

```text
Hello! My name is Aid.
I was created in 2018.
Please, remind me your name.
> User
What a great name you have, User!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
> 1
> 2
> 1
Your age is 22; that's a good time to start programming!
Now I will prove to you that I can count to any number you want.
> 5
0!
1!
2!
3!
4!
5!
Let's test your programming knowledge.
Why do we use methods?
1. To repeat a statement multiple times.
2. To decompose a program into several small subroutines.
3. To determine the execution time of a program.
4. To interrupt the execution of a program.
> 2
Completed, have a nice day!
```

## About

This project is a simple implementation of a chat bot to demonstrate basic Java syntax, input/output, and control flow structures.
