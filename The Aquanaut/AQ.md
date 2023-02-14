# The Aquanaut

## Contributions
For this project I did most of the programming, this means everything except for the main menu UI, settings, and certain parts of the boids. I also did some modelling and spent a lot of time on the design of the game. <br />
Programming: <br />
    - Camera <br />
    - Movement <br />
    - Attacks & combos <br />
    - Shooting (standard and heavy) <br />
    - Dodging & deflecting <br />
    - Damage & healing <br />
    - AI <br />
    - Poise <br />
    - Wave system <br />
    - Audio manager (fading music and playing sounds) <br />
    - Interactables <br />
    - Active effects <br />
    - CC effects <br />
    - Saving and loading <br />
    - In-game UI (not pause menu) <br />
Modelling: <br />
    - Weapons (2 swords, trident, harpoon, harpoon gun) <br />
    - Basic enemies (and their armour) <br />
    - Crystals (save- and healing crystals) <br />
    - Gate <br />
Design: <br />
    For the gameplay, and specifically combat, design it was mainly me and one other member that worked on it to balance and make it fun. The in-game UI was a collaborative effort where I would desig something and then change it according to input. <br />
<br />
This project was very fun to work on and also very usefull as it was the first project that required a proper start and finish for a level with scaling difficulty and a fun gameplay-loop. It also made me much better at writing sustainable code that could be expanded upon at a later date. Finally it was the first project where I had to properly think about how to make the game balanced and really fun. This lead me to getting better at exploring and bringing forward game-feel. What I am most proud of with this is how scalable and maintainable the code is as it was easy to add new features and fix any bugs that crept up.

## The Player
The player has a few options at any given time, dodging, attacking with their sword, and shooting their harpoon. The dodge gives invulnerability frames for a part of it which helps the player avoid damage. During an even smaller part of it is a deflect "window" where, if timed properly, the player can deal poise damage to the attacker while on the defensive. <br />
There are two options when attacking, light- and heavy attacks. When attacking with the sword this means that different animations with alternate stats will play. Light and heavy attacks can then be combined to perform chain attacks. When shooting a harpoon a light attack will root the target it hits while a heavy will stun it and anyone around but also costing crystals to use. Crystals are also used for healing.

<img src="The Aquanaut Heavy Harpoon.jpg" align="left" width="300">

When close to objects the player can interact with a prompt will appear telling the player that it is possible to do so.

<img src="The Aquanaut Interaction.jpg" align="left" width="300">

Large crystals will replenish the player's crystals and max out their health.

<img src="The Aquanaut Recharging.jpg" align="left" width="300">

## Enemies
Each enemy has a set of attacks that they can perform, these can then lead into other attacks for longer attack chains. There are three types of enemy, a sword enemy with more sweeping and AOE attacks but lower range; a trident enemy with longer range but less area; and a harpoon thrower that tries to stay away while attacking from range, when up close they can kick the player away.