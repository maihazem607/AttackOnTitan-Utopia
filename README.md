# Attack on Titan: Utopia 🛡️👾

** Attack on Titan: Utopia ** is a thrilling single-player, endless tower defense game inspired by the renowned anime series _Attack on Titan_. In this immersive experience, players must strategize and defend the Utopia District from the onslaught of titans that have breached Wall Maria, now threatening the very walls of Wall Rose. 🏰⚔️

## Table of Contents:

- [Game Overview](#game-overview)
  - [Setting](#setting)
  - [Gameplay Features](#gameplay-features)
    - [Endless Tower Defense Mechanics](#endless-tower-defense-mechanics)
    - [Multi-Lane Battlefield](#multi-lane-battlefield)
    - [Diverse Titan Types](#diverse-titan-types)
    - [Variety of Weapons](#variety-of-weapons)
    - [Resource Management](#resource-management)
    - [Danger Level System](#danger-level-system)
  - [Battle Phases](#battle-phases)
- [Game Video](#game-video)
- [Technologies Used](#technologies-used)
- [Setup and Installation Guide](#setup-and-installation-guide)
  - [Requirements](#requirements)
  - [How to Run the Game](#how-to-run-the-game)
- [Collaborators](#collaborators)

---

## Game Overview

### Setting 🌍

Set in a war-torn world, **Attack on Titan: Utopia** unfolds in the Utopia District, a vital stronghold on the northern border of Wall Rose. After the titans have breached Wall Maria, humanity's survival hangs by a thread. As the commander of the last line of defense, players are tasked with deploying various anti-titan weapons and strategies to prevent the titans from breaking through the walls and obliterating the last bastion of hope. 💪🛡️

### Gameplay Features

#### Endless Tower Defense Mechanics 🏰

Engage in an endless battle against waves of titans. The game has no winning condition; instead, the objective is to survive for as long as possible while defeating as many titans as you can, with your score increasing based on resources collected from fallen foes. 📈

#### Multi-Lane Battlefield 🌌

The battlefield is divided into multiple lanes, each featuring a segment of the wall to protect. Players must strategically deploy weapons in these lanes, each with its own health points (HP). If a segment is destroyed, that lane becomes inactive, requiring players to manage their defenses across all active lanes. 🚧

#### Diverse Titan Types 👹

Face various titans, each with unique attributes and abilities:

- **Pure Titan**: A basic titan with balanced stats.
- **Abnormal Titan**: Attacks twice per turn, posing a greater threat.
- **Armored Titan**: Highly resistant, taking only 25% damage from attacks.
- **Colossal Titan**: Starts with high HP and increases speed with each turn, becoming a significant danger if not dealt with quickly.

| Titan Type     | HP   | Damage | Height | Speed | Resources Value | Danger Level |
| -------------- | ---- | ------ | ------ | ----- | --------------- | ------------ |
| Pure Titan     | 100  | 15     | 15     | 10    | 10              | 1            |
| Abnormal Titan | 100  | 20     | 10     | 15    | 15              | 2            |
| Armored Titan  | 200  | 85     | 15     | 10    | 30              | 3            |
| Colossal Titan | 1000 | 100    | 60     | 5     | 60              | 4            |

#### Variety of Weapons 🔫

Players can purchase and deploy an array of weapons, each with specific strengths and weaknesses. Weapons include:

- **Piercing Cannon**: Attacks the closest five titans within its range.
- **Sniper Cannon**: Deals heavy damage to the closest titan.
- **Volley Spread Cannon**: Affects all titans within a specified range.
- **Wall Trap**: Targets titans that reach the wall directly.

| Weapon Name          | Price | Damage | Min Range | Max Range |
| -------------------- | ----- | ------ | --------- | --------- |
| Piercing Cannon      | 25    | 10     | -         | -         |
| Sniper Cannon        | 25    | 35     | -         | -         |
| Volley Spread Cannon | 100   | 5      | 1         | 5         |
| Wall Trap            | 75    | 100    | -         | -         |

#### Resource Management 💰

Collect resources by defeating titans, which can then be used to purchase weapons. Managing these resources effectively is crucial to maintaining defenses and ensuring the survival of the Utopia District.

#### Danger Level System ⚠️

Each lane has a danger level calculated based on the types and number of titans present. Higher danger levels require more immediate attention and resources to mitigate the threat.

### Battle Phases 🔥

The game progresses through three battle phases—Early, Intense, and Grumbling:

- **Early Phase**: Fewer titans with lower danger levels.
- **Intense Phase**: Increased titan strength and frequency.
- **Grumbling Phase**: Dominated by powerful titans, including multiple Colossal Titans.

| Turns Passed | Battle Phase | Titans Per Turn | Titans Type                       |
| ------------ | ------------ | --------------- | --------------------------------- |
| 0-15         | Early        | 1               | Pure, Abnormal, Armored, Colossal |
| 16-30        | Intense      | 1               | Pure, Abnormal, Armored, Colossal |
| 31+          | Grumbling    | 1 (increases)   | Colossal                          |

---

## Join the fight for humanity's survival!!⚔️

## Game Video 📸

Check out some exciting moments from _Attack on Titan: Utopia_ below!

[Video Link](https://github.com/user-attachments/assets/5ab61407-7566-4f78-87d1-2293a17fdcbd)

## Technologies Used

- **Programming Language**: Java
- **Framework**: JavaFX
- **Architecture**: MVC (Model-View-Controller)
- **Programming Paradigm**: Object-Oriented Programming (OOP)

## Setup and Installation Guide

### Requirements

- **Java Development Kit (JDK)** version 11 or higher
- **JavaFX SDK** version 22.0.1 or newer

### How to Run the Game

1. **Configure JavaFX**

   - Download the latest JavaFX SDK from [Gluon’s official site](https://gluonhq.com/products/javafx/).
   - Extract the contents and make a note of the `lib` directory path inside the SDK folder.

2. **Compile and Launch**
   - In your IDE, make sure to set the JavaFX `lib` folder as the module path.
   - When running the application, provide the following VM arguments:
     ```
      --module-path "path/to/javafx-sdk/lib" --add-modules javafx.controls,javafx.fxml,javafx.media
     ```

## Collaborators

- **[Mai Hazem]** - [@maihazem607](https://github.com/maihazem607)
- **[Esraa Tarek]** - [@EsraaTarek382](https://github.com/EsraaTarek382)
- **[Hana Ayman]** - [@HanaAyman33](https://github.com/HanaAyman33)
