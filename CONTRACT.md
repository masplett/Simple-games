# Dual Snake Game — CONTRACT

## Deliverable
Single-file HTML5 Canvas game: `dual-snake.html`

## Core Mechanics
- Two panels side-by-side (50/50 split)
- Left snake: WASD controls
- Right snake: Arrow key controls
- Both snakes controlled simultaneously by one player
- Speed increases: +10% every 3 food eaten, +2% per body segment
- Death mechanic: Dead snake's body becomes scattered food on BOTH panels
- Respawn: Dead snake respawns after survivor eats 5 food
- Game over when both snakes dead simultaneously

## Acceptance Criteria (Testable)

| # | Criteria | Test Method |
|---|----------|-------------|
| 1 | WASD controls left snake, arrows control right snake | Manual: Press keys, verify movement |
| 2 | Snakes move continuously, not just on keypress | Visual: Snakes auto-move |
| 3 | Food spawns randomly, never on snake body | Test: Play 10 foods, verify placement |
| 4 | Snake grows +1 segment per food eaten | Count segments before/after |
| 5 | Speed increases with food count and length | Timer: Measure interval decrease |
| 6 | Wall collision = death, body becomes 3-5 food items | Kill snake, verify food scatter |
| 7 | Dead snake respawns after survivor eats 5 food | Count foods, verify respawn |
| 8 | Game over when both snakes dead | Kill both, verify game over screen |
| 9 | Score displays and increments correctly | Check score matches food eaten |
| 10 | Game restarts on keypress after game over | Press key, verify fresh game |

## File Structure
```
dual-snake.html  (self-contained, no external deps)
```

## Timeline
Build + test: ~15-20 minutes with checkpoints

---
**Status:** Pending approval
