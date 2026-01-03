# Laser Mirror Puzzle

A browser-based puzzle game where you guide a laser beam to its target by strategically placing mirrors while avoiding obstacles.

## Game Objective

Guide the red laser beam from the starting point to the green target by placing and rotating mirrors. The laser bounces off mirrors and gets blocked by circular obstacles. Solve puzzles using the fewest mirrors possible!

## How to Play

**Desktop:**
- Click to place a mirror
- Move mouse to rotate the mirror
- Click again to confirm placement

**Mobile:**
- Tap to place a mirror
- Drag to rotate the mirror
- Release to confirm placement

## Features

- **Progressive Difficulty:** Each level adds more obstacles
- **Puzzle Sharing:** Share custom puzzles via URL with friends
- **Score Tracking:** Challenge others to beat your mirror count
- **Undo/Reset:** Experiment freely with mirror placements
- **Instant Feedback:** See the laser path update in real-time

## Controls

- **Undo/Cancel:** Remove last mirror or cancel current placement
- **Reset:** Generate a new random puzzle
- **Share:** Create a shareable link for the current puzzle
- **Next Level:** Progress to the next difficulty level (after solving)

## Technical Details

- Pure HTML5 Canvas implementation
- No external dependencies
- Responsive design (desktop and mobile)
- URL-based puzzle encoding for sharing
- Physics-based laser reflection system

## Running the Game

Simply open `index.html` in any modern web browser. No build process or server required!

## Puzzle Sharing

When you share a puzzle, the obstacle configuration is encoded in the URL. Friends who open your link will face the exact same puzzle layout and can try to beat your mirror count.
