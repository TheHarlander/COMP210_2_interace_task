# COMP210_2_interace_task

###State and justify the game that will be the basis for your interface
The game I will be making a VR user interface for is my comp230 group project, this game is primarily a rowing simulator with mini games and mysterious things happening. For the main mini game i am working on is where cats fall from the sky and come towards you and try and hurt you, your goal is to hit them away. 



###Assess VR/AR market
The Vr and AR market is ever expanding and progressing exceedingly. There is a lot of competition between which one is better, Virtual reality will be for the living room enclosed space where the player wants to explore fantasy worlds. Whereas the augmented reality will be for real life augmentin where the player can go anywhere with their phone. 
The haptic technology market is expected to be valued at USD 19.55 Billion by 2022, and in 2015 tactile haptic feedback was said to be the largest market. This shows promise for implemention in the games industry to use this huge market to their advantage.



###Outline an initial design in detail
The initial design is somewhat subject to change as the game is made and new minigames require additional information on screen but for the initial base ui there are a few key components. The first is a real life stick or pole of some kind that the user holds in real life that represents the oar in game which the player swings in game, with this I could have a device of some kind that when you swing and hit something it vibrates. Another haptic I could use is a fan and some salt water or river smelling water to allow the player to feel they are heading down a lake. 
the in game UI will only have a couple components. The first is the  health bar at the top of the screen and I would also put in a timer in the top right to show how long the player has left.
For the staff I will be most likely be using Arduino to simulate the hitting of the cats. for the smell and wind a simple fan and water collected from the sea should suffice. For the health bar and timer I will be using UDK's UMG.
![alt tag](https://github.com/TheHarlander/COMP210_2_interace_task/blob/master/Part-A/basicUIDesign.png?raw=true)


###Production
The first idea that stuck was the idea of using the vr controllers to row in this rowing simulator. With most kinds of small boats oars are used to move the boat along the water so this was going to be the basis of my design. After moving forward into the game project I was set on making the controller for the right handed vive controller which would be used to hit away the enemies in the game. For this prototype I made it our of cardboard so I could actually test out the controller with the vive controller, the pole was unable to fit nicely due to the trigger. To get around this I cut a small hole in the side so it would fit snuggly, to stop the user from pushing the controller too far up or misusing the hole I put an extruding cardboard and tape to remind the user to stop at this point.
The next problem was that the controller felt loose and could easily fall off the oar at anytime, I got around this by adding a strap of sorts for the vive controller to the oar.I then drew the logo on so that the user could see where to put it over.
[image]

###Haptics
I wanted the user to enjoy different types of haptics throughout their experience of playing the game. Firstly I thought of an unusual method of using a fan placed in front of the player to simulate the feel of them actually moving speedly across the water. The sensation of the cool air brushing past their skin would hopefully immerse them deeper. But then I realised I could put some scented water in front of the fan, not so that it would blow water at them but to blow the smell of lake/river water hitting another sense to immerse the player. An unexpected haptic happened during testing of the oar, not only does the weight of the oar itself give the feel of you actually holding something but when you were to swing the oar to hit the enemies in game the wind resistence allowed it to give the player the sense of actually swinging it in game. The final haptic I wanted to add but was unable as the parts for it that were being supplied by the university never arrived, was vibration. Although the Vive controllers come with a vibration feature integrated, I wanted to do it myself and give a greater vibration than the one supplied. 
Below is a picture of the arduino circuit I was going to use if the parts came, I went online and used an emulator that allowed me to create the board virtually.
[image]
In theory what I want to happen is for the vibration to happen at the time of impact between the oar and the cat. Playing around with the emulator I was able to get it to vibrate on and off every second with a simple motor pin high, motor pin low loop. To achieve it in my game I would do something along the lines of when a cat is destroyed by the oar it sends a letter to the arduino that then signals the motor pin to turn to high then off again.


####references
http://www.marketsandmarkets.com/PressReleases/haptic-technology.asp

https://www.arduino.cc/

https://docs.unrealengine.com/latest/INT/Engine/UMG/QuickStart/index.html 

http://www.digi-capital.com/news/2015/04/augmentedvirtual-reality-to-hit-150-billion-disrupting-mobile-by-2020/#.WAIVUegrKhc 
