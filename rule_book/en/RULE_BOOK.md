# Pluvionauts rule book

## Game overview

Explore the sky as an **air balloonist**.
Use your balloon to **tow sky islands** and shape the sky at your advantage in **search of rain**.

Answer to as much **villager requests** as possible to earn their support and be elected the **best pluvionaut** of the country!

## Game setup

[//]: # (<img align="right" width="500" src="./images/setup.svg">)

1. The box of the game serves as the board. Start by removing the **balloon dice**, the 12 **villager request cards**, the 3 **lighthouse buildings**, the 3 **water tower buildings** and the 6 **wall buildings** from the box. 
The 5 **mountain tiles**, the 6 **forest tiles**, the 10 **plain tiles** and the 2 **weather dices** should remain in the box.
2. Now shuffle the box so that each hexagonal tile and the weather dices are placed randomly on the board. Then ensure that each hexagonal tile is correctly placed at the center of a board hexagon and place the box a the center of the table.
3. Each player receives 2 **villager request cards** and places them hidden in front of them. They can look at there own set of cards any time during the game. The remaining **villager request cards** are placed facedown near the board.
4. The first player, chosen at random, takes the **balloon dice**.

![Game setup](./images/setup.svg)
*Diagram of the game, setup for 4 players here.*

## Villager request

The aim of the game is to earn the support of as much villagers as possible by validating **villager requests** to be elected the **best pluvionaut** of the country.
Two different type of **villager request** exists:
* **Weather requests**: villagers require a **specific weather** (rain and no thunder or thunder) on a **given terrain** type (plain, forest or mountain).
* **Region requests**: villagers require a specific **region size** or a specific **number of regions** of a given terrain type (plain, forest or mountain).

Upon **villagers request** validation, a player earns the number of villagers indicated on the top right of the card as support.
Once validated a **villager request** can provide the support of additional villagers if the condition is valid at the end of the game: indicated at the bottom right of the card.

### Weather request

Indicated at the top of the card, a **weather request** requires a certain **weather** (rain or thunder) on a minimum **number** of tiles of given **terrain** type.

The weather is controlled by the weather dice on the board. 
The position of a weather die corresponds to the center of the weather cloud.
* The value of the symbol **drop** corresponds to the **rain distance range**: it is considered raining on all the tiles up to that distance from the weather dice.
* The value of the symbol **bolt** corresponds to the **thunder distance range**:  all the tiles up to that distance from the weather dice are considered in a thunderstorm.
Refer to the **distance rule** to learn how distance is impacted by the terrain.

Note: The maximal range of a **weather dice** is **3**.

### Region request

Indicated at the top of the card, a **region request** requires either:
	- a region of given **terrain** type to be of a minimum **size**
	- a minimum **number** of regions of a given **terrain** type

A **region** corresponds to a set of adjacent tiles (sharing one edge) of the same **terrain** type.

## Distance rules

The same distance system is used to determine the weather range, the maximal balloon driving range and the island towing range (introduced in the next section).

The tile where the dice stands is considered at a distance 0 from the dice independently of the terrain.
The distance of an adjacent tile is however dependant of the **terrain** of that adjacent tile:
* An adjacent **sky tile** is at a distance of **1**.
* An adjacent **plain tile** is also at a distance of **1**.
* An adjacent **forest tile** is at a distance of **2**.
* An adjacent **mountain tile** is at a distance of **3**.

The distance of farther tiles from a die is computed as the smallest distance required to reach that tile.

## Playing the game

A game consists of several rounds that players take one after another in a clockwise direction.
In turn, the player performs the following actions in order:
1. **Balloon deployment:** throw the balloon dice on the board (refer to the **balloon deployment subtleties** section for more details). The position where the dice ended represents where your balloon ended up after deployment. The dice number represents the fuel remaining to continue driving the balloon.
2. **Balloon driving:** move the balloon dice up to a distance of the number indicated on the **balloon dice** (refer to the previous **distance rules**).
If the balloon was driven on an island:
	3. **Island towing:** flip the balloon dice and move that island up to a distance of the new number indicated on the **balloon dice** (refer to the previous **distance rules**). The island towed must be placed on an **sky tile**.
4. The player can then **OPTIONALLY** perform **ONE** of the following actions:
	* **Take a building:** choose and take any available building from the **building pool**.
	* **Place a building:** place one of their buildings on an available spot **adjacent to the balloon dice**. A building must always be adjacent to an island.
	* **Validate a Villager request:** If so, they flip their card so that it is visible by all players **AND** draw another request card.

## Influencing the weather

The weather is initially set randomly, but it may be changed during the game:
* one may knock a **weather dice** by aiming for it during the **balloon deployment**.
* one may change a **weather dice altitude**:
	- if an island is towed under a weather dice sitting on a sky tile, the weather dice increase its value depending on the terrain:
		* **plain**: +1
		* **forest**: +2
		* **mountain**: +3
	- if an island is towed from under a weather dice, the weather dice stays in place but decreases its value in a similar maner.
During elevation changes, the value of the dice is capped by its minimal value (1 = drop symbol) and its maximal value (6 = symbols).
		
Note: be aware that when the **weather dice** ends up near the board boundaries, it becomes much more difficult to influence it by throwing your balloon at it.

## Buildings

Buildings are placed in the rectangular holes in between hexagonal tiles.
A building **has to be placed adjacent to an island**. 
At **any point** in the game, if a building is not adjacent to an island, the building is **destroyed** and placed back in the **building pool**.

Buildings have various effects:
* the *wall* blocks the two adjacent islands from being towed. It blocks as a barrier for **weather**, **balloon driving** and **regions**.
* the *lighthouse* protects the two adjacent tiles from thunder.
* the *water tower* supplies the two adjacent tiles in water. 

Note: as walls block adjacent tiles from being towed, a wall is indestructible. If an island is initially adjacent to a wall or is brought adjacent to a wall, it will be blocked until the end of game.

## End of game

The end of the game is triggered when a player validates **3** **villager request cards**. 
Each **OTHER** player then plays one last turn before the game ends.

Each player then counts all the villagers support accumulated on their validated **villager request cards** (also counting the additional support if that request is valid at the end of the game).
The balloonist with the most medals is elected the best **pluvionaut** of the country!
If there is a tie, the players share the victory.

## Balloon deployment subtleties

* When deploying their balloon, the hand of the player must never hover the board.
* If the **balloon dice** ended in between several tiles, then the player chooses from which of the several tiles to start its **balloon driving**. Similarly, if a **weather dice** ends in between several tiles after a die throw, the current player chooses one of those tiles where to place the **weather dice** on.
* If the **balloon dice** does not end in the board, the deployment is canceled and every weather dice is set back to its initial position and value before the throw. The player then has a unique second chance to deploy its balloon again. It they fail again, they pass over to the next player.
* If a **weather dice** is thrown out of the board, the next player will throw is back in just before its turn.
* A player can not move nor rotate the board before its throw. He can however stand up and turn around the table if necessary.
