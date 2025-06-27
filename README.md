# 🎈 Balloon Game

Balloon Game is a simple yet engaging 2D game developed using **Java Swing**.  
In this game, the player controls a **balloon** that must avoid birds while collecting **coins** and **power-ups** to increase their score.

This project is ideal for learning Java GUI programming, basic **game loops**, **OOP design**, and **collision detection**.

---

## 🎯 Objective

Control the balloon to survive as long as possible by:
- **Avoiding birds** 🐦 (enemies).
- **Collecting coins** 💰 (score).
- **Grabbing power-ups** ⚡ (special boosts).

---

## 📦 Project Structure

```plaintext
Balloon-Game/
│
├── Game.java          # 💡 Entry point of the game. Handles main loop, rendering, and game logic.
├── Balloon.java       # 🎈 The player balloon: movement, collision handling, and rendering.
├── Bird.java          # 🐦 Enemy birds that move across the screen and cause game over if hit.
├── Coin.java          # 💰 Coins that the balloon collects to increase the score.
├── PowerUp.java       # ⚡ Temporary power-ups that give the balloon special abilities.
├── Background.java    # 🌄 Manages scrolling background effect to simulate movement.
├── Sound.java         # 🔊 Handles sound effects (optional or in progress).
├── Utils.java         # 🧰 Helper methods and constants (optional).
└── assets/            # 🖼️ Folder for images, sprites, and other resources.
```
---

## 🛠️ Technologies Used

- 🟦 Java 8+
- 🖼️ Java Swing (2D graphics)
- 🎮 Custom game loop
- 🧠 Object-Oriented Programming (OOP)

---

## 🚀 How to Run

### ✅ Requirements:
- JDK 8 or higher
- Java-compatible IDE (like IntelliJ, NetBeans, or Eclipse) **or** Terminal

### ▶️ Running from Terminal:

```bash
# Clone the repo
git clone https://github.com/Mostafa2115/Balloon-Game.git
cd Balloon-Game

# Compile all Java files
javac *.java

# Run the game
java Game
