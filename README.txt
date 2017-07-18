Welcome to Conq! The historical strategy game.
Needs: JAVA 8

The goal of the game is to get the most food, 
but you also get bonus points for taking enemy capitals, 
getting the most gold income and getting the most land area.

Basics:
To get around, enter your choice on the keyboard and then press enter.

There are three types of tiles in the game: land, sea, and coastal. 
Land is represented with a black background.
Sea is represented with a blue '=' with a blue background.
Coast is represented with a lowercase letter with a half black/half cyan background. Navies can go through coastal tiles.

The red and white X on the player's map is the spot currently selected. Use wasd to move it around. 
Information about the tile it is over is displayed on the right.

Game play:

Set up:
______________________________________
first you will need enter a savefile name for your game, every time you quit the game, the game will be saved this file name.
Next, you will to select what loction you want to play in.
Enter z to go to the previous map and x to go to the next map, press y to select the map.
Next you will select the year you want to start in, again, use z, x, and y to select it.
Next you will enter the number of human players you want to play with. The rest of the nations will use AI players.
For every player, they will select their country with the z, x, and y keys. The selected country will be highlighted in red on the map.
No two people can play the same country.

Next you will need to select the number of turns the game will be.
Once the number of turns is up, points will be counted and winners determined.

Next you will need to select the aggressiveness of the AI players.
The aggressiveness is the probability that they attack a weak tile.
0% means they will never attack another nation.
100% will mean that they will always attack if the odds are in their favor.
You can also choose 'r' instead for a random distribution of aggressivness from 0% to 100%.
Press 'y' when you are satisfied.

Then everyone will select a capital in their own land.
This capital should be placed in a safe place since you will lose points if someone else takes it.

Now players will each have options to do on their turn.
After they have done everything they want to do, they will end their turn by pressing z.

Let's look at the options players have in deeper detail.

a-look around:
________________________
This mode allows you to look around and see what the map is like. 
It will tell you:
	- the type of the selected tile,
	- The owner if there is one,
	-any navies that are present,
	-any buildings that are present (*(capital), #(farm), ^(Mine), @(Fort))

There are also different modes:
	-mode 0 is the normal display mode. It tells the player what land every nation owns. 
	 The territory is marked with a colored letter denoting which nation it belongs to.
	 Grey X's mean it is uncontrolled.
	-mode 1 is the building mode. If there is no building in the tile, it will display a '-'.
	 If there is at least one building, it will show the first building built there colored in the owner's color.
	-mode 2 is the military mode. If there is newly gained territory this turn, it will show up with a colored '+'.

	
b-build:
________________________
This mode allows you to build things in your nation. Make sure you have enough gold so you can build.
You can build:
	-Farms (#) They add food to your pool every turn.
	-Mines (^) They add gold to your pool every turn.
	-Forts (@) They add military units (mil) to your pool every turn. They also allow building of navies in adjacent
	sea tiles. They also give a defensive advantage when being attacked in that tile.
	-Navies (-) These can be built in sea tiles next to your forts. These can move around and attack nearby tiles.

t- trade:
________________________
This mode allows you to make deals with other nations. This might look complicated, but it is simple.
To make a trade:
	1-hover over the nation you want to trade with.
	2-select what you want to be trading with the format [letter][amount].
	  For example: r10 would set player A's contribution to the trade to 10 food per turn.
	               n30 would set player B's contribution to the trade to 30 military units (mil) per turn.
	3-select how long you want the trade to happen with the format g[# of turns].
	  For example: g3 would set the trade to end in three turns.
	4-both players will need to sign the agreement in order for it to take place.

Note: A player can't make a trade that takes away more than they can give.

c-conquer:
________________________
This mode allows you to use your military units (mil) to aquire territory. 
Select a tile adjacent to your territory you started with that turn or adjacent to one of your navies. 
The total mil for the two sides will be shown. The attacker can attack by entering the 'a' key as many
times as they want until the defender retreats or the attacker retreats.

n-move navies:
________________________
The mode allows you to move your navies. Select a navy by hovering over the navy and entering 'y'. 
The places it is able to sail to is highlighted. Select a spot again with the 'y' key. It will move
and then you will need to wait until next turn to move or attack from it.



END OF GAME:
________________________
The nation with the most points wins. The points are calculated as follows:
	-the amount of food owned by the nation,
	-plus any bonus points added by taking or losing capitals 
	 (20 points per taken capital, -20 points if you lost your capital)
	-plus 50 points to the nation with the highest gold income
	-plus 50 points to the nation with the largest land area.


Acknowledgements:
________________________
Thanks to GeaCron.com for the historical information used in the creation of the maps in this game.
http://geacron.com/home-en/
	
