
As a young adventurer, you seek gold and glory in the darkest dungeons there are.
You have initial health 100 and initial coins 0. You will be given a string, representing the dungeons rooms. Each room is separated with '|' (vertical bar): "room1|room2|room3…"

Each room contains item or a monster and a number, separated by space. ("item/monster number")

•	If the first part is "potion": you are healed with the number in the second part. But your health cannot exceed your initial health (100). Print: "You healed for {0} hp."
After that, print your current health: "Current health: {0} hp."

•	If the first part is "chest": You've found some coins, the number in the second part. Print: "You found {0} coins."

•	In any other case you are facing a monster, you are going to fight. 

The second part of the room, contains the attack of the monster. You should remove the monster's attack from your health. 

o	If you are not dead (health <= 0) you've slain the monster, and you should print ("You slayed {monster}.")

o	If you've died, print "You died! Killed by {monster}." and your quest is over. 
Print the best room you`ve manage to reach: "Best room: {room}".

If you managed to go through all the rooms in the dungeon, print on the next three lines: 
"You've made it!", "Coins: {coins}", "Health: {health}".

Input
You receive a string, representing the dungeons rooms, separated with '|' (vertical bar): "room1|room2|room3…".

Output
Print the corresponding messages, described above.



Input
rat 10|bat 20|potion 10|rat 10|chest 100|boss 70|chest 1000


Output
You slayed rat.
You slayed bat.
You healed for 10 hp.
Current health: 80 hp.
You slayed rat.
You found 100 coins.
You died! Killed by boss.
Best room: 6
