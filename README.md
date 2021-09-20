# Zooba-AI-Auto-Play
Mobile Game Scripts

Zooba is a mobile game with Battle royale game rules and MOBA style. i.e. you play LOL with PUBG rules.

To obtain high scores and reward, you need to play all the characters to some target levels every two weeks, which may not be fun when you are playing with some disliked characters.

This Zooba auto-play program can help!

You can train your model to be a escaping style player easily, which can help you get good rank in most of the auto-play games.
Aother better way is to use this model to do auto attach, auto start and exit, and randomly search around, staying in the fire circle. Then use another object detection (Google object detection API) program( will upload later) or Open CV template matching to detect other players, guards, weapons and Blood pack.This can be done easily by detecting the Health bar of other players and guards with a very high precision, and then weapons(only 4 types) and Blood pack(1 type). And escape from other players(or with higher ranks), while approching weapons, guards and aids.


I use BlueStacks5 to play Zooba at Windows PC. 

How to use:

1. Place the BlueStacks on the left top corner of your desktop, and run data_acquisition.ipynb when playing Zooba game.You can also train the model to learn to click start and exit between games. The start and exit button can be clicked with Spacebar.
2. run train_model.ipynb to train your model.
3. run auto_play.ipynb when you are in the game, and the model will play Zooba automatically.

Good Luck and Enjoy!
