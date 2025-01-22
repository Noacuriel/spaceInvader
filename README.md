# Space Invader - Final Project Noa Curiel and Arthur Friler 

## Description
This project is an implementation of the classic **Space Invader** game, developed as a final project for an Electrical Engineering lab course.
The game is designed using Verilog and simulates an interactive environment displayed through a VGA module.

## Main Features
- **Monster Matrix**:
  - A 16x8 matrix containing various types of monsters with different colors and shapes.
  - Each monster has a specific health value and attributes.
- **Player Logic**:
  - Allows player movement (left, right) controlled via input signals.
  - Tracks player health and manages collisions with enemy missiles.
- **Enemy Behavior**:
  - Monsters fire missiles at random intervals.
  - Collision detection between player, missiles, and defensive barriers.
- **Defensive Barriers**:
  - Four barriers that degrade when hit by enemy missiles.
- **Extra Life Mechanism**:
  - A random “rescue ball” grants extra life to a dying monster.
- **Player Health Tracker**:
  - Displays player health as a decreasing bar or counter.
- **Game Controller**:
  - Manages game state, including win/loss conditions and game flow.

## Technologies Used
- **Hardware Description Language**: Verilog
- **Development Environment**: Quartus Prime
- **Simulation and Debugging**: Signal Tap Logic Analyzer
- **Display Module**: VGA

## Project Structure
- **Player Logic Module**:
  - Handles player movement and interactions.
- **Monster Matrix Module**:
  - Manages monster behavior and states.
- **Collision Detection Module**:
  - Detects and processes collisions between all entities.
- **Random Generator Module**:
  - Generates random events, such as missile firing.
- **Game Controller Module**:
  - Oversees the game’s state and progression.


