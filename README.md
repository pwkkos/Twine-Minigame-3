# Twine Minigame 3

## Devlog

In the beginning of my game, I used the integer variable, "set $humanity to 0", in order to keep track of how much humanity the player receives throughout the game. When the player reaches the "choices" passage, they have the ability to choose between different options that link them to either the "gain" or "lose" passage. The "gain" and "lose" passages first add/subtract a number from "$humanity" by using a arithmetic expression such as "set $humanity to $humanity + 1" and then displays the number of humanity points the player now has with the "$humanity" variable. In addition, I also used the string variable, "$name", with a textbox macro in order for the player to be able to give themselves a name that would appear in game. 



I used if and else macros in my game to first check the number of humanity points the player has and to then determine what text, images, or options will be displayed to them. For example, if the player's "$humanity" is >=5, then an image and new text with the option to move on will appear. However, if the player's "$humanity" is not >=5, no new text or image will appear, instead, the player will need to keep gaining more humanity points until they reach the goal number. I chose to use if macros instead of making new passages because they allow me to change what is displayed to the player within the same passage, saving me from the hassle of creating multiple new passages and making it easier for me to navigate my game.

