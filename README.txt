Hannah DeFazio
2/20/18


function init:
This sets up the canvas and shaders. It initializes several variables that are used throughout the program. Several uniform variables are accessed. The polygon is drawn and rendered. 


function drawPoly:
This creates the polygon and updates myPosition. 


function movePolyKeys:
This determines what key was pressed and sets the x and y direction accordingly. This is called after a key press event. 


functions increaseButton/decrease Button:
This changes the speed of the movement depending on if the user wants to increase of decrease the speed. The value is different depending on the initial value of the movement.


function movePoly:
Changes the location of the polygon based on where the user clicks on the canvas. 


function stopStartButton:
Determines if the shape is going to be rotated based on if the rotate button is pressed. 

function render:
This refreshes the canvas, updates the variables, and draws the shape. 

Note: the rotation and translation happen in the html file. This is done by changing the x and y values with the uniform variables. 


