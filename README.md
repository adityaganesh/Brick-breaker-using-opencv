# Brick-breaker-using-opencv
In this project will be using any square object which has plain blue colour on it to move the paddle in the brick breaker game the whole game is similar to the original brick breaker game but the paddle will be controlled using a blue square object
# What does this game do?
This game is pretty similar to the game which we played in our childhood the goal is to break all the bricks using a paddle and ball.
Now the fun part is the paddle is not controlled by your keyboard but using a blue coloured square card you can hold this card in front of your webcam and move the card and the paddle will
move correspondingly. 
# How did I achieve this?
Now to achieve this one obvious thing is we need to be using image processing so we use the opencv package which is a open source package for image processing using python.
Now the main thing is to track the blue card and to do this we will be using a hsv values of the card and we will find the contour of blue card and find the centre of the contour and map
the centre to the paddles x and y coordinate to move it.

