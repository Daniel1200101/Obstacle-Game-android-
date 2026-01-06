Game Description:
This is an obstacle game inspired by the Tom and Jerry series.
In the game, Jerry must avoid collisions with Tom while collecting as many pieces of cheese as possible along the way.

## 📱 App Features

### 1️⃣ Main Menu Activity
The central hub of the application, featuring a clean and intuitive user interface to guide users through the multi-layered experience.

<p align="left">
  <img src="https://github.com/user-attachments/assets/f02bfb06-503a-46e7-a6a0-208e5ebedad2" width="250" alt="Main Menu Screenshot">
</p>

#### Key Navigation:
* **🕹️ Start:** Begins the core experience/security game.
* **⚙️ Settings:** Opens the configuration panel to adjust game parameters and system preferences.
* **🏆 Top Scores:** Displays a leaderboard of high scores, including a **Map Integration** that shows the physical locations where top scores were recorded.

### 2️⃣ Settings Activity
The configuration panel allows users to customize their experience by toggling control schemes and adjusting the difficulty level of the security challenge.

<p align="left">
  <img src="https://github.com/user-attachments/assets/621767c0-3681-4212-b42c-0cbab9aa1fe8"
   width="250" alt="Settings Activity Screenshot">
</p>

#### 🎮 Movement Controls
Users can choose between two distinct input methods for navigating "Jerry":
* **Buttons (Right Switch):** Manual on-screen controls for precise movement.
* **Tilt (Left Switch):** Uses the phone's **Gyroscope/Accelerometer** to move based on device orientation.

#### ⚡ Game Difficulty
Adjusts the speed of incoming obstacles to test user reaction times:
* **🟢 Easy:** Slow-moving obstacles (Ideal for testing basic layers).
* **🟡 Medium:** Moderate speed for a balanced challenge.
* **🔴 Hard:** High-speed obstacles for maximum difficulty.
Main Activity:
This is where the game is played and includes:
Grid Objects: Obstacles (Tom), coins (cheese), and life (red cheese).
Score: Displays the player's current score.
Movement Buttons: Controls for Jerry's movement.
Hearts Array: Represents Jerry’s remaining lives.

Game Objective:
Avoid hitting Tom (obstacles) to prevent losing lives.
Collect cheese (coins) for extra points.
Collect redCheese for an extra life.

Score Activity:
Displays the player’s score at the end of each game session.

Top Scores Activity:
Contains two fragments:
Player Scores Fragment: Displays the highest scores of the game.
Map Fragment: Shows the locations of each player’s high score.
By tapping a player’s score, the map will zoom to the location where they achieved that score.

