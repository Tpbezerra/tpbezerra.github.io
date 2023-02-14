# Tower Defence

## Contributions
As this was a solo project I implemented everything alone. For this project I didn't make any custom models, instead making use of the standard shapes available in Unity. The features I implemented are: <br />
    - Economy <br />
    - Distinct towers and placement <br />
    - Horde system <br />
    - Upgrades <br />
<br />
This was the first time I had done drag and drop style controls as well as an upgrade system. The turrents in this were also made from one script with different variables meaning that I made the script as modular as I could. I am quite happy with the upgrade system as it became easily scalable if I wanted to add more upgrades or expand to have multiple possible upgrades.

## Towers
As in other tower defence games you will attempt to fight off advancing enemies by placing towers of different types around the map. In this game there are 4 towers, a faster shooter for shorter range, a short range tower dealing AOE damage, a long range slower firing shooter, and a non-damaging slowing tower. The towers will prioritise firing damaging the enemies that are furthes along their paths.

<img src="Tower Defence Placement.jpg" width="300">

Each tower also has three upgrades that will improve the performance of it by increasing stats such as firing speed, range, damage, and penetration.

<img src="Tower Defence Upgrading.jpg" width="300">

Selling a tower will give back a percentage of the money invested into it. This includes the initial cost and all of the upgrade costs.

## Enemies
The enemies follow predefined paths and once they reach the end of that path the player loses health. They spawn with differing amounts of health and move faster the more they have. Their colour changes to reflect this health and speed.