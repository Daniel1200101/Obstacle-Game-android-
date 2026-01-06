<div align="center">

# 🐭 Tom & Jerry: Cheese Chase
**An interactive Android obstacle game featuring sensor-based movement and global high-score tracking.**

[![Status](https://img.shields.io/badge/Status-Complete-green?style=for-the-badge)](#)
[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen?style=for-the-badge&logo=android)](#)

---

### 🎯 Game Objective
**Survive the chase and climb the leaderboard!**
</div>

* **Avoid Tom:** Dodge the obstacles to keep your lives intact.
* **Collect Cheese:** Grab yellow cheese to boost your score.
* **Collect Red Cheese:** Find rare red cheese to restore your health.

---



## 📱 App Walkthrough

### 1️⃣ Main Menu
The central hub of the application, designed for clean and intuitive navigation through a multi-layered game experience.

<p align="center">
  <img src="https://github.com/user-attachments/assets/f02bfb06-503a-46e7-a6a0-208e5ebedad2" width="250" alt="Main Menu">
</p>

* **🕹️ Start:** Jump straight into the action.
* **⚙️ Settings:** Customize controls and difficulty.
* **🏆 Top Scores:** View the global leaderboard and achievement map.

---

### 2️⃣ Settings & Configuration
Tailor the gameplay mechanics to your preferred style.

<p align="center">
  <img src="https://github.com/user-attachments/assets/cb7e43c5-e980-4a39-9054-2c56991b5b43" width="250" alt="Settings">
</p>

* **🕹️ Movement Controls:** Toggle between **On-Screen Buttons** (Right Switch) or **Immersive Tilt Sensors** (Left Switch).
* **📈 Difficulty Levels:** Choose **Easy**, **Medium**, or **Hard** to adjust obstacle speed and intensity.

---

### 3️⃣ Gameplay Experience
The core arena where Jerry survives against Tom.

| **The Grid** | **Items & Hazards** | **Collision Feedback** |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/34a1b240-0af1-4bff-968f-02d6347f9a0d" width="200"> | <img src="https://github.com/user-attachments/assets/a9fd0e54-fb1a-4b29-b972-30e5108f4450" width="200"> | <img src="https://github.com/user-attachments/assets/8e17320e-d596-41a4-a3ff-e687c8de7311" width="200"> |
| Real-time score and Heart Array tracking. | Tom (Obstacle), Yellow Cheese (Score), Red Cheese (Life). | Visual **"MEOW"** alert + audio feedback on hit. |

---

### 4️⃣ Score Submission
Save your legacy after a hard-fought game.

<p align="center">
  <img src="https://github.com/user-attachments/assets/3065448f-ff12-47d8-98e6-b9c907c88e68" width="250" alt="Score Submission">
</p>

* **Smart Validation:** The system automatically checks if you've cracked the **Top 10**.
* **Data Persistence:** Scores and player details are saved locally to ensure progress is tracked.

---

### 5️⃣ Top Scores & Geographic Leaderboard
A dual-fragment activity that combines data with physical geography.

<p align="center">
  <img src="https://github.com/user-attachments/assets/eacba370-5173-44a0-b1a9-178ef3b99af8"
width="500" alt="Top Scores and Map">
</p>

* **🏆 Player Scores Fragment:** A scrollable "Hall of Fame" of the highest achievers.
* **🗺️ Map Fragment:** Powered by **Google Maps**, showing the exact location of every high score.
* **🔍 Interactive Zoom:** Tap any score in the list to automatically zoom the map to that specific achievement location.

---

<div align="center">

### 🛠️ Tech Stack
**Java/Kotlin** | **Android SDK** | **Google Maps API** | **SensorManager** | **Fragments**

</div>
