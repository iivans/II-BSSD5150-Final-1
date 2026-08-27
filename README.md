# II-BSSD5150-Final-1

## Overview

Welcome to **II-BSSD5150-Final-1**, a 2D platformer game developed in Unity version 2022.3.17f1. This repository houses the core source code, configuration files, and script assets designed to deliver an interactive side-scrolling platforming experience.

## Game Architecture and Components

The codebase is organized into several modular components that govern game logic, player controls, environment design, and enemy behaviors.

* **Game Management and UI:** Flow control, scoring, and scene transitions are managed by scripts such as `GameController`, `ScoreManager`, `Menu`, `NextSceneUI`, `WinSceneEnd`, and `GameOverController`. These handle win/loss conditions, user interface navigation, and score tracking throughout gameplay.
* **Player and Object Interaction:** Character mechanics and physical interactions rely on scripts like `Movement`, `Coin`, and `MovableBox`, allowing the player to navigate platforms, collect items, and interact with dynamic elements in the world.
* **Enemies and Hazards:** Challenge elements are introduced via `EnemyDragon`, `SawController`, `MaceEnemy`, and `FireballController`, which dictate enemy movement, hazard patterns, and combat interactions.
* **Environment and Parallax:** Visual atmosphere is established using background control scripts including `BackgroundControl_0` and `ParallaxBackground_0` to create depth perception via parallax scrolling.

## Technical Specifications

* **Engine Version:** Unity 2022.3.17f1 (Standalone Windows 64-bit build target)
* **Language Standard:** C# 9.0
* **Framework Compatibility:** .NET Standard 2.1 / .NET Framework 4.7.1

## Getting Started

To open, run, or modify this project, ensure you have Unity Hub installed alongside Unity Editor version 2022.3.17f1. Clone or download this repository onto your local machine, add it as a project via the Unity Hub, and open it in the Unity Editor to begin developing or playing.
