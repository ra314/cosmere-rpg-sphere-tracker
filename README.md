# cosmere-rpg-sphere-tracker
A web app to track your stormlight and wealth in the Cosmere RPG. Vibe-coded.

## Features

*   **Player Management:**
    *   Add, rename, and remove multiple players.
*   **Sphere Tracking:**
    *   Add spheres individually or in bulk by type, gemstone, and infusion status.
    *   Spheres are automatically valued in Diamond Marks.
    *   Track the quantity and status (Infused/Dun) of each sphere stack.
*   **Stormlight Management:**
    *   **Time-Based Depletion:** Advance game time to automatically drain Stormlight from Infused spheres after their 5-day lifespan.
    *   **Manual Toggling:** Directly infuse or drain specific quantities of spheres from any stack, regardless of time.
*   **Inventory Organization:**
    *   Spheres are sorted by gemstone and size for easy viewing.
    *   Quantity adjustments for sphere stacks are intuitive.
*   **Data Persistence:**
    *   **JSON Export:** Save your entire game's state (player data, sphere inventories) to a JSON file.
    *   **JSON Import:** Load a previously saved game state, allowing for continuity and sharing.

## **Sphere Values in Diamond Marks**

| Gemstone                 | Chip | Mark | Broam |
|--------------------------|------|------|-------|
| Diamond                  | 0.2  | 1    | 4     |
| Garnet, heliodor, topaz  | 1    | 5    | 20    |
| Ruby, smokestone, zircon | 2    | 10   | 40    |
| Amethyst, sapphire       | 5    | 25   | 100   |
| Emerald                  | 10   | 50   | 200   |

Page 242: The Stormlight Handbook
