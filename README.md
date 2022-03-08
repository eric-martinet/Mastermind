<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Mastermind game coding in Python
*Ildem Sanli, Olivier Masson*

*DATA 212, Paris Campus, Feb 25, 2022*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
Develop a Mastermind game version in Python.

## Rules
The mastermind game consists in that the codemaker secretly creates a code consisting of a sequence of 4 colored pins from a specific based on 6 possible colors.

Then, the codebreaker tries to guess the exact position of the sequence in the secret code.

For each guess that the codebreaker makes, the codemaker gives feedback with white and black pegs. Black pegs indicate the number of exact matches (right color in the right position). White pegs indicate the number of near matches (right color but wrong position.

We decided to initiate the game with a random generated code using Python’s random function.

## Workflow

1.	Project initiation (including flowchart and JIRA project planning)
2.	Coding (including integration and debugging)
3.	Preparation of key deliverables
4.	5-min Monday morning presentation


## Organization
Workflow was managed through a JIRA based Kanban board.

Repository structure:

* [Flowchart](1_Flowchart/): Flowchart logic behind the game
* [Code](2_Code/): The game as a Python file in Jupyter Notebook format
* [Slides](3_Slides/): Powerpoint presentation made to the class

## Links
[Game's repository](https://github.com/ildemsanli/Mastermind)

[JIRA board](https://dafeb.atlassian.net/jira/software/projects/G6/boards/3)

For more information on the game: https://en.wikipedia.org/wiki/Battleship_(game).
