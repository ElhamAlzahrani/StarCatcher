# Star Catcher ⭐👾

A 2D arcade game built with **C++ and OpenGL (GLUT)** as a Computer Graphics course project.

Catch the falling yellow stars, avoid the red ones, and reach 500 points before the 60 seconds run out.
[▶ Watch the gameplay demo](StarCatcherVideo.mp4)
## 🎮 Gameplay

- Catch **yellow stars** to earn 10 points each.
- Touch a **red star** and the mission fails instantly.
- Reach **500 points** to win before the timer hits zero.

## Controls

| Key | Action |
|-----|--------|
| Arrow keys | Move the player |
| Mouse | Player follows the cursor |
| Space | Start / continue / restart |
| P | Pause |
| Z / X | Zoom in / out |
| Esc | Quit |

## Features

- Four scenes: start screen, how-to-play, gameplay, and game over
- Custom-drawn player and rotating stars using OpenGL primitives
- Textured background and pause screen (custom BMP loader)
- Background music and win/lose sound effects
- Score, countdown timer, collision detection, and zoom

## Requirements

- Windows
- Visual Studio
- GLUT / freeglut set up for your project

## How to run

1. Create a new C++ project in Visual Studio with GLUT/freeglut configured.
2. Add `StarCatcher.cpp` to the project.
3. Put these files in a folder on your computer:
   `audio.wav`, `win.wav`, `lose.wav`, `background.bmp`, `pp (1).bmp`
4. In `StarCatcher.cpp`, update the file paths (in `playMusic`, `playWinSound`, `playLoseSound`, and `init`) so they point to the folder from step 3. The paths currently point to the author's computer.
5. Build and run (F5).

## Team

This was a group project for our Computer Graphics course.

- Elham Alzahrani
- Jana Haroun
- Maareb Felemban
- Aryam Alameer
