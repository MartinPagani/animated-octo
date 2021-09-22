A game for NLPF - 2021
===========================

A video game with three.js

**RULES**
- Finish the TO DO list :)
- You can update the index.html file and all the files inside the game repository

**DONE**

- [X] : As a player, I want to shot when I press space
- [X] : As a player, I want to see a little spaceship
- [X] : As a player, I want to move this little spaceship
- [X] : As a player, I want to a map with a tiles
- [X] : As a player, I want to fall when I have no tile under me
- [X] : As a player, I want to restart the game, if I fall
- [X] : As a player, I want to turn right/left to be able to change my direction (right/left) //Right direction was summing positive angle.
- [X] : As a player, I don't want any error in the Console bar //Length could change, and result in overflow as i was calculated on a fixed length.
- [X] : As a player, I want to be stop when I go into the left wall // All wall collisions were coded expect for th left one. Added it. Also aligned player position with graphic position when collinding into a wall.
- [X] : As a player, I want to have a ground when I start the game //Added a redblock at the center of the grid. + removed the translation between ground referential and player graphic referential.
- [X] : As a player, I want to decrease my life when I fall // Added a loseLife function.
- [X] : As a player, I want a better light to be able to see all the map // Increased light size. Maybe make it sdtick to the middle ?
- [X] : As a player, I want to see ennemy

**WIP**

**TO DO**

- [ ] : As a player, I want to destroy ennemy when I shot them
- [ ] : As a ennemy, I want to move on one axe
- [ ] : As a player, I want to decrease my life when I am touch by an ennemy
