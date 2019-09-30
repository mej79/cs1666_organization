# CS1666 Team EXAMPLE

## Team Members
* AI Generation Subteam
	* Shawn Blake
		* Pitt ID: smb255
		* Githuber username: smb255
		* Personal fork URL: 
	* Erick Brindock
		* Pitt ID: esb43
		* Githuber username: ErickBrindock
		* Personal fork URL: [https://github.com/ErickBrindock/MerderMisstery](https://github.com/ErickBrindock/MerderMisstery)
	* Jiang Bian
		* Pitt ID: jib38
		* Githuber username: 54m43lJ
		* Personal fork URL: 
* Interactive Simulation Subteam
	* Griffin Lynch
		* Pitt ID: gtl6
		* GitHuber username: gtl6
		* Personal fork URL: 
	* Darpun Kohli
		* Pitt ID: dak190
		* GitHuber username: dkdude98
		* Personal fork URL: 
	* Max Jahnke
		* Pitt ID: mej79
		* GitHuber username: mej79
		* Personal fork URL: 
	* Graham Zug
		* Pitt ID: gvz3
		* GitHuber username: GrahamZugPitt
		* Personal fork URL: 
* Networking Subteam
	* Coleton Bryan
		* Pitt ID: ctb36
		* GitHuber username: ctb36
		* Personal fork URL: 
	* (John) Colton Bove
		* Pitt ID: jcb164
		* GitHuber username: ColtonBove
		* Personal fork URL: 
	* Dorian Vesely
		* Pitt ID: dpv6
		* GitHuber username: dvesely40
		* Personal fork URL: 
	* Alex Thune
		* Pitt ID: abt31
		* GitHuber username: abt31
		* Personal fork URL: 

## Game Description

For our game, we are building a procedurally generated murder mystery. The player will be able to
move around a town, interacting with static NPC's to discover the web of relationships that caused
the death of one of the town's beloved citizens. At the endgame, the player will be placed in a 
'trial' scenario, where they will be asked to accuse one of the NPC's of murder and provide evidence
as to why they think that NPC murdered our vic.

Less gameplay oriented - before the player begins their interaction, the game will generate a scenario
based on a provided seed (or picking one of its own). Based on that, the game will create NPC's with 
distinct personalities that will, once the simulation phase begins, interact in a specified way. The simulation 
will continue until, in due course, one NPC chooses to murder another.


## General Milestones

* The Player will be able to walk around the game map
* The Player will be able to access an inventory, which will be populated by items they pick up
* The Player will be able to save and load their game in progress
* The Map will be populated by an as yet undetermined number of NPCs (to be specified ASAP)
* The Player will be able to interact with any NPC through a conversation system that will be the same for every NPC
* The Player will be able to interact with items in the game world (which will likely be very limited in number, but also needs to be decided ASAP)

## Advanced topics

* AI Generation 
	* Develop a model of Human Behavior that lends itself well to a murder mystery
	* Develop any intermediary models required to promote interaction (e.g. News events of the form "Charlie was rude to Sarah")
	* Develop an interface with the ISD team for those models
	* Implement a system that allows procedural generation and dynamic updating for NPC behavior and information models
	* Create a system that allows procedural generation of visual representations of said NPCs 
	* Stretch goal: Update the above visual system such that certain visual cues are linked to underlying emotional variables
* Interactive System Design
	* Work with the AI team to develop human behavior and intermediary interfaces to simulate interaction 
	* Decide on a range of interactions that the AI may choose to take, and goals that can be used to cause the AI to attempt to take them
		* This is akin to causing an AI to go get food by making them hungry every day at a specific time
	* Create a model of the in-game map that allows AI that are in the same "room" to interact with one another (and those that aren't to not)
	* Implement a "simulator" that will give the NPC's goals and then allow those NPC's to complete them however they want
		* Side note: we'll have to have discussions as to how to achieve the "however they want"
* Network 
	* Create a web server capable of receiving and sending information packets
	* Allow connections across separate networks
	* Create server-side user profiles
	* Add a friend system for the profiles 
	* Add a chat system between profiles 
	* Add a central hub where game seeds may be shared and commented on 
		* This one will warrant a discussion as to how we want to "share" seeds, and whether we want to limit the pool of possible seeds.
