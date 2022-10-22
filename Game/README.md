# KASPAR
KASPAR game executable using the windows visual studio IDE. The application is made with C/C++ using OpenGL API for rendering the graphics.
The game can be expanded to play with the machine as well as using a NAO robot in order to enhance the interaction with the Ai player. 


## HOW TO CONNECT
The game connects with the Ai module and remote controls via sockets. The sockets used for each connection can be found in the configuration 
panel under `Sockets, Robot connection` , once the game is open. 

###  AI Player module
By default the Ai player server is open so simply executing the Aiplayer.exe file should connect the modules. The enable the AI to play in the actual game
you will need to enable the checkbox under `players, Player Y AI` (important to be that specific checkbox). 

###  Remote controls
Under `Sockets, Server` you need to enable the players remote controls by clicking the checkbox `Enable remote control X` or/and `Y`. A text should appear 
under the checkbox saying that the server is `listening`.
Now you can run the read_console.py (See folder consoles) acordingly. If successful the listening text on the config panel now should say `connected` in green.


## IMPORTANT NOTE!
Only use KASPAR level. Easy, medium and hard levels have been deprecated.
