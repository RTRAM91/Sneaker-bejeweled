# Sneaker Bejeweled 👟

A fun twist on the classic Bejeweled match-3 game featuring sneakers instead of gems!

## Features

- **6x6 Game Grid** - Classic match-3 gameplay
- **Swap Mechanics** - Click two adjacent sneakers to swap them
- **Match Detection** - Automatically detects matches of 3 or more
- **Cascading Matches** - Matches trigger gravity, creating chain reactions
- **Scoring System** - Earn 10 points per sneaker cleared
- **Level Progression** - Level increases every 100 points
- **Move Counter** - Track your moves

## How to Play

1. **Open** `index.html` in your web browser
2. **Click** two adjacent sneaker tiles to swap them
3. **Match** 3 or more of the same sneaker type in a row or column
4. **Clear** matched sneakers to score points and trigger cascades
5. **Progress** through levels by earning points

## Game Rules

- Sneakers fall downward when tiles below them are cleared (gravity)
- Clearing a group triggers cascades, which can create chain reactions
- Each move counts toward your total moves
- Score increases by 10 points per sneaker cleared
- Level 1 starts at 0 points, increases every 100 points

## Sneaker Types

- 👟 Black Sneaker
- 🟦 Blue
- 🟥 Red  
- 🟨 Yellow
- 🟩 Green
- ⚪ White

## Technologies

- **Phaser 3** - Game framework
- **HTML5 Canvas** - Rendering
- **Vanilla JavaScript** - Game logic

## Installation & Running

No installation needed! Just open `index.html` in any modern web browser.

## Game Loop

The game follows this sequence:
1. User selects first tile
2. User selects adjacent tile to swap
3. Tiles swap positions
4. Check for matches (3+ in a row/column)
5. Remove matched tiles and increase score
6. Apply gravity (tiles fall down)
7. Repeat match checking until no more matches found
8. Refill empty spaces with new random sneakers
9. Return to step 1

Enjoy your sneaker matching adventure! 🎮
