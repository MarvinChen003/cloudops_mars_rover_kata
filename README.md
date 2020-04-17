Mars Rover Kata.

– Develop an api that moves a rover around a grid.
– You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is facing.
– The rover receives a character array of commands.
– Implement commands that move the rover forward/backward (f,b).
– Implement commands that turn the rover left/right (l,r).
– The only commands you can give the rover are f,b,l, and r.
– Implement wrapping from one edge of the grid to another. (planets are spheres after all)
– Implement obstacle detection before each move to a new square. If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point and reports the obstacle.

Here is an example:
– Let’s say that the rover is located at 0,0 facing North on a 100×100 grid.
– Given the command “ffrff” would put the rover at 2,2 facing East.
