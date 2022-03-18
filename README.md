# walking_simulators
lab4: tasks 5 and 6
***
Task 5<br>
The main goal was to create  a bunch of classes to be able to run the already existing file. There are five classes: Room, Character, Enemy(Character), Ally(Character), Item.  
According to the plot, you have to go through 3 rooms, connected with each other, with 2 enemies. For beating a monster, you have to use its specific item of weakness. The end of the game comes when 2 monsters are defeated or the player is dead.<br>
Commands to go through the game plot:<br>
*talk* - a small message from the character you want to talk with<br>
*fight* - you have to choose what you will fight with next<br>
*take* - if there’s an item, put it to your backpack<br>
*north/south/east/west* - to go through the locations<br>

Task 6<br>
I tried to make the game from task 5 a little bit more difficult. Here, you are the adventurer, who wanders in the deep forest.<br>
Player\`s initial  HP is 4. Five locations are connected with each other. There are 4 enemies with specific item of weakness, if you choose the wrong item you loose 1 from your HP, else you receive a piece of puzzle. Enemies can drop interesting things, as well as you can receive them from your allies.<br>
If all enemies are defeated, you receive a puzzle with some strange text on it. If your HP is bigger than 2, the ending monster appears, else the game ends.<br>
After defeating the main enemy, you win the game and can continue your amazing adventures!<br>
Classes: Stage, Character, Enemy(Character), Ally(Character), Item. <br>
Commands to go through the game plot:<br>
*talk* - a small message from the character you want to talk with<br>
*fight* - you have to choose what you will fight with next<br>
*take* - if there’s an item, put it to your backpack<br>
*north/south/east/west* - to go through the locations<br>
