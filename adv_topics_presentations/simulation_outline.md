# Simulation Advanced Topic Presentation

## Presentation 1 (10/30):

Simulation Presentation

Team ALPHA



- Griffin: Overview of Simulation in General
  - Granularity of world models
    - Philosophical World Models
    - Physical World Models
  - Simulation Models
    - Deterministic Mathematical Descriptions
    - Agent-Driven Models (decisions made ad hoc)
  - What did we choose?
    - Really a mix of these. Very much a middle ground between Physics and Ontology, and a pseudo-random, agent-driven simulation model.
- Graham: Markov Chains
  - What Markov Chains are
    - A mathematical definition
    - An example
  - Background
    - Some of the fun history behind Markov chains, namely the statistics and the free will vs. law of large numbers
    - Why Markov chains are useful for simulations
  - How to implement Markov chains in a program
    - Implementation of a Markov chain in pseudocode
  - How we used Markov chains
    - Explaining the events in our game, how they are Markov chains, and how we are choosing to implement them
- Max: Abstraction of Personality
  - What is important in people?
    - Different models for personality
    - Extra complexity vs. extra engagement
    - Considerations for gameplay based around variations in personalities
  - Where is the personality displayed?
    - Importance of individual character traits
    - Use of interactions to define people
    - Progression of relationships from one state to the next
    - Concluding event, murder, result of string of incidents
  - Pitfall: Constant reinforcement
    - Could reach a situation where same tendencies are enforced
    - Leads to lack of diversity in interactions
    - Solution: Separate chains of events that link together
      - Prevents constant reinforcement
      - Allows for resets in relationships with some holdover
- Darpun: Constraint Satisfaction
  - Crowd simulations
    - Easy to make NPCs with simple behaviors, but much more challenging to make meaningful interactions in an open world setting.
  - Smart Areas
    - NPCs location carries behavioral information about how they should act.
    - Ex. The NPCs do not know how to behave at a house party, but the house party knows how the NPCs should act.
  - In transition to/from Smart Areas
    - Utilize &quot;situations&quot;
    - Ex. Poor NPCs take on the role of beggars and rich NPCs take on the role of benefactors. When two individuals from both groups intercept, the benefactor gives the beggar money.
  - System Design
    - Process of backtracking search and inference (forward checking)
    - Detailed explanation of the solution

