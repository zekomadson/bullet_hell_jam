# bullet_hell_jam
Repository for the Bullet Hell Jam (05/10/2024)


## Theme of Jam
- Consequences

## My Interpretation
- A series of levels
- You spawn along with alot of other NPCs characters, similar to a gladiator arena or D-day intro.
- You are trying to navigate to the safe space on the otherside of the map.
- Along the top are a bunch of "turrets" shooting bullets at you
- Hidden in the level are monsters also hunting you.
- If you shoot and kill, your sentiment drops but you gain XP.
- How you gain XP:
    - Survive a level
    - Kill enemies
- You can use level points to increase your stats, stats to increase include:
  - Overall Health
  - Bullet Size
  - Ammo Size (alotted amount for a given level)
- When the sentiment drops the following happens:
    - Number of bullets from the turrets increase
    - The size of the bullets increase
    - The speed of the monster inside increases.


## Basic Build:
- Character Spawn in a new level
- NPCs spawn with you and navigate towards the safe zone. 
- Character reaching safe zone triggers a 'Level Complete'
- Turrets shoot at specific spots you need to navigate around
- Monsters inside track towards the characters.


## Functionality:
- NPCs are the same class as the main character and the monsters hunt those
- All the monsters are the same type of base class, we can make specific small differences
- When a monster hits you it removes a specific amount of HP.  
