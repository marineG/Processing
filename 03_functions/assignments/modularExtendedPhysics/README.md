# modular extended physics

Copy the code provided here to get you going. It's code we have seen before. What you are asked to do in this exercise is change the code so that it behaves exactly as before only this time you have moved all code out of the draw() function and into the drawBall(), moveBall() and bounceBall() which you will have to define yourselves.

### step by step

1. Change your code so that drawBall() takes in two parameters x, y for the position of the circle.
2. Change your drawBall() code so that when the mouse is inside the moving ball the ball becomes black (hint: use the [dist()](http://processing.org/reference/dist_.html) function. When the ball hits the walls it becomes red again.
3. Make your sketch interactive by adding a keyPressed() function. Inside keyPressed() you must use the system variable [key](http://processing.org/reference/key.html) so that when you press the “f” the ball moves faster. When you press “s”, it moves slower
4. using the [constrain()](http://processing.org/reference/constrain_.html) function set the max speed to 10 and the minimum to 1
