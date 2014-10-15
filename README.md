PaddleSweep
===========

Paddle Sweep project with Processing

The project is a  game built with Processing 2.0 framework.
The gameplay is to move the paddle present at the centre of the screen in a vertical direction.
Four elliptical projectiles move with different velocities within the vicinity of a rectangular region of interest. 
The objective is to come in contact with these projectiles. Each projectile carries different points 1,2,3,4.
The player is given 100 seconds to score a maximum number of points. The one with the highest score wins.

The game uses pVector class of a euclidean vector to describe the motion of the elliptical projectiles. The projectiles are circular. The projectiles with the greatest speed fetches more points on contact event.
