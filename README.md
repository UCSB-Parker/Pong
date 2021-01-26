# VolleyPong
This project replicates Pong, the table tennis–themed arcade video game originally released by Atari in 1972. The theme for this
game is singles volleyball played between two players, one blue player and one red player. The colors signify that the two players are opponents.
One of the players is controlled by the user while the other user is AI 
controlled. The challenge in implementing an AI user is the balance between making the AI user skilled enough to be a challenge and easy enough to be beatable. 
The object of the game is to score 5 points (win by 2). The scripts from this game are based on the scripts from the pong tutorial ( i.e. https://www.awesomeinc.org/tutorials/unity-pong/) 
and various Unity and C# resource pages ( e.g. https://docs.unity3d.com/ScriptReference/Vector3.html) 
and are modified according to the requirements and specifications needed for this version of Pong. The mechanics of the game are 
similar to the original Pong video game. That is, the game consists of two paddles and one ball. 
The game is single player, where one user controls a single paddle and is playing against an AI with 
one level of difficulty. The game has a restart button that resets the scores to zero, and resets the paddles and ball to its original position. 
Certain mechanics of the game have been updated from the original version
of Pong. Firstly, the user paddle has the option to move in the x and y directions rather than soley the 
x direction. This reflects the mechanics of volleyball where the player is free to move around the court. Secondly,  the AI paddle mimics the balls motion but is 
constrained to moving in the y-direction. The design includes an 
updated background volleyball court, volleyball, judge's chair, spectators, scoreboard, and win message. Each of the features add a volleyball quality to Pong. Scalling the scoreboard, reset button, and win message 
based on the dimensions of the monitor that the game was being played on was challenging. The dimensions must be based on values relative to the size 
of the string, while hard coding the values can lead to an unplayable game. Effectively using the Unity game engine to mimic certain aspects of physical reality
while ignoreing others is challening. For instance, the speed, radius, and mass of the ball all needed be changed relative to each other in order to provide the most re
It was a challenge to find the  appropriate 
vector images for the objects needed to reflect the theme of the game because many images exist behind a paywall. 





