<div align="center">

# 🎮 Life @ AUST

**A 2D projectile-throwing arcade game built with the iGraphics library — a CSE1200 term project at Ahsanullah University of Science and Technology.**

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](LICENSE)
[![Language: C/C++](https://img.shields.io/badge/Language-C%2FC%2B%2B-00599C.svg?logo=cplusplus&logoColor=white)](#-built-with)
[![Built with: iGraphics](https://img.shields.io/badge/Built%20with-iGraphics-2ea44f.svg)](#-built-with)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-contributing)

</div>

---

## 📖 Project Introduction

Ahsanullah University of Science and Technology
Department of Computer Science and Engineering
Year 1, Semester 2
CSE1200 iGraphics Term Project

- **Section:** C
- **Group:** 02
- **Project Title:** LIFE@AUST
- **Project Submitted on:** October 4, 2021

**Group Members**

1. Tabassum Tara lamia — 200104128
2. Parvez Ahammed — 200104129
3. Chandrima sarker shipra — 200104131

**Project Supervisor**

Ashek Seum
Lecturer,
Department of Computer Science and Engineering,
Ahsanullah University of Science and Technology

---

## ✨ Gameplay / Features

Life @ AUST is a menu-driven arcade game where you aim and throw an object across three playable levels, using a velocity meter and direction controller to land hits while obeying projectile-motion physics.

- 🎯 **Projectile throwing** — adjust the angle and the speedometer/velocity bar, then throw an object that follows projectile motion (physics-based trajectory).
- 🧱 **Obstacles & collision** — moving obstacles per level with a collision controller.
- 🏆 **Three playable levels** — progress from level 1 → 2 → 3, carrying your score forward between levels.
- 👤 **Player profiles & high scores** — enter your name; scores are saved to file and shown in a descending high-score list.
- 💾 **Pause & resume** — the resume state is saved to file, so you can leave and continue later (with a user authenticator and a "name not found" screen).
- 🔊 **Sound effects** — audio cues where needed.
- 🌗 **Light / dark screens** — light and dark variants for the menu, story, controls, play, and high-score screens.
- 🎓 **Ending credits** — an end-of-game certificate / credits screen.

---

## 🚀 Built With

- **[iGraphics](LIFE@AUST/iGraphics%20Project/headers)** — a teaching graphics library (`iGraphics.h`) used at AUST for CSE1200.
- **C / C++** — game logic in `LIFE@AUST/iGraphics Project/LIFE@AUST.cpp` plus developer-written headers.
- **OpenGL / GLUT** — iGraphics is a wrapper over OpenGL and GLUT (ships with `GLUT32.DLL`).
- **Microsoft Visual Studio 2010** — Win32 project (`LIFE@AUST.sln`, Visual C++ Express 2010).

---

## 📦 Getting Started

This is a Windows / Visual Studio project that targets the iGraphics library.

### Prerequisites

- Windows
- **Microsoft Visual Studio 2010** (the project was built with VS 2010, version `10.0.40219.1 SP1Rel`)

### Setup

1. **Clone the repository.**

   ```bash
   git clone https://github.com/parvez-ahammed/life-at-aust.git
   ```

2. **Install the iGraphics dependencies.** Copy all the files from
   `1. Guidelines/Required Files` into the Windows SDK library folder:

   ```
   C:\Program Files (x86)\Microsoft SDKs\Windows\v7.0A\Lib
   ```

   > For a step-by-step walkthrough (including Visual Studio installation), see the guides in the **`1. Guidelines`** folder:
   > `0. VisualStudio_InstallationGuide.pdf`, `1. iDoc.pdf`, and `2. Advanced Functions iGraphics.pdf`.

3. **Open the solution.** Launch `LIFE@AUST/LIFE@AUST.sln` in Visual Studio 2010.

4. **Build & run.** Build the `iGraphics Project` (Win32, Debug or Release) and run it to start the game.

---

## 🎮 Screenshots

<p align="center">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_load.png" height="600">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_member.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_member_light.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_story.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_story_light.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screeen_play.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screeen_play_light.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_control.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_control_light.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_highscore.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_highscore_light.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_append_data.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_input.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_input_resume.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_level_1.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_level_2.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_level_3.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_name_not_found.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_resume.png" height="300">

<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_game_over.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/screen_go_level_2.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/Screen_go_level_3.png" height="300">
<img src="https://raw.githubusercontent.com/parvez-ahammed/life-at-aust/master/2.%20Game%20Shots/Screen_certificate.png" height="300">

</p>

---

## 🤝 Contributing

This is an archived university term project, but issues and pull requests are welcome. Please be respectful and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 📄 License

Licensed under the **GNU Affero General Public License v3.0** — see the [LICENSE](LICENSE) file for details.

© 2026 Parvez Ahammed
