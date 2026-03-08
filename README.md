# 🐍 Dual Snake

A single-player, dual-control snake game that tests your ambidexterity!

## How to Play

Control **two snakes simultaneously** using different hands:
- **Left Panel (Green Snake):** WASD keys
- **Right Panel (Red Snake):** Arrow keys

## Game Mechanics

- **Speed increases** as you eat more food and grow longer
- **Death mechanic:** When a snake dies, its body becomes scattered food on BOTH panels
- **Respawn:** The dead snake respawns after the survivor eats 5 food
- **Game Over:** When both snakes are dead simultaneously

## Goal

Keep both snakes alive as long as possible and rack up the highest combined score!

## Running the Game

Simply open `dual-snake.html` in any modern web browser. No server or installation needed!

```bash
# Or serve locally (optional)
python -m http.server 8000
# Then open http://localhost:8000/dual-snake.html
```

## Controls

| Action | Left Snake | Right Snake |
|--------|------------|-------------|
| Up | W | ↑ |
| Down | S | ↓ |
| Left | A | ← |
| Right | D | → |
| Restart | SPACE (after game over) | SPACE |

---

Built with HTML5 Canvas + vanilla JavaScript. No dependencies.
