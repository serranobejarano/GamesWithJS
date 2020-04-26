# Games With JS
This repository is meant to gain some basic knowledge about JavaScript while building some classic video games.

The original source of these games is [this repository](https://github.com/kubowania) from Ania Kubow.

## Game Index
1. [Memory Game](#1-memory-game)
2. [Whack-a-mole](#2-whack-a-mole)
3. [Connect Four](#3-connect-four)
4. [Snake](#4-snake)
5. [Space Invaders](#5-space-invaders)
6. [Frogger](#6-frogger)
7. [Tetris](#7-Tetris)

## 1. Memory Game

A retro grid-based game in vanilla JavaScript, HTML and CSS.

Memory Game, or Matching Game, is a simple card game where you need to match pairs by turn over 2 cards at a time. 

### Inbuilt functions to focus on:
- for loops
- addEventListener
- setAttribute
- getAttribute
- data-name
- document.querySelector
- createElement

[Check the code!](/1_MemoryGame)

## 2. Whack-a-mole
Simple grid-based game using HTML, CSS and JavaScript. 

The idea of whack-a-mole is simple! The player needs to hit the grid with the mole in as many times as possible until the time runs out.

### Inbuilt functions to focus on:
- document.querySelector
- textContent
- forEach
- addEventListener
- setInterval
- classList.add

[Check the code!](/2_Whack-a-mole)

## 3. Connect Four
A retro grid-based game in vanilla JavaScript, HTML and CSS.

Connect Four is a two-player board game in which the players first choose a color and then take turns dropping one colored disc from the top into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

### Rules of the Game
1. You will start as player One
2. You will take your go as player One
3. You will not be allowed to go in squares that are not at the bottom of the grid, or do not have a taken square under it
4. Once your go is taken and you did not win, It will be player Two's go
5. The gamer will continue until a winning combination of four is reached by player One or player Two, or until the grid is full and no winning combination was found.

### Inbuilt functions to focus on:
- for loops
- addEventListener
- setInterval
- document.querySelector
- arrow functions

[Check the code!](/3_ConnectFour)

## 4. Snake

Well, everyone knows Snake. What else can I tell you about it?

### Inbuilt functions to focus on:
- project set up
- linking your JavaScript and CSS files to - your HTML file
- event listeners
- query Selectors
- arrow functions
- forEach
- setting time intervals and countdowns

[Check the code!](/4_Snake)

# 5. Space Invaders
A vanilla JavaScript game with HTML and CSS.

Space Invaders is a simple grid-based game in which you as the shooter have to shoot down as many alien invaders before they get to you. We are going to build a 15 x 15 grid square with 20 invaders to shoot.

### Inbuilt functions to focus on:
- for loops
- addEventListener
- classList
- document.querySelector
- Timeout
- switch case

[Check the code!](/5_SpaceInvaders)

# 6. Frogger
A retro grid-based game in vanilla JavaScript, HTML and CSS.

Frogger is a 1981 arcade game developed by Konami and originally published by Sega. The game was originally going to be titled "Highway Crossing Frog," but the executives at Sega felt it did not capture the true nature of the game and was changed simply to "Frogger". The object of the game is to direct a frog to its home by crossing a busy road and navigating a river by jumping on logs.

### Rules of the game
- You will start on your blue starting block, or 'starting-block'
- You have 20 seconds from pressing the start button to get to your red block or 'ending-block' to win the game
- You will lose if the time runs out
- You will lose if you get hit by a car, or 'c1'
- You will lose if you fall into the river, or '.l4, .l5, .lf2, .lf3'
- You will be safe on the road, or '.c2, .c3'
- You will be safe on the logs, or '.l1, .l2, .l3'
- You will move with the logs when on them
- You can pause the game by pressing the same button as you did to start the game

### Inbuilt functions to focus on:
- switch
- cases
- addEventListener
- removeEventListener
- setInterval
- clearInterval
- document.querySelector
- arrow functions

[Check the code!](/6_Frogger)

## 7. Tetris
Again... Who doesn't know tetris?

[Check the code!](/7_Tetris)