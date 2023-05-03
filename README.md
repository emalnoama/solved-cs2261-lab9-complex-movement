Download Link: https://assignmentchef.com/product/solved-cs2261-lab9-complex-movement
<br>
In this lab, you will be completing several different TODOs, which will, piece by piece, add complex sprite movement. Your code may not compile until you complete an entire TODO block, at which point the game should compile with a new component of the final outcome (unless otherwise specified).

TODO 1 – Complex Camera Movement

We want our pikachu to walk only on the screen, and have the camera follow it without showing something outside of the world.

<ul>

 <li>TODO 1.0: In game.c, in the updatePlayer() function, add in the sprite and camera movement.</li>

</ul>

Your pikachu should now be able to walk around and see the entire map, but not off of the edge. The pikachu should always be in the middle of the screen unless at the edge of the map (see the example.gba).




<h2>TODO 2 – Collision Map</h2>

Now we want our pikachu to treat the visuals of the map is if they were actual barriers to movement.

<ul>

 <li>TODO 2.0: The collision map has been created for you. Open collisionmap.bmp and export it. Remember that we want to check the colors of each pixel, so take that into account when choosing export settings.</li>

 <li>TODO 2.1: Add collisionmap.c to your Makefile, and include collisionmap.h in game.c.</li>

 <li>TODO 2.2: Update your movement code to only allow pikachu to move if the collision map allows it (is white) in the areas that you need to check.</li>

</ul>

Your pikachu should be not be able to walk over the house or the bushes. The pikachu should be able to walk between the house and the bushes on the right and top, in both directions.


