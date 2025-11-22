# asteroids — simple OOP example
A small, self-contained reimplementation of the classic Asteroids game intended as an object‑oriented programming example. The project demonstrates clean separation of responsibilities across small classes (Ship, Asteroid, Bullet, Game, etc.) and shows basic game loop structure using Pygame.

## Features
- Minimal playable Asteroids: ship movement, shooting, asteroid spawning and splitting, simple collision handling.
- Focus on OOP concepts: encapsulation, single responsibility, composition, and simple inheritance where appropriate.
- Easy to read, modular code suitable for learning and modification.

## Requirements
- Python 3.12
- UV venv
    - pygame

## Controls
- WASD: rotate/thrust
- Space: fire

## Learning goals
- Understand how to model game entities as classes
- See how responsibilities are split between update/render and collision logic
- Use a simple game loop and event handling with Pygame