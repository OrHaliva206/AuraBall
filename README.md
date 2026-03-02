# AuraBall

A sensory rehabilitation game built with HTML5 Canvas. Currently playable with keyboard (Space) and touch controls.

**Play now:** [orhaliva206.github.io/AuraBall](https://orhaliva206.github.io/AuraBall/)

## How It Works

1. **Login** — Create an account (stored locally) and view the leaderboard
2. **Calibration** — Hold Space (or touch on mobile) to fill the pressure gauge. Push the ball up to the target line to set your sensitivity
3. **Start** — Choose dominant hand, see your personal best, then play
4. **Game** — Hold Space / touch to make the ball rise, release to fall. Navigate through procedural gates for as long as you can
5. **Game Over** — View your score and best score, then replay or return home

## Features

- Single-file app (HTML + CSS + JS, no dependencies)
- Vertical pressure gauge with calibration midline target
- Test canvas to preview ball behavior before playing
- Procedural obstacle generation (top, bottom, middle gates)
- Difficulty scaling over time (speed increases, gaps shrink)
- Ball trail and glow effects
- Screen shake on collision
- Local auth with scoreboard
- Left/right hand mode toggle
- Mobile-optimized touch controls and physics
- Works on desktop and mobile browsers

## Controls

| Platform | Action |
|----------|--------|
| Desktop  | Hold **Space** to rise, release to fall |
| Mobile   | **Touch & hold** the lower screen area to rise, release to fall |

## Tech

- Vanilla JS, HTML5 Canvas
- No frameworks or build tools
- localStorage for user data and scores
- GitHub Pages for hosting
