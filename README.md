# LearningSprint3_Problem3

## Asterisk Web Port

This project is a browser-based single-player port of **Asterisk**, recreated in HTML5 Canvas and JavaScript as part of **SE 4900 Learning Sprint #3**. The original goal was to take inspiration from the older C# WinForms version of the game and adapt it into a fully playable web version contained in a single `index.html` file.

In this version, the player controls a spaceship and must navigate through floating cloud-like obstacles while reaching the exit gap on the right side of the screen to advance to the next level. The game becomes more difficult over time through increased speed and tighter obstacle patterns.

## How to Play

- Press **Start Game** to begin or skip the countdown
- Hold **Enter** to make the spaceship rise
- Release **Enter** to let the spaceship fall
- Avoid hitting walls or cloud obstacles
- Pass through the glowing exit gap on the right side to advance to the next level
- If you crash, the game shows **Game Over** and allows you to restart

## Features Implemented

### Core mechanics
- Single-player browser game built with HTML, CSS, and JavaScript
- HTML5 Canvas rendering
- Enter key controls rise and fall
- Level progression through the right-edge exit gap
- Restart after game over

### Difficulty progression
- Increasing movement speed across levels
- Obstacle placement becomes more challenging over time
- Exit gap positioning changes by level

### Creative enhancements
- Spaceship player design instead of a simple square
- Floating cloud-like obstacles
- Horizontal animated exhaust trail
- Color-changing background effects
- Countdown before each round
- Score counter and level display
- Persistent high score using `localStorage`
- Sound effects for crash and level-up

## Files

- `index.html` — complete playable game in one self-contained file
- `README.md` — project overview and instructions

## How to Run

Run locally
1. Download or clone the repository
2. Open `index.html` in a web browser

## AI Usage

This README was initially generated with AI assistance and then reviewed, edited, and validated for accuracy. AI was also used during development to help translate the original game concept into HTML5 Canvas code, suggest enhancements, and assist with debugging. Final decisions, corrections, and validation were completed manually.

## Repository Link

GitHub Repository:
https://github.com/ptran21/LearningSprint3_Problem3