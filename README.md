# Hi! I'm Dawin Yurtseven

Hello there! My name is Dawin Yurtseven, an Informatics: Game Engineering student at the Technical University of Munich. I'm an aspiring game developer that loves story driven games the most. I'm looking forward to work together with passionate people. 

# Current Projects
I'm working on multiple projects. Although I haven't worked on them for a longer time, I started to work on them again as of lately. These projects are not completed yet but here is a short description about them as well as what has been implemented and needs to be implemented.

## ThunderPunk
ThunderPunk is supposed to be a fast-paced jump-n'-run that uses its physics-based controller for more complex movement.

Things that have been implemented so far:
- Movement along the x and y axis
- Camera control with Cinemachine 
- jump and dashes
- custom gravity that works on any object that has the "CurvedGround" tag
- a camera Focus for the LockDash function

Things that are planned to be implemented soon:
- [ ] LockDash function to reach further objects directly
- [ ] Spline System for custom paths that the player can walk, grind and jump on
- [ ] Grinding system for defined path movement
- [ ] custom character model with animations
- [ ] enemy who have limited reactions to the player


## Castle-In-The-Sky
Castle in the Sky is supposed to be a mobile story game which consists of a turn-based battle system and a visual novel like story before and after a fight. 

Things that have been implemented so far:
- Character Information for battles as well as their possible actions and reactions to enemy actions
- Battle system which goes the certain order of "player state" - "enemy state" until either side is dead
- simple UI placeholder that is responsive to a players possible actions
- movement towards target after certain actions via interpolation of character and target positions

Things that are planned to be implemented soon:
- [ ] Enemy Ai types for enemies
- [ ] proper animation and waiting time for custom animations
- [ ] visual novel system with corresponding ui
- [ ] reactive camera for battleflow 
- [ ] more dynamic UI which takes up less space


## System Generator Plug in for Unity
This project is currently about a Turn Based Combat system generator that lets people that want to create a specified Turn Based Combat system without programming. The generated files will be explained further with docs but the basic idea about this plug-in was meant for artist to work on a game alone without needing to programming such a system themselves. If everything for this system has been implemented properly, thinking about other system generators is more than a possibility.

Things that have been implemented so far:
- stat list that lets user create a stat with either an int value or float value
- condition list that lets the user specify a condition that affects a specified stat in a custom way

Things that will be implemented soon: 
- [ ] an Mandatory Animation List for each character
- [ ] a list of actions with each customizable that can affect specific targets
- [ ] a state list of the battle gameflow that is set in order
- [ ] customizable enemy ai that works by giving the action it has and conditions it has to be met for the activation of that action. this is a crude idea of a behaviour tree
- [ ] stage position for the position of characters on the battle field
- [ ] parser that will convert this information to two c# files that are ready to use

> **Note** that this project is made with the idea to faster create turn based combats and make it easier to change the game rules without having to code. it is momentarily only a test project for tool programming and to get familiar with the UXML and USS languages for the Unity game engine.

# How to reach me
if you like to contact me, you can do so via [LinkedIn](https://www.linkedin.com/in/dawin-yurtseven-1b3097265/) ,[Twitter](https://twitter.com/dawinyurtseven) and per Email: dawinyurtseven@gmail.com
