# Snake-Game-HS2021

Project Language: Python

Group ID:  108

## Table of contents
* [Introduction](#Introduction)
* [General-Content](#General-Content)
* [Repository](#Repository)
* [Installations](#Installations)

## Introduction
This project is part of the mandatory curriculum of the course “7,789 | 8,789: Skills: Programming with Advanced Computer Languages” supervised by Dr. Mario Silic at the University of St. Gallen. It was created by a group of students consisting of six people namely Deniz Süzen, Hyungmin Koh, Jonas Rusca, Nurel Yilmaz, Samuel Bissegger und Wei Zheng. 

## General-Content
This project aims to build a simple and fun “Snake” game with some individualized features using the programming language Python. Snake is a bordered plane game, designed in the time of the arcade game blockade in the late 1970ies. The game design is set up to maneuver a dot, and later a line in direction of tokens. The tokens have the impact of making the line grow in length. The objective of the game is to eat as many tokens as possible. At the same time the player must not touch the walls, obstacle, or collide with the players avatar. Else the game ends and the player is attempt anew. 

We will be using Pygame and pygame.menu to create this game. PyGame is an open-source library that is designed for making video games. It has inbuilt graphics and sound libraries. It is also beginner-friendly, and is suitable for cross-platform games.

The game starts with a title screen where it is possible for the user to enter their name and refer to the instructions if needed. In order to start the game the player has to press “start” or press “quit” if they wish to leave the game.

The gaming interface shows the score at the top left corner. To play the game the user navigates the snake, which is the green block, with the arrow keys. There are three additional features on the screen. First are the obstacles which colored in black and should be avoided. The other two features are the two types of “food” added to the game. Starting with the regular red food item that increases the length of the body by one block and the score by 1 point after being eaten. The other is a special item that appears randomly after 15 seconds. The yellow food block increases the length of the snake by 5 blocks but also increases the score by three extra points. A sound effect is played once a food item is eaten or when the snake collides with the obstacle, the wall or itself. 
Once the snake run into an obstacle, the boarder or the avatar itself, the game over screen pops up and shows the currently reached score. The player can choose to restart the game by clicking the “replay game” button or choose to exit the game by selecting “quit game”. 

## Repository
The repository shows five files. The “README.md ” file gives an overall introduction and project description. “Snake-Game-HS2021.py” contains the code. The screenshots within “Screenshot” show the gaming interfaces. “Ding.mp3”and “game_over.mp3”are used for the sound effects. 

In case you are using jupyter notebook to run the code, please ensure that the code and the sound files are located in the same folder for the code to run smoothly. 

## Installations
The following programs were used to analyse and test the code:
* Python 3.9 
* Anaconda 3
* Jupyter Notebook and VS Code (visual studio code - program)

The following packages are required to run the code: 
* pygame, pygame-menu, time, datetime, sys, random
In case these packages are not installed yet. Please run “pip install” for each package.
