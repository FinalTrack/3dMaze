# 3dMaze (Canvas Fun)
Video Demo: https://www.youtube.com/watch?v=ubJLTP-Oz-g

Use the arrow keys to navigate the maze and obtain all 15 gems.

3d maze utilizes a method known as raycasting, to create the illusion of 3d graphics in a 2d map. Rays are sent out along the player's field of view and travel until they hit a wall. The height of the line drawn on the screen depends upon the distance the ray travelled. An algorithm called as Digital Differential Analysis is used for checking collisions between a ray and a square grid: https://lodev.org/cgtutor/raycasting.html

Using canvas's drawImage function, it was possible to incorporate textures and sprites into the game. The images and sound effects used in this game were found on the internet from various sources. 
