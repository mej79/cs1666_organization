# Team 1 Markdown

## Team Members
* Physics sub-team
	* Milo Davis
		* Pitt ID: mcd66
		* GitHuber username: minnon
		* Personal fork: https://github.com/minnon/Team-1
	* Andrew Welby
		* Pitt ID: apw50
		* GitHuber username: apw50
	* Ken Lin
		* Pitt ID: kel117
		* GitHuber username: kel243
	* Linghai Wang
		* Pitt ID: liw82
		* GitHuber username: nxdens
* Procedural generation sub-team
	* Pedro Pallares
		* Pitt ID: pep24
		* GitHuber username: ppallares
	* Keith Stebler
		* Pitt ID: kcs66
		* GitHuber username: KCS66
	* Peter O'Hara
		* Pitt ID: pjo13
		* GitHuber username: pjo13
* AI sub-team
	* Evan Stephenson
		* Pitt ID: evs25
		* GitHuber username: EvanMStep
	* Gareth Chapman
		* Pitt ID: gjc26
		* GitHuber username: gjchapmn
	* Jonathan Zhang
		* Pitt ID: jcz18
		* GitHuber username: jcz18
	* Michael Spila
		* Pitt ID: mrs185
		* GitHuber username: MichaelSpila97
## Game Description

Our game will be a top-down shooter with strategy elements. With space as the setting, the player will spawn in 1 of the 7 procedually generated hexagonal zones that comprise the game map. As a spaceship that can be controlled with the keyboard, the player will be tasked with shooting AI enemies to clear them out of and therefore gain control of each zone. The more zones controlled by the player, the more AI allies the player can recruit.


## Specific Milestones

* World Objects (large to small): Stars, black holes, planets, asteroids, meteoroids 
* Unit Objects (small to large): Fighter class ship, hero class ship, cruiser class ship, captial class ship
* Objects all exist on same plane and can collide with each other
* Free roam throughout the map's 7 zones
* Credits increment at regular intervals with the amount depending on controlled zones and the objects in said zone
* UI for trading credits for ally units or repairs for player's ship
* Lose when player's ship is destroyed, win when every zone is controlled

## Advanced topics

* Physics
	* Gravity accurately simulated (but with exaggerated scale) for all objects	
	* Newton's laws of motion apply such that objects
* Procedural generation
	* Each zone dynamically generated as a solar system with varying objects and conditions
	* Unique hyperspace maze for the player to traverse generated when the moving between zone
* AI
	* Allies and enemies avoid collisions and friendly fire
	* Allies passively follow player and can be given basic orders (go to point, attack target)
	* Enemies build ships and attack player zones that are adjacent to theirs
