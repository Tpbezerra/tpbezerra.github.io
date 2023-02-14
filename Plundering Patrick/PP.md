# Plundering Patrick

## Patrick
The player controls Patrick with some different movement abilities such as walking, running, jumping and climbing, crouching, and sliding. Depending on how they are moving at the moment Patrick will give off different amounts of sound that the enemies can hear. The player also has the ability to interact with objects such as picking up items, holding bottles, and reading.

<img src="Plundering Patrick Interaction.jpg" width="300">

Picked up items are added to the player's inventory which other interactables may require to be used.

<img src="Plundering Patrick Inventory.jpg" width="300">

Held bottles will holster the cutlass and can be thrown to make a sound which distracts enemies.

<img src="Plundering Patrick Throwing.jpg" width="300">

Reading anything will bring up an interface with text. There are also doors and chests which can be opened around the map.

<img src="Plundering Patrick Reading.jpg" width="250">

For fighting the player has a cutlass that can be used to swing at enemies and block and parry their attacks. The pistol can be used to deal a lot of damage from range but also costs ammunition.

## Enemies
The enemies are controled using a FSM. They will patrol on predefined paths until they are alerted in some way, whether by spotting or hearing something or being alerted by their comrades. Once they've been alerted they will try to find the alerting presence by moving to the last known location of it. If they can't reach that position they will move to another one where they can at least see the alert location. <br />
<br />
If they spot the player they will alert other nearby enemies to that fact while moving to attack. Enemies can have a cutlass, pistol, or both. If they have both buyt can't reach the player they will use their pistol. At any one time two enemies can attack at once while the rest circle around, this is to make sure that the player doesn't get overwhelmed by all enemies attacking at once.

<img src="Plundering Patrick Combat.jpg" width="300">

## Contributions
For this project I programmed everything, did the modelling and animations, and designed the UI. <br />
Programming: <br />
    - Movement <br />
    - Attacking <br />
    - Interactions <br />
    - Objectives <br />
    - Inventory <br />
    - AI <br />
    - UI functionality <br />
    - Settings and keybindings <br />
 <br />
 Modelling and animations: <br />
    - Humanoid model and animations (movement, climbing, sliding, attacking, aiming) <br />
    - Cutlass and pistol <br />
    - Misc (bottles, gold, pouch, compass, chest, fountain, hats, tree)