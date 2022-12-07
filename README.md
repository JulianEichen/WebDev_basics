# Web-Dev basics
A collection of small projects from a [Web-Dev foundations course](https://www.theodinproject.com/paths/foundations/courses/foundations), so basic HTML, CSS and JavaScript are used.
The projects are 
- [A 'Rock Paper Scissors' game](#1-rock-paper-scissors)
- [An 'Etch-A-Sketch' page](#2-etch-a-sketch)
- [A basic calculator page](#3-calculator)

## 1 Rock Paper Scissors
### Access:
[RPS Demo](https://julianeichen.github.io/RPS/)

### Source:
'Rock Paper Scissors' game project from theOdinProject: <br>
[theOdinProject.com rock-paper-scissors](https://www.theodinproject.com/lessons/foundations-rock-paper-scissors)<br>
[theOdinProject.com revisiting rock-paper-scissors](https://www.theodinproject.com/lessons/foundations-revisiting-rock-paper-scissors)

### Task (extract):

- Your game is going to play against the computer, so begin with a function called getComputerChoice that will randomly return either ‘Rock’, ‘Paper’ or ‘Scissors’. We’ll use this function in the game to make the computer’s play. 
- Write a function that plays a single round of Rock Paper Scissors. The function should take two parameters - the playerSelection and computerSelection - and then return a string that declares the winner of the round like so: "You Lose! Paper beats Rock".
- In our UI, the player should be able to play the game by clicking on buttons rather than typing their answer in a prompt. 
- Create three buttons, one for each selection. Add an event listener to the buttons that call your playRound function with the correct playerSelection every time a button is clicked.

### Changes And Added Features:
- no running score


## 2 Etch-A-Sketch
### Access:
[Etch A Sketch Demo](https://julianeichen.github.io/et-a-sk/)

### Source:
Etch-A-Sketch project from theOdinProject: <br>
https://www.theodinproject.com/lessons/foundations-etch-a-sketch

### Task (extract):

- Create a webpage with a 16x16 grid of square divs. Create the divs using JavaScript. Don’t try making them by hand with copy and pasting in your HTML file!
- Set up a “hover” effect so that the grid divs change color when your mouse passes over them, leaving a (pixelated) trail through your grid like a pen would. 
- Add a button to the top of the screen that will send the user a popup asking for the number of squares per side for the new grid. Once entered, the existing grid should be removed and a new grid should be generated in the same total space as before (e.g. 960px wide) so that you’ve got a new sketch pad.

### Changes And Added Features:
- toggle borders between squares
- drop-down menu to chose between colors


## 3 Calculator
### Access:

[Calculator Demo](https://julianeichen.github.io/meCalc/)

### Source:
Calculator project from theOdinProject:

https://www.theodinproject.com/lessons/foundations-calculator

### Task (extract):

- Your calculator is going to contain functions for all of the basic math operators[...]. add, subtract, multiply & divide
- Create a basic HTML calculator with buttons for each digit, each of the above functions and an “Equals” key. 
- Users should be able to string together several operations and get the right answer, with each pair of numbers being evaluated at a time. **For example, $12 + 7 - 5 * 3 =$ should yield $42$.**
- Your calculator should not evaluate more than a single pair of numbers at a time. 

### Changes And Added Features:
- maximum length for numbers are 9 digits (including '.')
- floating point numbers
