# Cricket Game

A simple web-based Cricket Game that lets users play a Bat-Ball-Stump game against the computer. The game involves making a choice between Bat, Ball, or Stump, and the computer generates a random move. The game keeps track of the user's score, including wins, losses, and ties.

## Table of Contents

- [Overview](#overview)
- [Game Features](#game-features)
- [How to Play](#how-to-play)
- [Resetting the Game](#resetting-the-game)
- [Technical Details](#technical-details)

## Overview

The Cricket Game is a browser-based application that allows users to play a simple game against the computer. The game involves making a choice between Bat, Ball, or Stump, and the computer randomly generates its move. The result of the game is displayed, and the user's score is updated accordingly.

## Game Features

- **User Choice:** The user can choose between Bat, Ball, or Stump by clicking on the respective buttons.
- **Random Computer Move:** The computer generates a random move (Bat, Ball, or Stump) for each round.
- **Result Display:** The game displays the user's choice, the computer's move, and the result of the round.
- **Score Tracking:** The user's score, including wins, losses, and ties, is displayed after each round.
- **LocalStorage Persistence:** The user's score is persisted using `localStorage` to maintain the state even after refreshing or closing the browser.

## How to Play

1. Click on the "Bat," "Ball," or "Stump" button to make your move.
2. The computer will randomly generate its move.
3. The result of the round, along with your and the computer's moves, will be displayed.
4. The updated score, including wins, losses, and ties, will be shown.

## Resetting the Game

To reset the game and clear the score:

1. Click the "Reset" button.
2. The game score will be reset, and you can start playing again.

## Technical Details

- **HTML and CSS:** The game interface is built using HTML and styled with CSS.
- **JavaScript:** The game logic is implemented using JavaScript.
- **LocalStorage:** The `localStorage` API is used to persist the user's score across sessions.
- **Random Move Generation:** The computer's move is generated randomly using the `Math.random()` function.

Feel free to explore the code to understand the implementation details and make any enhancements or modifications as needed. Enjoy playing the Cricket Game!
