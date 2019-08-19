#Frontend-Nanodegree-Arcade-Game :
==================================

Starter code source:https://github.com/udacity/frontend-nanodegree-arcade-game


## How to Download and Setup the Game :
=======================================

Installation:

Download the repository:
 * Click download ZIP on the right of the screen, then extract the zip file to your computer, or clone the repository using git.
 * Navigate to where you unzipped the file or cloned the repository.
 * Double-click index.html to open the game in your browser.
  for the below link:

	1.Download the file from [GitHub](https://github.com/udacity/fend-project-memory-game) or ZipFile (https://github.com/udacity/fend-project-memory-game/archive/master.zip)

	2. Extract the file 
	3. The file Contains:
		1. css folder, //Modify or Use for styling purpose.
		2. images folder, //Place the Images based on requirements.
		3. js folder, // Contains app.js, engine.js, resources.js.
			1. app.js // You need to modify the contents as following requirements.
			2. engine.js // Contains default scripts by udacity or git hub if you need can change it.
			3. resources.js // Contains some resources scripts
			4. ArcadeGame.js // I created a new file ArcadeGame.js for my reference and add my scripts to it. 
		4. index.html // If needed you can add your html tags to Build more.
		5. README.md // Share your information regarding Frontend-Nanodegree-Arcade-Game.
		6. Follow the Instructions of given in app.js and make it.

###Udacity Front End Nanodegree JavaScript Style Guide :
=========================================================
	[Url](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html)

### Instructions for Students :
===============================
	Students should use this [rubric](https://review.udacity.com/#!/projects/2696458597/rubric)for self-checking their submission. Make sure the functions you write are **object-oriented** - either class functions (like Player and Enemy) or class prototype functions such as Enemy.prototype.checkCollisions, and that the keyword 'this' is used appropriately within your class and class prototype functions to refer to the object the function is called upon. Also be sure that the **readme.md** file is updated with your instructions on both how to 
		1. Run and
		2. Play your arcade game.


## About Game

	In this game you have a Player and Enemies (Bugs).
	The goal of the player is to reach the water, without colliding into any one of the enemies.
	The player can move left, right, up and down. The enemies move in varying speeds on the paved block portion of the scene.

	Once a the player collides with an enemy(Bug), the game is reset and the player moves back to the start square and get.
	Once the player reaches the water the game is won.

### For more Details Check out Guide:
=====================================
For detailed instructions on how to get started, check out this [guide](https://docs.google.com/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true).

Gameplay:

=====================================

	*Use the arrow keys to move the character(Player).
	*The objective is to reach the top of the water
	*Avoid hitting the bugs while trying to make it to the 		water on the other side of the stone.
	* Each time you reach the top of the water, difficulty 		increases.
	*When you reach the water your character will move 		back to the grass so that you can try again and 	shows an alert(You Win !).
