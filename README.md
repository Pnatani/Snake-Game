SnakeGame
=========

Classic Arcade Game- Snake

Project Report - Snake Game

By Pratibha Natani

Course: Software Engineering and Testing-Portland State University

Date: 30 January 2013


Project Description:
This game has a board and a snake. There are food items on the board for the snake to consume. The snake moves around on the board and eats the food piece. As it consumes the food piece a new piece is created on the board and the snake length increases by 1. The user can control the direction of the snake with arrow keys. 
The player cannot stop the snake from moving while the game is in progress, and cannot make the snake go in reverse. If the snake head touches itself or the walls it dies.


Project Requirements:

1.  The following minimum game parameters should be set by the player and processed by PHP prior to the start of a game:
  1.	Board size
  2.	Snake pace
  3.	Number of possible simultaneous goals

2.	Game behavior should be consistent with traditional rules of play as described on Wikipedia or other available web resources

3.	The game animates itself

4.	The player directs the head of the snake

5.	Colliding with goals/food lengthens the snake

6.	Colliding with walls or the tail of your snake ends the game

7.	Main game controls should be the keyboard arrow keys

8.	Score should be tracked and displayed during play

9.	An external style sheet should be present to skin the app

10.	There should be no JavaScript errors when the app runs

11.	The game has three levels. As the snake consumes specific number of food items the user reaches next level and with each level the snake pace is faster.


Project Files:

1)	index.html – The main page of the project which draws a form where user can choose his game options like – Board Size, Snake Pace and No of goals.

2)	Snake.php – This file has embedded PHP and Javascript code. PHP script extracts the form parameters from the index.html and processes them. The parameters are used by Javascript to set the game.  This file has the main control logic for enabling the game.

3)	Snake.css- External style content for the index.html and Snake.php files.

4)	food.png- Image of the food item drawn on the board.

5)	snake.png- Image of the snake  segments which are used to draw the snake.

6)	Snake_Report.docx- Brief project summary.


Tools/Languages Used:

•	Javascript, PHP, HTML, CSS

•	Firebug Lite 1.4.0, Wamp Server, Sublime Text2


References/Collaboration:

•	http://www.tizag.com/phpT/forms.php

•	http://www.w3schools.com/js/js_objects.asp

I discussed the project with following people: 
•	Neeraja Kanth Budamagunta, Padmaja Matlaparti, Minh Truong, Ni Ba
