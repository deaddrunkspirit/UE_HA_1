# UE_HA_1

### DisDoc

***Name:*** UE_HA_1

***Description:*** This is a 3d game with procedural level generation

***Plot:*** no plot

***Gameplay:*** Main character needs to pass through levels and earn maximum score. To success
character needs to avoid moving obstacles and jump through different platforms. Player can collect
bonuses to make gameplay easier for some time period. Difficulty increases from level to level (levels are longer, objects are faster)

***Mechanics:***

1. Main character

a. Walk

b. Jump

c. Ragdoll

2. Bonuses

a. Walk through walls

b. Slow time

***Interface:*** Basic interface that shows which bonusses active and what level you are on

***Graphics:*** 3D graphics

***View:*** 3rd person view from the back of the character

***Sounds and music:*** -

***Technologies:*** UE 4.26, created for Windows 10

### Level generation

Levels are generated procedurally. It depends on the difficulty - the higher the difficulty, the longer the level and the faster the objects. Level has multiple different assets. Level finished when player crosses finish line at the end of the level. Each level represents a path with one direction, but this direction can change in some parts of the level (the path can go right or left). Each level has randomly spawned bonuses of 2 types - Slow time bonus and Walk through wall bonus. They spawn with possibilities 2/3  for STB and 1/3 for WTWB 

### Bonuses

1. Walk through walls bonus
2. Slow time bonus

### Moving obstacles

#### Hammer
This object is a hammer that moves vertically around its handle. After hammer hits player, player goes ragdoll

#### Wall
Wall moves up and down to confuse or stop player to go through

#### SeeSaw
Platform that fixed at the center and rotates. If player stands on this platform it starting to simulate physics, so player can accidently fall from it.

#### MovingWall
This object rotates around its axis horizontally. If wall hits player with its front side (from rotation direction view) it goes ragdoll

### Mechanics ideas
Ideas for wall, moving wall, see saw and hammer were taken from the game "Fall Guys". This object mechanics helps to make a challenge for player.

### Gameplay Scemes

![Flowchart](https://user-images.githubusercontent.com/55884001/146657667-2c4eff28-49a7-454a-9868-ce988f8a2273.jpg)

### Links to sources
No sources were used
