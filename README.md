# CG-Assignment
This is the repository for my CG Mini Project, "Visualization of Cellular Automata"

Cellular automata are a way of modelling pixels on screen.
It can form complex patterns and animations from some simple rules, through various iterations.
It is used to model systems in biology, physics, generate random numbers for cryptography, etc.
One subpart of this is an algorithm called Conway’s game of life. 
An initial configuration is created using pixels, and its evolution is observed.
Conway’s game of life has simple rules that govern the status of an organism, in this case a pixel on screen. 
It has rules that create and destroy pixels, in a manner that leads to interesting patterns being formed.
We implement this concept as an animation using OpenGL. 


FEATURES IMPLEMENTED: 
 
 Initialize random state 
 Automatically run next iteration (using timer function) 
 Add concept of old age, as a new rule that can be seen by changing colors o The maximum age that an organism can be alive is also set, after which it dies. 
 Animation (using double buffering mode) o To increase/decrease animation speed the time parameter can be modified 
 User interactivity (using keyboard and mouse) 
  o Keyboard: Press 1 to play animation, Press 2 to pause, Press 3 to reset board to blank state 
  o Mouse: Left click/ drag to add pixels on screen (in pause mode) 
 
This project is designed using some of the OpenGL inbuilt functions and some user defined functions. 
