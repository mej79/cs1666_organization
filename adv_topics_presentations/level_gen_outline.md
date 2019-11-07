# Procedural Level Generation Advanced Topic Presentations

## Presentation 1 (10/23):

-Start off explaining what random level generation is
-Explain the game design benefits of it
-People love adventure and the unexpected
-Replayability
-Explain the difference of random level gen from just simply using random in different spots
-Explain the difficulty of random level generation at an advanced level
-Run through and load up some examples of random level generation
-Roguelike Games:
  -Binding of Isaac: simple example
  -Dwarf Fortress (Farnan will like this example)
-Map Build Games
  -Minecraft
  -Terraria
-No Man’s Sky: https://nomanssky.fandom.com/wiki/Procedural_generation
-Run through some beginner level random generation algorithms
-Maze Generation
-Show the class how the code works, run through it
-Can generate a model of a maze for the class to see
https://www.youtube.com/watch?v=6kv5HKPB1XU
-Room Generation
-Show small video about how rooms are generated in action, talking over the video about what is going on
https://www.gamasutra.com/blogs/AAdonaac/20150903/252889/Procedural_Dungeon_Generation_Algorithm.php


## Prsentation 2 (11/6):
*Begin by shortly explaining our group's game and how procedural level generation will be used in Galaxy and Maze Generation 
*Galaxy Generation
  *Explain why this problem can be/needs to be solved with Procedural Generation
  *Show algorithms that can solve this problem
  *Poisson Disc Sampling Algorithm
    *What does it do and how does it work?
    *How does it relate back to galaxy generation?
    *Pros and Cons
    *Why didn't we pick this to solve our problem?
  *Random Number Generators
    *What do they do and how do they work?
    *Different types
    *Which one should we use for our case?
    *Limitations?
*Maze Generation
  *What defines a good maze? a bad maze?
  *What parameters do we have to account for?
  *What makes an algorithm good for maze generation?
  *Wilson's Algorithm
    *Deep dive into how it works (complexity, runtime, etc. )
    *Why it's good for maze generation
    *Why we chose not to implement it
  *Eller's Algorithm
    *Deep Dive into how it works
    *Advantages and Disadvantages of Eller's Algorithm, including implementation challenges.
    *Why we chose to implement this over other algorithms 



## Presentation 3 (11/20):
*Begin by explaining the various ways that procedural generation is to be used in our game
  *generating random caves
  *generating obstacles
  *generating enemies
  *what factors did we have to take into account for generating each of these entities?
*discuss the obstacles that we overcame and how we solved these problems
  *different procedures we had to create the cave and why we chose what we did
  *pros and cons of the options we had
  *ensuring a cave was traversible
  *creating a scaling difficulty
    *scaling of turrets, powerups, missiles
*deep dive into our cave algorithm
  *show the class the code
  *demo the game to show it in action
