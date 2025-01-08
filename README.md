# Augmented-RaceAUGMENTED RACE 
Description: 
This game features two virtual players competing to reach a preset destination on virtual 
racetracks. Player movement is controlled by individual virtual buttons assigned to each player. 
When a player's movement button is pressed, their game piece will advance one step forward 
on the playing surface. 
A third virtual button acts as a simulated dice roll to determine how many steps a player may 
move each turn. When this button is pressed, it randomly generates a whole number between 1 
and 3, representing a dice roll value. The player whose turn it is, will press their movement 
button, to move their virtual player forward. 
Gameplay alternates between players, with the virtual dice rolled to set the movement range 
for Player 1 first. Player 1 then presses their movement button the allotted number of times. 
Play then passes to Player 2 who gets to press the random number generator button and 
corresponding movement for their game piece. This alternates until one player lands their game 
piece exactly on the destination spot, winning the game. 
Virtual Objects:  
 Virtual Players: 
Virtual players have been successfully set up. We have downloaded these from 
the Unity asset store. 
 Virtual Racetrack: 
A custom racetrack has been created using Unity cube primitives to provide a 
virtual racing environment. Numbers have been incorporated onto the blocks in 
virtual track. We imported these from SketchFab. 
 Virtual Button: 
A transparent virtual button linked to an image target has been implemented to 
determine the number of steps the virtual object should move. A plane matching 
the size of the virtual button has been attached to it for visibility. The button 
generates a random number between 1 and 6.            
Real Objects and Image Targets: 
 A real-world image target featuring a race game cartoon picture. 
 Three image targets for three virtual buttons. 
 Real obstacle 
Interactions: 
 Destination Target and Virtual Object Interaction: 
Interaction between the destination target and virtual objects has been 
implemented using Unity animation. The virtual object rotates when closer to 
the destination. 
 Real Obstacle and Virtual Player Interaction: 
Interaction between the real obstacle and virtual objects has been implemented 
using Unity animation. The virtual object rotates when closer to the real obstacle. 
Code Structure: 
Scripts: 
 Virtual button script for generating a random number: 
A script has been attached to the button so that the button responds to 
obstructions within the phone's camera view, simulating a physical button press. 
A TextMesh object displays the generated random number between 1 and 6. 
 Script to move the player according to the button pressed: 
A script has been attached to an empty GameObject which detects the button 
press using camera obstruction. Whenever the button is pressed, the player is 
moved forward by one unit by changing it’s transformed. 
 Animation script for virtual real interaction: 
A script has been attached which calculates the distance between the virtual 
object and the real target. When they are close, the virtual object animation is 
triggered. 
YouTube Link: 
https://www.youtube.com/watch?v=0GYHLof4GKY 