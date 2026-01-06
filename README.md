## 🎮 Game Description:
This is an obstacle game inspired by the Tom and Jerry series.
In the game, Jerry must avoid collisions with Tom while collecting as many pieces of cheese as possible along the way.


## 📱 App Features

### 1️⃣ Main Menu Activity
The central hub of the application, featuring a clean and intuitive user interface to guide users through the multi-layered experience.

<p align="left">
  <img src="https://github.com/user-attachments/assets/f02bfb06-503a-46e7-a6a0-208e5ebedad2" width="250" alt="Main Menu Screenshot">
</p>

#### Key Navigation:
* **🕹️ Start:** Begins the core experience/obstacle game.
* **⚙️ Settings:** Opens the configuration panel to adjust game parameters and system preferences.
* **🏆 Top Scores:** Displays a leaderboard of high scores, including a **Map Integration** that shows the physical locations where top scores were recorded.
---
### 2️⃣ Settings Activity
The settings panel allows players to customize their gameplay experience, from how they control Jerry to the overall intensity of the game.

<p align="left">

  <img src="https://github.com/user-attachments/assets/cb7e43c5-e980-4a39-9054-2c56991b5b43" width="250" alt="Settings Activity Screenshot">
</p>

#### 🕹️ Movement Controls
Choose how you navigate Jerry to avoid incoming obstacles:
* **Buttons (Right Switch):** Classic on-screen button controls for precise movement.
* **Tilt (Left Switch):** Immersive gameplay using the phone's **sensors**; move Jerry by tilting your device left or right.

#### 📈 Game Difficulty
Adjust the speed of the obstacles to match your skill level:
* **🟢 Easy:** Obstacles move at a slow, predictable speed.
* **🟡 Medium:** A moderate pace requiring better focus.
* **🔴 Hard:** High-speed obstacles for players seeking a real challenge.

---
### 3️⃣ Main Activity (Gameplay)
The core gameplay screen where the player controls Jerry to survive, collect items, and achieve high scores.

#### 🎮 Game Interface
<p align="left">
  <img src="https://github.com/user-attachments/assets/34a1b240-0af1-4bff-968f-02d6347f9a0d"
width="250" alt="Main Gameplay">
</p>

* **Grid Objects:** A dynamic grid featuring **Tom** (Obstacles), **Cheese** (Score Boosts), and **Red Cheese** (Health/Life).
* **Live Score:** Real-time tracking of cheese collected during the session.
* **Hearts Array:** A visual life bar representing Jerry’s remaining health.
* **Movement Buttons:** On-screen controls for quick navigation (when Button mode is active).

#### 🧀 Items & Hazards
<p align="left">
  <img src="https://github.com/user-attachments/assets/a9fd0e54-fb1a-4b29-b972-30e5108f4450"
width="250" alt="Game Items">
</p>

* **Obstacles (Tom):** Avoid these at all costs! 
* **Score (Yellow Cheese):** Collect these to increase your total points.
* **Health (Red Cheese):** Rare items that restore a life to your Hearts Array.

#### 🙀 Collision State
<p align="left">
  <img src="https://github.com/user-attachments/assets/8e17320e-d596-41a4-a3ff-e687c8de7311"
 width="250" alt="Collision Feedback">
</p>

* **Feedback:** When an obstacle hits Jerry, a **"MEOW"** alert is triggered + cat meow sound, and a life is deducted from the heart array.

---
### 4️⃣ Game Over & Score Submission
When the game ends, players have the opportunity to save their legacy. 
<p align="left">
  <img src="https://github.com/user-attachments/assets/3065448f-ff12-47d8-98e6-b9c907c88e68"
width="250" alt="Score Submission">
</p>

* **Data Entry:** If a player achieves a high score, they can enter their details to be recorded.
* **Smart Validation:** The system automatically checks if the current score qualifies for the **Top 10 Leaderboard**.
* **Automatic Saving:** All high scores are saved locally/to the database, ensuring your progress is never lost.
---
### 5️⃣ Top Scores Activity
This activity provides a detailed look at the leaderboard using a dual-fragment layout, combining competitive data with geographic tracking.

<p align="left">
  <img src="https://github.com/user-attachments/assets/3c5bc798-83b0-4cca-b9b3-abc3c34c62e7"
width="250" alt="Top Scores and Map">
</p>

#### 🏆 Player Scores Fragment
* **Hall of Fame:** Displays a list of the highest scores achieved across all game sessions.
* **Session Details:** Shows the player's name and their final score.

#### 🗺️ Map Fragment
* **Global Pinning:** Displays the precise location where each high score was achieved.
* **Interactive Zoom:** A specialized feature where **tapping a player's score** in the list triggers the map to automatically zoom into the specific location of that achievement.
