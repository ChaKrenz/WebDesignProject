# 3D Speedrunning Game Design Document

## Objective

To design a 3D speedrunning game where the player's objective is to complete the course as quickly as possible. Players can collect various tools and resources that enhance their speed, agility, or abilities. The game features a leaderboard showcasing top times for global players, fostering competitive play.

---

## Introduction

The game emphasizes speed, agility, and efficient use of collected tools to reach the finish line in record time. With minimal distractions, the design prioritizes an engaging player experience by incorporating interactive elements that enhance the game’s excitement without overwhelming the player.

---

## The Design Process

### 1. Research and Inspiration

Drawn inspiration from popular speedrunning games like *Mirror’s Edge* for its parkour elements and *Trackmania* for competitive time-based racing. The game will use elements from fast-paced obstacle courses, where players need to make split-second decisions to maximize speed.

---

### 2. Concept Development

#### Purpose
The game provides a fast-paced experience where players race against time to reach the finish line. It emphasizes quick reflexes, path optimization, and strategic use of power-ups and tools collected along the way. The leaderboard adds a competitive edge, motivating players to improve their scores and climb the rankings.

#### Target Audience
This game is intended for a broad audience:
- **Ages:** 8 and up
- **Interests:** Speedrunning, racing, platforming games, competitive gaming
- **Needs:** The game addresses the desire for high-speed, skill-based gameplay, and leaderboard-driven motivation for constant self-improvement.

---

## Conceptualize the Design

### Aesthetics (Look)

#### Visual Style
- **Theme:** Futuristic and sleek, inspired by a cyberpunk aesthetic. Levels feature vibrant neon colors and metallic surfaces, creating an energetic atmosphere. This doesn't necessarily have to be what the user sees... maybe add a feature so the user can switch how their screen looks while they are doing it.
- **Imagery/Iconography:** Futuristic icons for tools and power-ups, minimalist HUD elements for a clean and immersive visual experience.

#### Color Scheme
- **Palette:** Neon blues, purples, and pinks against darker backgrounds to create high contrast, emphasizing speed and excitement.
- **Psychology:** The color scheme conveys a sense of urgency and action, which aligns with the game’s high-paced nature.

#### Typography
- **Font Style:** Sleek, modern fonts with strong readability for HUD elements and leaderboard text.
- **Consistency:** Fonts will maintain a uniform style across menus, in-game popups, and leaderboard displays.

#### Layout
- **Game UI:** Minimalist, with only essential HUD elements (time, collected resources, and player position) displayed. The leaderboard is accessible from the main menu and end screens.
- **Ease of Navigation:** A clear main menu with options to start the game, view leaderboards, and adjust settings. Simple and intuitive.

---

### Functionality

#### Core Features
- **Speedrun Objective:** The primary objective is to finish the course in the shortest time possible.
- **Tool Collecting Mechanic:** Players can gather tools (e.g., speed boosts, grappling hooks, time-slowing gadgets) along the route to aid them.
- **Leaderboard:** Displays the top scores globally, allowing players to compete for the fastest times.
- **Time Tracker:** Real-time tracking of the player’s current run time, displayed in the HUD.

#### Controls

- **View Panning:** Use the mouse to shift perspectivie similar to minecraft. This should be a first person point of view and there should be some screen shake to make it look as if the user is running.
- **Movement:** `W`, `A`, `S`, `D` keys for forward, left, back, and right movement.
- **Jump:** `Space` to jump, with controlled height based on how long the key is held.
- **Inventory Access:** `E` key to open the inventory, allowing players to view and equip items.
- **Tool Activation:** Certain tools are automatically equipped when collected, while others may require manual activation through hotkeys (e.g., `1`, `2`, `3` for speed boosts, grappling hook, and time-slowing gadget).

---

#### Abilities and Tools

1. **Speed Boosts**
   - **Effect:** Temporarily increases the player's speed, allowing for quick dashes.
   - **Use:** Essential for overcoming longer jumps or dashing through long sections with minimal obstacles.
   - **Duration:** Typically lasts for 2–3 seconds with a cooldown period before it can be used again.

2. **Grappling Hook**
   - **Effect:** Allows the player to grapple onto specific points, quickly propelling them across gaps or pulling them up to higher platforms.
   - **Use:** Useful for vertical navigation or bypassing lengthy sections.
   - **Mechanic:** Players aim at a designated grapple point and press the assigned hotkey to activate.

3. **Time-Slow Gadget**
   - **Effect:** Temporarily slows down time, allowing the player to better control movements or react to obstacles.
   - **Use:** Helps in areas with a high density of obstacles, tight corners, or sharp turns.
   - **Duration:** Lasts for approximately 5 seconds, with a cooldown period.

4. **Inventory System**
   - **Purpose:** Allows players to manage collected tools and power-ups.
   - **Functionality:** Accessible by pressing `E`. Players can equip or discard tools as needed based on the upcoming obstacles or path layout.

#### User Flow

1. **Start Game:** Player selects “Start Game” from the main menu.
2. **In-Game Navigation:** Player navigates the course, collecting tools and using them to overcome obstacles.
3. **Finish Line:** Upon reaching the finish, the player’s time is displayed.
4. **Leaderboard Update:** If the player's time is one of the fastest, it is uploaded to the leaderboard.
5. **Replay or Exit:** The player can choose to try again or return to the main menu.

---

### Interactive Elements

- **Tools/Resources:** Includes speed boosts, a grappling hook for quick traversal, and a time-slow gadget. Each tool is visually distinct and highlights the cyberpunk theme.
- **Leaderboards:** Accessible from the main menu, showcasing top players and their scores globally. A local leaderboard is also available to track personal progress.

---

### 4. Create Design Sketches

#### Wireframes

1. **Main Menu Wireframe**
   - Simple layout with “Start Game,” “Leaderboard,” and “Settings” options.
   - Clean and intuitive design with a futuristic theme.

2. **In-Game HUD Wireframe**
   - Minimalistic HUD, showing time at the top, tool inventory on the right, and resource counters (like coins) on the left.

3. **Leaderboard Wireframe**
   - List of player names, scores (time to complete), and ranks displayed in an organized, scrollable format.

#### Mockups

1. **Main Menu Mockup**
   - Vibrant, neon-themed menu with futuristic fonts and iconography.
   - Hover effects on buttons to match the cyberpunk aesthetic.

2. **Game HUD Mockup**
   - HUD elements (time, tools) styled with sleek, semi-transparent backgrounds to avoid obstructing the view of the course.

3. **Leaderboard Mockup**
   - Neon text and a dark background, with animations for score updates to create a dynamic leaderboard experience.
