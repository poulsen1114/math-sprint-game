# Math Quiz Game

## Overview

This is a simple math quiz game where users can select the number of questions they want to answer and test their math skills by solving random multiplication equations. The game keeps track of the user's time, penalizing them for incorrect answers, and displays their final score on the score page. The best scores for different question amounts are also saved in local storage and displayed on the splash page.

## Pages

### 1. Splash Page (`splash-page`)

The splash page is the starting point of the game. It allows users to choose the number of questions they want to answer using radio buttons. The best scores for different question amounts are displayed on the page.

### 2. Countdown Page (`countdown-page`)

The countdown page shows a countdown timer (5, 4, 3, 2, 1, GO!) before the game starts. It creates the game equations and prepares for the game.

### 3. Game Page (`game-page`)

The game page displays the math equations that the user needs to solve. Users need to select their answer (true or false) for each equation. The game keeps track of the time played.

### 4. Score Page (`score-page`)

The score page displays the final score, which is the total time taken to complete the quiz. It also shows the base time (time played without penalties) and the penalty time (additional time added for incorrect answers). The page also allows users to play again.

## Features

- Users can choose the number of questions they want to answer.
- The game displays random multiplication equations.
- Users can select their answers (true or false) for each equation.
- The game penalizes users with a 0.5-second penalty for each incorrect answer.
- The game keeps track of the user's time and displays the final score.
- Best scores for different question amounts are saved in local storage and displayed on the splash page.
- Users can play the game again after viewing their score.

## How to Play

1. Open `index.html` in a web browser.
2. On the splash page, choose the number of questions you want to answer using the radio buttons.
3. Click the "Start" button to begin the game.
4. On the countdown page, wait for the timer to count down from 5 to 1 and then display "GO!".
5. On the game page, solve the math equations by selecting either "true" or "false" for each equation.
6. The game will penalize you with 0.5 seconds for each incorrect answer.
7. After answering all the questions, you will be redirected to the score page, displaying your final score.
8. The best scores for different question amounts are shown on the splash page.

## Dependencies

- This game does not have any external dependencies and can be run in any modern web browser.

Enjoy the game and have fun testing your math skills!
