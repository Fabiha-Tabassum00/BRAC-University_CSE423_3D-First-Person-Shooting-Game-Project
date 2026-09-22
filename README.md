# 3D Shooter Game

A 3D first-person shooter built with **Python and OpenGL (PyOpenGL / GLUT)** for a Computer Graphics course. The player navigates a city-style grid, fights through waves of enemies, collects ammo, and faces a final boss.

## Gameplay

- **Open city grid** with buildings, streets, street lamps, and trees for cover and navigation.
- **Wave-based combat** — enemies arrive through a spawner in escalating waves, increasing in number and difficulty.
- **Boss fight** — the final wave introduces a powerful boss; defeating it completes the game.
- **Resource collection** — replenish ammo by defeating enemies and opening treasure boxes placed around the map.
- **Weapons** — a limited bullet supply plus throwable grenades, so ammo management matters.
- **Health system** — the player has hearts and can be damaged by enemies.

## Controls

| Input | Action |
|-------|--------|
| `W` / `S` | Move forward / backward |
| `A` / `D` | Turn and strafe left / right |
| Left click | Shoot a bullet |
| Right click | Throw a grenade |
| Arrow keys | Adjust camera height and position |
| `C` | Cheat: refill health, ammo, and grenades |
| `R` | Restart after game over or victory |

## Requirements

- Python 3.x
- PyOpenGL

Install the dependency:
```bash
pip install PyOpenGL PyOpenGL_accelerate
```

## Running

```bash
python 3D-Shooter-Game-GLU.py
```

## Author

**Fabiha Tabassum Poroma**
