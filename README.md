# Dead Commits

**Dead Commits** is a minimalist browser strategy game inspired by the visual language of the GitHub contribution graph.  
Built as an experimental project out of curiosity, it explores how familiar developer metaphors (commits, conflicts, streaks, energy) can become core game mechanics.

## Play

This project is intended to be hosted on **GitHub Pages**.  
Open the deployed page and play directly in your browser.

## Gameplay Overview

- You start with a “dead” contribution grid.
- Click gray cells to **plant commit seeds** (costs energy).
- Live cells can be boosted and will **spread** over time.
- Red cells represent **merge conflicts** and can corrupt nearby cells if ignored.
- Keep the graph alive while managing limited energy and rising conflict pressure.

## Win / Lose Conditions

- **Win:** resurrect at least **60%** of the grid.
- **Lose:** conflicts corrupt **30%** of the grid.

## Controls

- **Click dead cell:** resurrect a commit
- **Click live cell:** boost cell level
- **Click conflict cell:** resolve one conflict
- **R:** resolve all active conflicts
- **P:** purge/reset the grid state
- **N:** start a new game

## Features

- GitHub-style 12-month contribution grid (53 × 7)
- Energy-based decision making (seed vs boost)
- Autonomous growth/spread simulation
- Conflict spawn + cascade pressure system
- Score, streak, resurrected count, and conflict tracking
- Lightweight single-file implementation (HTML/CSS/JS)

## Tech Stack

- **HTML5**
- **CSS3** (custom styling and animations)
- **Vanilla JavaScript** (game loop and state management)

## Project Status

Experimental and actively tweakable.  
The current version focuses on game feel, visual clarity, and core loop balancing.

## Roadmap Ideas

- Difficulty presets (casual / normal / hard)
- Persistent high scores
- Mobile-first control tuning
- Optional sound design and accessibility settings
- Additional mechanics (power-ups, special events, daily challenge mode)

## License

No license is currently defined. Add a `LICENSE` file if you want to make usage terms explicit.
