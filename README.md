#Joselin Weisz - Adventure Game
#CSS 225 Final Project
#Story follows a hero who wakes up in a mysterious city, unable to leave certain blocked off areas. The hero has to search the city blocks that are available, battle monsters until they find the evil mastermind and defeat them to leave and finsih the game. 
#To play the game, user needs the main.py file, battle_module, and search_module, in addition, the #chapters should be in a subdirectory within the game folder. 
#open main.py to play. 
CSS 225 Final Project - Adventure Game 
Joselin Weisz 
National Louis University 
3/20/2025
========================================


#Where the code is hosted:
-------------------------

This game can be found on GitHub and pythonanywhere.com 

External services (if there are any)
No external services are needed, aside from a Python interpreter

#Languages and technologies:
-------------------------
This game is written in programming language Python

System requirements and supported applications
It runs best on a laptop or desktop, with Windows or Apple OS. Not recommended for a mobile device. 

#Coding naming conventions:
-------------------------
I didn't use any specific code naming conventions. My goal was only to make things as concise, yet detailed, as possible. I wanted all objects to be distinct from one another, while being as short as possible. I felt the game was already dialog heavy, so I wanted the names to be very short. 

#How to run build deploy the program:
------------------------------------

The game is structured like this:
text_game/
├── main.py
├── battle_module.py
├── search_module.py
├── chapters/
    ├── chapter1.py
    ├── chapter2.py
    ├── chapter3.py
    ├── chapter4.py
    ├── chapter5.py
    ├── chapter6.py
    ├── __init__.py


To play this game, open main.py in a Python interpreter or run it from the command prompt using python main.py. 

#An overview of the architecture:
-------------------------------

The game's architecture can be broken down into the modules I used to make it functional. two core modules (search_module.py and battle_module.py) were frequently used, so they were organized as separate modules.

The search module allowed the player to search the city-scape in 4 directions with different outcomes. 
The battle module was used the most, and it simulated a fight with various monsters found in the game. 
The game is supposed to go through a set of events in each chapter, so most chapters include one or both modules. 
I needed to ensure that the player worked through the requirements of each chapter in order, so the chapter's themselves also became modules. 
main.py ensures progression by restricting access to the next chapter until the previous one is completed.

#How to start the program (start the game)::
-------------------------------------------

To play this game, open main.py in a Python interpreter or run it from the command prompt using python main.py.. 


