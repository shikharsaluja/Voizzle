# Voizzle : The Voice Enabled Word Puzzle 

[![game version](https://img.shields.io/badge/version-1.0-red.svg)](https://img.shields.io/badge/version-1.0-red.svg)
[![npm version](https://badge.fury.io/js/npm.svg)](https://badge.fury.io/js/npm)

_For people who enjoy playing word puzzles but are too lazy to move their hands to mark the words._


![Screenshot](http://oi63.tinypic.com/2ajwadg.jpg "Screenshot during game play")

##Installation
The dependencies for server and client. How to install them


```bash
sudo apt-get install npm
npm install node -g
git clone https://github.com/CodeCorp/Voizzle.git
cd Voizzle
npm install
node server.js
```


If you run into a problem in any of these steps, use `sudo` followed by the command

##Game Play
To start a new game press New Game button after entering the puzzle number in the text field beside the New Game button.

Press the speak button to start when you're ready to speak. The animation in the text field denotes when the app is listening.

The clients are randomly alloted a color (yellow/green) and the alloted color is highlighted in the score board on the top right.

The game begins after you press the New Game button and the timer in the right side starts. Speak a word while the app is listening and watch it get highlighted in the puzzle with the colour alloted to you while your opponents words are highlighted with a different colour. 

The aim is to find maximum number of words before the timer ends.




##Contributors
* Pulkit Agarwal ([@thepulkitagarwal](https://github.com/thepulkitagarwal))
* Rohan Goel ([@rohangoel96](https://github.com/rohangoel96))

##License
Voizzle is licensed under the [MIT License](https://github.com/CodeCorp/Voizzle/blob/master/LICENSE.md)
