# 🚦 Traffic Simulation Game in Java

This is a Java-based 2D traffic simulation game developed as a university term project. The simulation involves multiple levels of increasing difficulty, real-time vehicle generation, and tile-based map rendering.

## 🎮 Project Overview

- Vehicles move autonomously across predefined road tiles.
- Collisions are avoided using simple movement and lane rules.
- Spawners periodically generate new cars at specific entry points.
- The game background and roads are rendered using Java GUI components.

## 🛠️ Features

- Object-oriented design with classes for `Car`, `RoadTile`, `Building`, and `Levels`.
- 5 progressively harder levels implemented: `Level1.java` to `Level5.java`.
- Real-time simulation with vehicle spawners (`CarSpawner`).
- Java Swing/GUI-based graphical rendering.
- Modular code for extensibility (new roads, spawners, levels).

## 🗂️ Project Structure

TermProject/
├── Building.java
├── Car.java
├── CarSpawner.java
├── GameBackground.java
├── Level1.java ... Level5.java
├── RoadTile.java
├── TrafficLight.java
├── Test.java


## 🖥️ How to Run

1. **Requirements**:
   - Java JDK 8 or above
   - A Java IDE (e.g., IntelliJ IDEA, Eclipse) or terminal

2. **Compile:**
   ```bash
   javac *.java
   ```

3. **Run (example):**
   ```bash
   java Level1
   ```

> Each `LevelX` class starts a different difficulty level of the game.

---

## 📄 Project Report

The full project documentation includes:
- Class descriptions
- Design explanation
- Simulation logic
- Development notes

## ✍️ Author Note

This project was fully developed as part of a team term project, but this GitHub repository is maintained and uploaded solely by **Alper Kaan Arslan**.
