

# UE_HA_1

### DisDoc

***Name:*** UE_HA_1

***Description:*** This is a 3d game with 

***Plot:*** no plot

***Gameplay:*** Main character needs to pass through levels and earn maximum score. To success 
character needs to avoid moving obstacles and jump through different platforms. Game is over if player goes ragdoll or fall.

***Mechanics:***

1. Main character

a. Walk

b. Jump

c. Ragdoll

***Interface:*** -

***Graphics:*** 3D graphics without textures

***View:*** 3rd person view from the back of the character

***Sounds and music:*** -

***Technologies:*** UE 4.26, created for Windows 10

### Level generation

Levels are generated procedurally. It depends on the difficulty - the higher the difficulty, the longer the level. Level has multiple different assets. By randomly picking 2 * difficulty + 1 assets level generates this count multiple by two platforms. These platforms are main body of the level. Level also has empty platforms at the beggining and at the end. Level finished when player crosses finish line. Each level is a set of streaming sublevels.

### Bonuses

Bonuses not yet implemented

### Moving obstacles 

#### Hammer
This object is a hammer that moves vertically around its handle. After hammer hits player, player goes ragdoll -> gameover

#### Wall
Wall moves up and down to confuse or stop player to go through

#### SeeSaw
Platform that fixed at the center and rotates. If player stands on this platform it starting to simulate physics, so player can accidently fall from it.

#### MovingWall
This object rotates around its axis horizontally. If wall hits player with its front side (from rotation direction view) it goes ragdoll -> game over.

### Mechanics ideas
Ideas for wall, moving wall, see saw and hammer were taken from the game "Fall Guys". This object mechanics helps to make a challenge for player.

### Gameplay Scemes
No schemes yet

### Links to sources
No sources were used

