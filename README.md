PROJECT TITLE: Dragon Slayer RPG
VERSION 1.1

------------------
CHANGELOG

V 1.1: Updated font family, font size, and text descriptions.

V 1.0: Original release

------------------

PROJECT DESCRIPTION:
A text-based adventure role-playing game (RPG) that is meant to showcase my understanding of basic HTML, CSS, and vanilla JavaScript (JS).
I completed this project as part of FreeCodeCamp's JavaScript certification course.

TECHNOLOGIES USED: 
1. VSCode Editor
2. HTML
3. CSS
4. JavaScript

CHALLENGES: 
Since this is my first JavaScript project, I had to fully grasp the fundamental concepts such as:
1. naming and calling variables
2. arrays and methods
3. different function types
4. generating random number values

HOW TO INSTALL AND RUN:
1. Download the .zip file
2. Extract folder
3. Launch your preferred code editor
4. Open the folder (dragon-slayer-rpg) in the code editor
5. Run a live server of the program (ex. for VSCode, install and use the "Go Live" extension)
6. Play the game and enjoy.

MAIN OBJECTIVE: Defeat the dragon to win the game.

GAME DETAILS:
1. Health: The number of "life points" you have. As long as you have more than 0 Health, you can continue playing.
2. XP: The number of "experience points" you have. The more XP you get, the more daamage you deal to monsters.
3. Gold: The amount of currency you can use to buy Health or Weapons. Earn more Gold by killing monsters.
4. Weapon: Items used to deal damage to monsters. From weakest to strongest, the weapons in this game are Stick, Dagger, Claw Hammer, and Sword. Each weapon costs 30 Gold.
5. Monsters: From strongest to weakest, the monsters in this game are Slime, Fanged Beast, and Dragon. Each monster deals a random amount of damage based on their level.

HOW TO PLAY:
1. You start the game in Town Square with 100 Health and 50 Gold.
2. From the Town Square, you can choose to go the "Store", "Cave", or "Fight the Dragon".
3. Collect more Gold by choosing the "Go to cave" button. You will then get to choose whether to fight a weak monster (slim), strong monster (fanged beast), or return to Town Square.
4. Everytime you choose to fight a monster, you can either "Attack" to deal damage to it, "Dodge" to avoid getting damage to yourself, or "Run" to escape the fight.
5. Attacking a monster deals damage to it based on your currently equipped weapon. I added code that randomizes the damage you deal and the chance to actually hit the monster.
6. After you attack, the monster will retaliate if it is still alive. The damage it deals will be a randomly generated number.
7. If you receive damage, your Health decreases. When you reach 0 Health, you die and the game is over.
8. If you kill a monster, you will return to Town Square.
9. You can buy a new weapon more more health by choosing "Go to Store". If you have the strongest weapon, the option to sell the other ones will become available.
10. When you are ready, choose "Fight the Dragon" from the Town Square to face the final boss.
11. If you defeat the dragon, you win the game.
12. Restart the game anytime after winning or losing.

TIPS TO WIN:
1. You can have more than 100 Health. The more you have when facing the dragon, the better the odds of surviving its massive amounts of damage.
2. Your weapon has a chance to break while attacking a monster. If it does, the next strongest one in your inventory will be used.
3. Sometimes it's better to run from a fight when you are low on Health. Live and fight another day.

FUTURE CHANGES:
I will continue to review and improve upon my code blocks to make them more readable and enforce the DRY policy ("Don't Repeat Yourself").
Whenever I update the game, I will add a changelog of revisions.
I am also planning to add more features like Armor, more weapons, new monsters and encounters, and hidden secrets.
Updating the game to use React.js insetad of vanilla JavaScript.

I hope you enjoy and please don't hesitate to leave feedback. I would really appreciated all the advice I could get to become a better developer!
