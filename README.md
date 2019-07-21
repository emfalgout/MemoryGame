# Memory Game Project

## Table of Contents

1. [Description](#description)
2. [Instructions](#instructions)
3. [Contributing](#contributing)

## Description

This project is a memory game written in JavaScript, HTML and CSS. A four-by-four board of blank cards is presented to the player. The player can click on a card to reveal a symbol.  The symbol on each card matches that of another card on the board. The objective of the game is to find the matching card to each pair in the least amount of moves and time possible. If two cards do not match, they will shake, turn red, and flip back over. If they do match, they will turn turquoise, a wiggle-like animation will play and the cards will remain face up. Once all the card pairs are uncovered, the game is finished and a congratulatory modal will be displayed with the final game stats and a play again button.

## Instructions
Once the game files are downloaded, you can start the game by opening `index.html` in your browser of choice.

## Usage
The main files for this project are the following:

| File name         | Description                                           |
|-------------------| ------------------------------------------------------|
| `css/app.css`     | The styling for game board and congratulations modal  |
| `css/animate.css` | The styling for the animations                        |
| `index.html`      | The main HTML file for the game                       |
| `js/app.js`       | The main JavaScript file for the game                 |

All of the program files must be saved in their corresponding subdirectories unless it is a Markdown file or `index.html` which can be saved in the main directory. Please refer to the following table for a breakdown of all the subdirectories.

| Subdirectory Name | Description       |
|-------------------|-------------------|
|`css`              | CSS files         |
|`gifs`             | All .gif files    |
|`img`              | All images        |
|`js`               | JavaScript files  |


### Game Play

#### Start of Game
<img src="img/start-game.png" width = "350">

#### Cards Do Not Match
<img src="gifs/no-match-animation.gif" width = "350">

#### Cards Match
<img src="gifs/match-animation.gif" width = "350">

#### Resetting the Game
<img src="gifs/reset-game.gif" width = "350">

#### Completed Game
<img src="gifs/finished-game.gif" width = "350">

#### Replaying
<img src="gifs/play-again.gif" width = "350">


## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).
