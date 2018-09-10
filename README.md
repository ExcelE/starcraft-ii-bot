# starcraft-ii-bot
This project aims to create a StarCraft II bot with Deep Learning. 

What makes this really cool is that this was a collaboration between DeepMind and Blizzard. They made the APIs available to allow hobbyists like you and me to play around and build a bot.
The best part? StarCraft II is free to play!

The idea behind the implementation:
In most deep learning implementation for games, Q Learning seems to be the most popular option. It's a great algorithm for ATARI games, with simple mechanics and goal. However, StarCraft II is a different environment. There are numerous variables to keep track of, even variables have variables. What do I mean?

StarCraft II is a Real-time Strategy Game. It gives players the ability to pick and choose units and upgrades provided that the players understand the costs (time and resources). Starting off with limited resources, the players will have to decide the best possible course of action to increase resource acquisition while building an army to either attack or defend. And you can imagine the game state possibilities as the match goes on.

TODO:
* Add the AI
