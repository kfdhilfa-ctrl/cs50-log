# Week 0 - Scratch

This folder contains my Scratch project for Week 0 of CS50.

## Project

- File: project.sb3

## Description

This project is a simple interactive story built in Scratch.

The user starts by pressing keys to begin and is then asked if they are interested in joining a math class. If they choose yes, they enter a hall and meet another character who gives them a short test.

The test consists of 4 questions, and the user needs at least 3 correct answers to pass. If they pass, they get admitted to the class. Otherwise, they fail.

This project helped me practice using user input, conditions, and variables to control how the story progresses.

## Features

- Multiple sprites (including a non-cat sprite)
- Interactive story with user choices
- Uses loops and conditions
- Uses variables to track progress and score
- Includes a custom block

## CS50 Check

All requirements were successfully met using check50.

- Valid Scratch project
- Contains at least two sprites (including a non-cat sprite)
- Includes multiple scripts
- Uses:
  - Conditions
  - Loops
  - Variables
  - Custom blocks

All checks passed successfully.

## Notes

I got stuck for over an hour on a bug where one sprite was not waiting for another to finish.

I learned that in Scratch, different sprites run their scripts in parallel, not sequentially. This means they do not automatically wait for each other.

To fix this, I had to explicitly control the flow using conditions and timing so that one part of the program waits for another.

This helped me better understand how program flow works.
