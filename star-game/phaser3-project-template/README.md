# Star Game using Phaser3



This is a Phaser game written in JavaScript that involves a player character collecting stars while avoiding bombs. The game world consists of platforms that the player can jump on, and the player has basic left-right movement and jumping abilities.

The game is created using the Phaser game engine, which is a popular choice for developing 2D games in JavaScript. The code consists of three main functions: preload(), create(), and update(). The preload() function is used to load the game assets, such as images and spritesheets, while the create() function is used to create the game world and set up the game mechanics. The update() function is called on every frame and is used to update the game state, such as the player's position and velocity.

The game world is created using static platforms, which are defined using the physics engine. The player character and stars are also created using the physics engine, which allows for realistic movement and collision detection. The player character has left-right movement controlled by the arrow keys, and can jump using the up arrow key.

The stars are placed at fixed positions on the platforms and can be collected by the player when they come into contact with them. The score increases by 10 each time a star is collected. When all the stars have been collected, a new batch is generated and a bomb is placed at a random position on the screen.

The player must avoid the bombs, which bounce around the screen and can cause the player to lose a life if they come into contact with them. If the player loses all their lives, the game is over.

Overall, this is a simple but fun game that demonstrates the basics of game development using the Phaser game engine.
