# Endless Runner Demo (Unity)

A 3D endless runner prototype developed in Unity.

The player runs through a procedural environment, avoids obstacles, and collects coins while interacting with dynamic visual effects that enhance gameplay feedback.

---


## Gameplay

- Endless forward movement
- Lane-based movement system
- Jump mechanic
- Obstacle avoidance
- Coin collection
- Score increases over time
- Game over on collision

---

## Controls

| Key | Action |
|-----|--------|
| A / D | Move left / right |
| Space | Jump |
| Esc | Pause |

---

## Features

### Gameplay Systems
- Endless runner loop
- Procedural obstacle spawning
- Coin collection system
- Score tracking system
- Collision-based game over

### Visual Effects
- Custom Shader Graph road curvature effect  
  *(simulates a slight bending road illusion without modifying geometry)*

- Proximity-based highlight system  
  *(coins and bottles emit glow when player is near to improve visibility and feedback)*

---

## Tech Stack

- Unity
- C#
- Shader Graph
- Unity UI
- Physics (Rigidbody / Colliders)

---

## Architecture

- PlayerController (movement + input handling)
- ObstacleSpawner (procedural spawning system (with Object Pooling))
- Coin system (collection + scoring)
- GameManager (game state control)
- UIManager (score + game over UI)
- VFX system (proximity highlight logic)

---

## What I Learned

- Building endless runner gameplay loops
- Implementing modular gameplay systems in Unity
- Working with Unity Physics and triggers
- Creating custom visual effects using Shader Graph
- Using proximity-based feedback to improve game feel
- Structuring scripts for scalability and readability

---

## Screenshots / Video


---

## How to Run

1. Open project in Unity (2022.3+ recommended)
2. Open the Main Scene
3. Press Play
