# snakes_game
This snakes game is based on python and opencv. the program do not cover all the aspect of original snakes game but will illustrate the how to make a basic snakes game.

## Libraries used
- opencv
- numpy
- random

## how to create your own snakes game
- first of all create a background with a border. This is done with the help of new_game function in the program which returns a numpy array with shape 500x500x3
- Then initialize the coordinates of both the snake and the food. This is done with the help of random_pos function which return two random number which are used as the coordinates for the food and snake.
- then in an infinite loop assign different color to the coordinate of the snake and food so that it can be distinguished by the player.
- read the key strokes pressed by the user and change the coordinates of the snake according to the key strokes
- if the player press the escape key destroy all the windows and exit the program
- if the snake eats the food generate a new coordinate of the food.



- suggestions and code improvements are most welcome.
