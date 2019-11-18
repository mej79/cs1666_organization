# Advanced Topic Presentations

## Presentation 1 (10/28):

  * Briefly mention some general real world applications with AI and then segue into game AI
  * Introduce the basic goals of video game AI:
      * What do we do to create a fun AI to play with?
      * Goal to make AI appear human controlled?
        * Make the AI react as a human would based on situation or act in the most beneficial way to its goal
      * Cheating AI a good idea?
  * Dive a bit deeper into Game AI
    * Dynamic AI through changes in state and behavior  
      * Finite State Machines
      * State Transition Tables
    * AI pathfinding
      * Obstacle avoidance, pursuit, dodging, etc
      * Detection boxes
        * Invisible collisions with objects will help to inform the AI on what to do next.
    * Using Decision Trees for NPCs
  * Possible ideas, solutions, and expected problems to our implementation
    * Using graphs to navigate the game world
      * This could be especially effective when the environment is effectively generated once


## Prsentation 2 (11/11):

  * Continuation of explaining beginner concepts that first group presents on
      * Ex. How AI is needed for video games to be fun/interactive 
  * Learning
      * Different forms of learning
          * Intra-Behavior, Inter-Behavior
      * Action Prediction
          * N-grams?
      * Decision learning
  * AI in our game
      * Explain how we got the enemy plane to follow at first
      * Explain why traditional path-finding algorithms (i.e. the ones involving Dijkstra’s or A* algorithm) aren’t the best choice for path-finding for the enemy plane
          * Introduce risk scoring algorithm
  * Future Plans for AI in our game
      * Possible enhancements to risk scoring algorithm
      * Can explain some concepts that are in the book provided in the AI sub chat

## Presentation 3 (12/2):

* A* vs Theta* algorithm
  * Algorithm In Theory
    * Reminder of what A* algorithm is from the last AI presentation
    * Go over theta* algorithm and its relationship to A*
       * Contrast the two algorithms and what Theta * adds to A*
       * Go through a simple example of pathing using theta*
  * Talk about navigational mesh component of Theta *
    * Initial mesh construction
    * How we use the mesh
    * How the mesh is made
    * Mesh improvements
  * AIShip radar (Will probably go between Implementation and Ship states)
    * Avoiding friendly fire
    * Interaction with mesh
* Implementation:
  * What is the perfect pathfinding implementation?
    * One that finds the absolute minimum valid path in the shortest amount of time
  * Challenges:
    * Dynamic world
    * Large Search Space
    * Very small Deadline to return paths for all AI ships
  * How we will Evaluate an implementation?
    * Time it takes to return path
    * How accurate is the path
  * Goes over three major implementation of pathfinding over the course of the semester
    * Implementation 1: Naive Pathfinding
    * Implementation 2: Open set is the C standard library p_queue
    * Implementation 3: Open set is Custom p_queue with indirection
  * Can we do more to improve the runtime?
    * Evaluation of data structures
        * Multidimensional Array
        * C standard library map and set
        * C standard library unordered map and set
            * Discuss Cantor Hash
     * Does changing any of our data structure have a significant effect on runtime.  
     * Calculating entire path vs Segmenting path
 * AI/Ship states
   * Short intro to Turing machines
     * Relate to finite state machines, why model as a Turing Machine
     * Discuss states, transitions, “tape” for an abstract turing machine
     * Explain usage of 2 tapes: distinct alphabets 
   * Modeling AI to function like a TM 
      * Model various AI ship states, actions, transitions 
          * Relate usage of 2 tape to input/output values
          * Discretize “goals” into specific actions, then into a TM alphabet.
          * Provide relevant diagrams showcasing states relevant to game
       * Give a high level/abstract explanation of the process ships make decisions
          * Mention the functions that ships use for decision making
          * Explain why AI ships have different interactions compared to player
    * Differences between enemy and allied AI, both representation and codewise

