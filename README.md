Structure and implement the core mechanics for this project in Unreal Engine:

1. Game Maps
Design: Create two open-world maps with varied terrain like forests, hills, buildings, or caves. Use Unreal's landscape tools to build environments.
Map Mechanics: Integrate a minimap that shows the player’s location. Add markers or icons that appear when the player is close to treasure or important items.
Travel Between Maps: Consider teleportation portals, hidden paths, or missions that unlock the second map.

3. Treasure Hunt System
Hints: Create a system where the player receives hints based on their proximity to the treasure (e.g., audio cues, glowing markers, or messages).
Final Treasure: Place the final treasure in a unique location on the second map. Use puzzles, enemies, or locked areas to make accessing it challenging.

4. Enemy AI (Bots)
Enemy Spawning: Use random spawning across the map to make encounters less predictable. Design bots with different behaviors (patrolling, guarding treasure spots, ambushing).
Combat System: Implement a combat system with shooting mechanics. You can use Unreal’s blueprint visual scripting or code in C++ to handle the weapon mechanics, aiming, and enemy damage.

5. Looting and Randomization
Building Interiors: Design buildings where players can find loot (guns, ammo, health packs). Randomize the loot for each playthrough using Unreal’s randomization logic.
Loot System: Create a looting mechanic where players can interact with objects (e.g., crates, cabinets). Implement different types of weapons with stats like damage, range, and accuracy.

6. Open-World Exploration
Traversal: Allow the player to explore freely with climbing, running, and possibly vehicles or horses to cover larger distances.
Map Design: Scatter small points of interest (camps, ruins, outposts) that encourage exploration and can contain loot or mini-bosses.

7. Progression and Leveling
Leveling System: Add character progression where the player earns experience points (XP) for defeating bots or finding items. Unlock new abilities (faster movement, higher jumps, better aim) as they level up.
Upgrades: Implement upgrade stations or merchants where the player can improve weapons, armor, or health with materials found around the map.

8. Randomized Loot Distribution
Randomization Logic: Use Unreal Engine’s random number generator to place items in random locations within each building. Items should refresh after a certain time or when the player revisits the area.
Different Loot Types: Categorize loot into common (ammo, small guns), rare (armor, special weapons), and unique (special items or high-damage weapons).

9. UI and User Experience
HUD: Display health, ammo, minimap, and hints on the player’s HUD. Use visual or auditory cues to inform players when they’re near treasure.
Inventory System: Design an inventory where the player can manage their loot and weapons.
