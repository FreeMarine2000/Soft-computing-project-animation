# C.E.N.T.A.U.R — Obstacle Navigation Simulation

> **Combat-Enabled Navigation & Tactical Autonomous Utility Robot**
>
> A soft-computing project showcasing an autonomous bot navigating a dynamic obstacle-filled environment using intelligent pathfinding and threat-response logic.

---

## About

🎮 **[View Virtual Demo](https://freemarine2000.github.io/Soft-computing-project-animation/)** — Watch the bot autonomously scan, navigate, engage, and exit a hostile environment in real time.

The demo runs entirely in the browser — no installation required.

---

## What the Bot Does

The simulation plays out in five sequential phases:

| Phase | Name | Description |
|-------|------|-------------|
| 0 | **SCAN** | Bot idles at its starting position and sweeps the environment with radar rings, assessing threats and planning a route |
| 1 | **APPROACH** | Bot follows the computed optimal path toward the objective while the stickman enemy fires near-miss shots |
| 2 | **ENCOUNTER** | Bot reaches the stickman; a barrel is detonated — the explosion eliminates the threat |
| 3 | **EXIT** | Bot navigates the exit corridor and leaves the combat zone |
| 4 | **DONE** | Brief pause before the simulation loops and resets |

The environment is rendered as an **isometric (3D top-down)** grid with:
- Dynamic pathfinding visualization (ghost trail overlay)
- Real-time threat indicators (HUD: THREAT / PATH / STATE)
- Particle explosion effects
- Bullet-trail rendering with impact holes
- Animated stickman enemy with death physics

---

## Tech Stack

- **Pure HTML5 Canvas** — zero dependencies, no frameworks
- **Vanilla JavaScript** — hand-written isometric renderer, easing functions, and state machine
- **CSS** — minimal dark-theme HUD

---

## Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/FreeMarine2000/Soft-computing-project-animation.git
   ```
2. Open `index.html` in any modern browser — that's it.

---

## Project Context

This animation was built as part of a **Soft Computing** course project to visually demonstrate autonomous agent behavior, including:
- Environment scanning
- Pathfinding under adversarial conditions
- Threat neutralization
- Mission completion and loop control
