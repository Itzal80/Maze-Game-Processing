# Maze-Game-Processing
A simple, customization maze game. Each maze is different and unique.

This program is a two part program. The first part of the program is an algorithum that produces random mazes every time. 
How the algorithum works:
First it starts at a point on a grid. Each grid point has "walls." Each point also has neighbors.
If the starting point (lets call this guy the creator) moves, he destroys all the walls he touches.
Randomly going to a neighbor the creator keeps destroying walls
The creator will not go through wall to a grid spot he went to before. This prevents loops.
If the creator is stuck and surounded by neighbors he has visited, he back tracks.
This is done by adding all moves to an array and takes appart said array through a stack idea.
The algorighum is done once the creator is back at the start.

The second part of this program is makeing the algorithum a game.
It picks a end location by random. It looks at all locations that have 3 walls left and picks one of them to be the end.
Then the player is spawned in and can move with wasd or the arrow keys.
The program also times the player

When the player first opens up the program they are met with a custimization menu.
Here the user can change almost every aspect of the game.

I hope you enjoy the game!
