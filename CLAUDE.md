# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is "Flappy Pink" - a browser-based HTML5 game similar to Flappy Bird, built as a single-file application with a cute pink theme and friendly gameplay mechanics.

## Architecture

- **Single HTML file**: `index.html` contains all HTML, CSS, and JavaScript inline
- **Self-contained**: No external dependencies or build tools
- **Canvas-based game**: Uses HTML5 Canvas API for rendering
- **Asset-driven**: Game assets (images/audio) loaded from `assets/` directory

## Key Components

### Game Structure (all in index.html)
- **CSS Variables** (lines 9-18): Color theme using CSS custom properties in `:root`
- **Game Canvas** (line 94): 420x680px canvas element
- **Game State** (lines 131-137): Hero object, pipes array, stars array, scoring
- **Game Loop** (lines 306-322): Main animation loop using `requestAnimationFrame`
- **Physics Engine** (lines 221-275): Gravity, collision detection, movement

### Core Game Mechanics
- **Hero Movement**: Gravity-based physics with jump controls
- **Pipe Generation**: Procedurally spawned obstacles with gaps
- **Star Collection**: Collectible items for bonus points
- **Easy Mode**: Collision assistance (bounces instead of game over)
- **Scoring**: Points for passing pipes + bonus points for stars

## Development Commands

**Run the game**: Open `index.html` in any modern web browser

**No build process**: This is a static HTML file with no compilation needed

## Customization Points

### Visual Customization
- **Colors**: Modify CSS variables in `:root` (lines 9-18)
- **Character**: Replace `assets/hero.png` (maintain ~64x64 proportions)
- **Background**: Replace `assets/background.png`

### Gameplay Tuning
- **Difficulty**: Adjust `gap` value in `spawnPipe()` (line 160)
- **Speed**: Change pipe movement speed (line 232, currently 2.4)
- **Physics**: Modify gravity `hero.g` (line 131, currently 0.48)
- **Jump strength**: Adjust `hero.jump` (line 131, currently -7.2)

## File Dependencies

All assets must exist in `assets/` directory:
- `background.png`, `hero.png`, `heart.png`, `star.png`, `sparkle.png`
- `logo.png`, `favicon.png` 
- `star.wav` (audio file)

Missing assets will cause rendering issues but won't break core game functionality.