# Endless Runner Demo (Unity)

A 3D endless runner prototype developed in Unity.

The player runs through a procedural environment, avoids obstacles, and collects coins while interacting with dynamic visual effects that enhance gameplay feedback.

---

<img width="600" height="337" alt="ezgif com-optimize" src="https://github.com/user-attachments/assets/ee9629cb-05e2-47ed-a0bc-6d9ee1fdaf93" />

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

<img width="600" height="337" alt="ezgif com-video-to-gif-converter (1)" src="https://github.com/user-attachments/assets/80c72d76-3dcf-4a8e-aba1-605f0ce26511" />


### Visual Effects
- Custom Shader Graph road curvature effect  
  *(simulates a slight bending road illusion without modifying geometry)*

- Proximity-based highlight system  
  *(coins and bottles emit glow when player is near to improve visibility and feedback)*

<img width="858" height="534" alt="Screenshot_27" src="https://github.com/user-attachments/assets/b108eca2-33b6-485f-99b5-06e2adc8ced5" />

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

### Animation System
The character uses an **Animator Controller** paired with a **1D Blend Tree** to ensure smooth visual transitions when switching lanes (left/forward/right) and execution of the jump state.

<img width="556" height="240" alt="Screenshot_28" src="https://github.com/user-attachments/assets/7d368e23-af45-4083-a01d-3e934b4e38ea" />
<img width="584" height="293" alt="Screenshot_30" src="https://github.com/user-attachments/assets/aed6ac91-9e48-42cb-a1d3-048975f010c5" />

---

## What I Learned

- Building endless runner gameplay loops
- Implementing modular gameplay systems in Unity
- Working with Unity Physics and triggers
- Creating custom visual effects using Shader Graph
- Using proximity-based feedback to improve game feel
- Structuring scripts for scalability and readability

---


## How to Run

### Run the Code in Unity
1. Open project in Unity (2022.3+ recommended)
2. Open the Main Scene
3. Press Play

### Play in Browser (Quick Demo)
You can play the fully functional WebGL demo directly in your browser without downloading anything:
👉 **[Play Endless Runner Demo on itch.io]((https://vertexvrtx.itch.io/endless-runner-demo)**
