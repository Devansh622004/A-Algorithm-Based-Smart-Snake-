# 🐍 SMART SNAKE — A* Pathfinding AI Game (Premium Edition)

This project implements a **self-playing Snake game** using the **A\* Pathfinding Algorithm**.  
The snake intelligently navigates the grid, avoids obstacles, and always searches for the **shortest and safest** path to food.

---

## 🎯 Objective

To design and develop an **AI-driven Snake game** using the **A\*** algorithm so the snake can automatically locate and reach the food while avoiding walls and its own body.

---

## 🧠 Technologies Used

| Technology | Purpose |
|----------|---------|
| Python | Base programming |
| Pygame | Graphics, animation & keyboard handling |
| A\* Algorithm | Smart pathfinding logic |
| Manhattan Distance | Heuristic for A* |

---

## 🔥 Features

✅ A* intelligent path planning  
✅ Avoids collisions with itself and walls  
✅ Dynamic maze generation  
✅ Night mode visuals  
✅ Smooth graphic animation  
✅ Score tracking and snake length growth  
✅ Resizable window + optional fullscreen  
✅ Safe fallback moves when path is blocked  

---

## 🧩 Game Controls

| Key | Action |
|----|--------|
| SPACE | Pause/Resume |
| R | Restart |
| N | Toggle Night Mode |
| M | Toggle Maze/Normal Mode |
| F | Fullscreen Mode |
| ESC | Quit Game |

---

## ▶️ How to Run

### 🔹 1️⃣ Install Requirements
```bash
pip install pygame

🌟 Future Enhancements
Reinforcement Learning (Q-Learning version)
Longer planning path to avoid trapping itself
Smart food placement to increase challenge
UI menus & sounds

🧱 Maze & Obstacles

A random maze is generated using obstacle placement:
✔ Border walls
✔ Random blocks inside grid
✔ Safe spawn area for snake

Maze makes AI decision-making challenging 🧩
