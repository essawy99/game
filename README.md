# BrickBreaker

Contributers:

Mo Essawy,
Osman,
Dheva

This codeBase contains a lot of comments in order to make it easier
for an outside observer to understand it. There may be some areas
that are light in comments and could be difficult to understad it
should be easy to get a grasp of the overall structure. The program
will load into any modern browser and has no dependencies. The 
program begins at index.html where a series of scripts are run. 
Globalvars.js defines a number of global variables used extensively
in the program including w, h, wUnit, hUnit, center, though most of
these variables are self explanatory

The script is begun and controlled through controller.js. Controller.js
creates a game object described by  Game.js. Which interacts with 
a number of different game objects such as enemyPlanes.js, enemyShips.js
cannon.js, background-tanks-health.js, and user.js. explosion.js defines
explosions that are used by enemyPlanes.js and design.js contains the designs 
for all of the drawings. This code was generated by creator which can be found
at https://github.com/essawy99/Creator.

There are multiple layers and sublayers of abstraction that allowed us to develop
the program simultaneously and minimize the amount of code needed to run the program.
Multiple iterations of code reductions allowed us to cut down file sizes from 30-70%
by removing redundencies.

Game can be played at https://essawy99.github.io/game.github.io/

Any questions on how the code works can be sent to essaw007@umn.edu.
