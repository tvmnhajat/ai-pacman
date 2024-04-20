
## Problem Description
You are given a file which describe Pac-man World. Propose or apply learned algorithms to help Pac-Man to find foods without dying by monsters.

<p align='center'><img align='center' src="http://ai.berkeley.edu/images/pacman_game.gif"></p>

Pacman or monsters only moves in 4 direction: left, right, bottom, up and cannot move over or through the wall. The game has four levels:
- Level 1: Pac-man know the food’s position in map and monsters do not appear in map. There is only one food in the map.
- Level 2: monsters stand in the place ever (never move around). If Pac-man pass through the monster or vice versa, game is over. There is still one food in the map and Pac-man know its position.
- Level 3: Pac-man cannot see the foods if they are outside Pacman’s nearest threestep. It means that Pac-man just only scan all the adjacent him (8 tiles x 3). There are many foods in the map. Monsters just move one step in any valid direction (if any) around the initial location at the start of the game. Each step Pacman go, each step Monsters move.
- Level 4 (difficult): map is opened. Monsters will seek and kill Pac-man. Pac-man want to get food as much as possible. Pacman will die if at least one monster passes him. It is ok for monsters go through each other. Each step Pacman go, each step Monsters move. The food is so many. 

Game points is calculated as following rules:
- Each moving step, your point will be decreased by 1.
- Each food you take, 20 points will be given for you.

You may need to run your algorithm on many different graphs to make a comprehensive comparison of these algorithms’ performance regarding the following aspects:
- Time to finished
- The length of the discovered paths

Specially, you should generate some difficult maps such as Pac-man is stay among two monster or wall is around in all side. 
