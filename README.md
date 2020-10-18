# amWRit

# Angry50

As part of learning through Harvard's CS50G "Introduction to Game Development" course, recreating the Angry Birds game using Lua and LOVE2D.
Updates were made on the original source code provided by CS50, based on assignment specifications.

__Assignment 6: “Angry Birds, The Tri-Shot Update”__

__LOVE 11.3__

# Assignment Updates

__Split Player Aliens__
- When space bar is pressed  after the player Alien is launched and it hasn’t hit anything yet, split the player alien into two. 
- If the player Alien isn't launched, hitting space bar doesn't split the Alien.
- If the player Alien has collided or hit the obstacles, hitting space bar doesn't split the Alien.

__Respawn Player AlienLaunchMarker__
- Respawn Player Alien only if all of the three player aliens have come to near halt.