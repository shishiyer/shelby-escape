**Shishir Iyer  
Period 2  
05-25-18**  

# Shelby Escape

Mr. Shelby's computer has been overrun by bugs! After hours of trying to debug, he has gotten trapped within his computer. 
Help him escape!

### Program Details

If you are reading this, go and play outside or do something more constructive. This program is designed for those who want
to constructively waste time.

In this program, the player (represented by an image of Mr. Shelby) has to navigate to the end of the level while avoiding 
enemies (the bugs) that obstruct his or her path. Some of the enemies move in set paths, some wander around the screen 
randomly, while others chase the player, the latter of which the player can shoot. The player has 3 three health points. 
Shooting an enemy awards the player 1 health point, while touching an enemy makes the player lose 1. The player also starts
out with a timer of 1:00. Completing a level adds 10 seconds, while losing health subtracts 5 seconds. The player also has to
navigate around holes (code style errors). Should he or she fall into one, the player will go back to the previous level.

### Concept Art

```
_____________________
|                   |        |>  - Level end
|         |>        |        |
|         |         |
|___________________|        X - enemy
|                   |        S - player
|   X X X X X X X   |        O - hole
|                   |
| X X X X X X X X X |
|              O    |
|   X X X X X X     |
|                   |
|    O              |
|                   |
|                   |
|          S        |
|___________________|

```
### Controls

**W / Up arrow** - move forward  
**A / Left arrow** - move left  
**S / Right arrow** - move right  
**D / Down arrow** - move backwards  
**Spacebar** - shoot (introduced in Level 5)  

### Class List

**Sprite** - describes all elements that are drawn on the screen  
**Player** - controls the function of the player  
**Enemy** - represents any enemy in the game  
**Hole** - represents the functionality of a pothole  
**FixedHorizontalPathEnemy** - represents an enemy that travels along a fixed horizontal path  
**FixedVerticalPathEnemy** - represents an enemy that travels along a fixed vertical path  
**RandomEnemy** - represents an enemy that travels in a random direction  
**TrackingEnemy** - represents an enemy that chases the player  
**GameBoard** - represents the drawing surface where all the elements of the game are rendered  
**Game** - controls the logic of the game  

### Responsibility List

**Shishir (that's me!)** - All of the classes mentioned above.
