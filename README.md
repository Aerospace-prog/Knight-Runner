# 🏃‍♂️ Knight-Runner

> **Knight-Runner** is a 2D platformer game built using **Godot Engine 4.x**, featuring smooth character movement, enemy AI, collectible mechanics, animations, and a centralized game state system.  
>  
> This project focuses on **clean architecture, modular scenes, and core game-development fundamentals**.

---

## 📌 Highlights (TL;DR)

- 🎮 Physics-based 2D platformer
- 🧠 Enemy AI with raycast-based patrolling
- 🪙 Coin collection & real-time score tracking
- ☠️ Death zones with slow-motion effect & scene reload
- 🎞️ Animation-driven visual feedback
- 🔊 Audio cues for interactions
- 🧩 Clean, modular scene architecture

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Core Mechanics](#-core-mechanics)
- [Installation & Setup](#-installation--setup)
- [Controls](#-controls)
- [Architecture & Design](#-architecture--design)
- [Codebase Analysis](#-codebase-analysis)
- [Game Objects](#-game-objects)
- [Technologies](#-technologies)
- [Known Limitations](#-known-limitations)
- [Future Enhancements](#-future-enhancements)
- [License](#-license)
- [Contributing](#-contributing)

---

## 🎮 Overview

**Knight-Runner** is a side-scrolling 2D platformer where the player controls a knight navigating through levels filled with obstacles, enemy slimes, hazard zones, and collectible coins.

The game demonstrates:
- Character controllers
- Collision handling
- Enemy AI logic
- Animation state management
- Centralized score tracking
- Scene-based architecture

### Sreenshots & Videos
**#1**

<img width="580" height="327" alt="image" src="https://github.com/user-attachments/assets/07ebd632-ecbe-4c77-a87f-6cb122b2c414" />

---

**#2**

<img width="579" height="331" alt="image" src="https://github.com/user-attachments/assets/f5d51e78-091e-4856-a443-675c99a49c1c" />


**#3**


https://github.com/user-attachments/assets/688b171d-840e-4087-bd66-9cc555928744


---

## ✨ Features

### 🎯 Core Gameplay

- Smooth player movement & jumping
- Coin collection with animations
- Enemy AI patrolling using raycasts
- Death zones with slow-motion effect
- Centralized score management

---

## 📁 Project Structure

```text
Knight-Runner/
├── scenes/
│   ├── player.gd
│   ├── coin.gd
│   ├── slime.gd
│   ├── killzone.gd
│   └── *.tscn
├── scripts/
│   └── game_manager.gd
├── assets/
│   ├── sprites/
│   └── audio/
├── project.godot
├── export_presets.cfg
└── README.md
```

---

## 🔧 Core Mechanics

### Player Controller
Handles movement, gravity, jumping, animation states, and sprite flipping.

### Enemy AI
Raycast-based patrol system with automatic direction switching.

### Game Manager
Tracks and updates score globally.

### Coin
Triggers score increment and pickup animation.

### Kill Zone
Handles player death and scene reload.

---

## 🎮 Installation & Setup

```bash
git clone https://github.com/Aerospace-prog/Knight-Runner.git
cd Knight-Runner
```

Open with Godot Engine and press **F5** to run.

---

## 🎮 Controls

| Action | Keys |
|------|------|
| Move Left | A / ← |
| Move Right | D / → |
| Jump | Space / W |

---

## 🧠 Architecture & Design

- Scene-based modular architecture
- Single responsibility scripts
- Signal-driven interactions
- Centralized game state

---

## 🔍 Codebase Analysis

**Strengths**
- Clean modular code
- Frame-rate independent physics
- Efficient raycasting

**Improvements**
- Constants instead of magic numbers
- Input rebinding
- Save system

---

## 🎭 Game Objects

| Object | Type |
|------|------|
| Player | CharacterBody2D |
| Coin | Area2D |
| Slime | Node2D |
| Killzone | Area2D |

---

## 🛠 Technologies

- Godot Engine 4.x
- GDScript
- Godot Physics
- AnimationPlayer
- Git

---

## ⚠️ Known Limitations

- Single level
- No save system
- Limited enemy types

---

## 🚀 Future Enhancements

- Multiple levels
- Boss enemies
- Power-ups
- Menu system
- Persistent high scores

---

## 📝 License

Open-source for educational use.

---

## 🙌 Contributing

Fork → Branch → PR 🚀

---

## 👨‍💻 Author

**Aerospace-prog**
