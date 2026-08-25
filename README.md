# Guess My Number

Practice project from Jonas Schmedtmann's JavaScript course. I built it while learning DOM manipulation, then rebuilt the interface in Webflow.

## What it does

The page picks a secret number between 1 and 20. You guess, and it tells you whether you are too high or too low. You start with 20 points and lose one per wrong guess. The best score in the session is kept as a high score.

## Built with

- JavaScript
- Webflow

## What I learned

- Reading and writing DOM content with `querySelector` and `textContent`
- Handling click events and converting input values to numbers
- Keeping score and high score in variables that survive a reset
- Why doing the same `document.querySelector` lookup over and over is worth pulling into a function

## Demo

[Play it here](https://nikola-jovanovic-guess-my-number.webflow.io)

## Note

This is course work, not an original project. It is here because it is where I started with JavaScript and I would rather show the progression than hide it.
