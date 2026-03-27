# 🦸‍♂️ MARVEL Turn-Based Strategy Game

  🎮 Overview

This project is a Java-based turn-based strategy board game inspired by the Marvel universe.
Developed as a team project, the game allows players to control teams of champions (Heroes, Villains, and AntiHeroes),
utilize unique abilities, and compete strategically on a grid-based map.

The game emphasizes object-oriented design, game logic implementation, and modular architecture.

  🚀 Features

* 🧠 Turn-based gameplay with strategic decision-making
* 🦸 Multiple champion types (Hero, Villain, AntiHero)
* ⚔️ Unique abilities (Damaging, Healing, Crowd Control)
* 🎯 Area-of-effect mechanics and targeting system
* 🛡️ Status effects (Stun, Shield, Silence, Root, etc.)
* 🎮 Interactive GUI for gameplay visualization
* 👥 Two-player competitive mode

  🏗️ System Architecture

 # Core Engine

*  Game.java  – Main game logic and flow control
*  Player.java  – Player data and team management
*  PriorityQueue.java  – Turn order handling system
*  GameListener.java  – Event handling and interaction

 # Game Model

   Champions

* Hero, Villain, AntiHero classes with different behaviors
*  Champion.java  as the base class

   Abilities

*  Ability.java  (base class)
* Subclasses:

  * DamagingAbility
  * HealingAbility
  * CrowdControlAbility

   Effects System

* Status effects such as:

  * Stun, Shield, Silence, Root, Disarm, Dodge, SpeedUp
* Implemented using a flexible effect-based design

   World Elements

* Grid-based board system
* Covers and interactive objects
* Movement directions and conditions

 # Exception Handling

Custom exceptions for robust gameplay:

* InvalidTargetException
* NotEnoughResourcesException
* AbilityUseException
* UnallowedMovementException
* LeaderAbilityAlreadyUsedException

  🎨 GUI

* Implemented using Java-based GUI components
* Provides visual representation of:

  * Board state
  * Champions
  * Actions and abilities

  🛠️ Tech Stack

*   Language:   Java
*   Paradigm:   Object-Oriented Programming (OOP)
*   Concepts Applied:  

  * Inheritance & Polymorphism
  * Encapsulation
  * Exception Handling
  * Data Structures (Priority Queue)

  🎯 Learning Outcomes

* Designed a modular game engine using OOP principles
* Implemented complex game mechanics and rules
* Built reusable and scalable class hierarchies
* Developed structured exception handling for game logic

  👨‍💻 Team Project

Developed as part of a university coursework project (3rd semester) focusing on software engineering and object-oriented design.


