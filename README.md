# rock-paper-scissors
This is my first full web project which implements all three of HTML, CSS and JavaScript. The focus was not necessarily to write clean code, but code that works. It is extremely hacky but achieves the functionality that was set out to work. 

This is a one player game of Rock, Paper, Scissors. There are fixed HTML elements which include three buttons, each with an associated choice of Rock, Paper or Scissors. Firstly, there if the `getComputerChoice` function which chooses a random element out of `optionsArray = ['rock', 'paper', 'scissors']`. This is assigned to the variable we call `computerChoice` 

Also, the script waits for the player to click on one of the options. Each button has an `id` from `'rock'`, `'paper'`, `'scissors'`. On a click of a button, this `id` is passed into the `playRound` function which then decides based on some pre-defined logic, if the `computer` or the `player` is the winner. Once the calculation is performed, the `verdict` updates the player's score and the player and computer selection. When 5 rounds have been played, it displays the player that won based on a best out of 5 basis.
