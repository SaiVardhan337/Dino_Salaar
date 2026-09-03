<div align="center">

# 🏃‍♂️ SALAAR RUN

### Run. Jump. Slide. Survive.

**A Chrome Dino-style endless runner reskinned with Prabhas from _Salaar_.**

![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111)
![Dependencies](https://img.shields.io/badge/Dependencies-None-42b883?style=for-the-badge)
![Mobile](https://img.shields.io/badge/Mobile-Friendly-6366f1?style=for-the-badge)

</div>

---

## 🎮 About the game

**Salaar Run** is a fast, lightweight browser game inspired by Chrome's offline Dino Runner. Guide the hero through an endless desert, leap over waist-high cacti, and slide beneath birds flying at head level. The pace gradually increases, so every second survived becomes more intense.

Everything runs directly in the browser using one HTML file, HTML5 Canvas, vanilla JavaScript, and two local character sprite sheets—no framework, package installation, or build process required.

## ✨ Features

- 🏃 Smooth eight-frame running animation
- 🦘 Natural jump arc with dedicated airborne artwork
- 🛝 Animated slide sequence with a reduced collision hitbox
- 🌵 Randomized waist-high cactus obstacles
- 🐦 Head-level flying obstacles designed to be avoided by sliding
- ⚡ A noticeable 10% speed boost every 250 points, up to the maximum pace
- 🏆 Live score and persistent high score using `localStorage`
- 🔊 Procedural footsteps, jump, landing, slide, score, and collision sounds
- ⏸️ Pause and resume with `Esc` or the mobile pause button
- 📱 Responsive canvas with reliable gestures and dedicated mobile jump/slide buttons
- 🎯 Forgiving collision boxes for fair gameplay
- 🚫 No frameworks, build tools, or external runtime dependencies

## 🕹️ Controls

| Action | Keyboard | Mobile |
|---|---|---|
| Jump | `Space` or `↑` | Tap the game or tap `↑` |
| Slide | Hold `S` or `↓` | Swipe down, tap `↓`, or hold `↓` |
| Sound | Press `M` to mute/unmute | — |
| Pause/resume | `Esc` | Tap `⏸` or `▶` |
| Restart | `Space` or `↑` after collision | Tap after collision |

> Browser audio begins after your first keypress or tap because browsers block autoplay until the player interacts with the page.

## 🚀 Run locally

### Quick start

Clone the repository and open `index.html` in a modern browser:

```bash
git clone https://github.com/SaiVardhan337/Dino_Salaar.git
cd Dino_Salaar
open index.html
```

On Windows, replace the last command with:

```powershell
start index.html
```

### Local server

You can also serve the project locally:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## 📁 Project structure

```text
Dino_Salaar/
├── index.html
├── assets/
│   ├── character-actions.png   # Jump and slide poses
│   └── running-actions.png     # Eight-frame running cycle
├── README.md
└── .gitignore
```

## 🧰 Built with

- **HTML5 Canvas** for rendering and animation
- **Vanilla JavaScript** for game logic, input, physics, and collision detection
- **Web Audio API** for dependency-free procedural sound effects
- **CSS** for the responsive game frame and mobile layout
- **Local Storage API** for high-score persistence

## ☁️ Deploy to Vercel

This is a static site with no build command. Import this GitHub repository in Vercel and use:

| Setting | Value |
|---|---|
| Framework Preset | `Other` |
| Build Command | Leave empty |
| Output Directory | `.` |

Or deploy from the terminal:

```bash
npm install -g vercel
vercel --prod
```

## 🌐 Live demo

**Vercel:** `https://your-project-name.vercel.app`

_Replace the URL above after the first production deployment._

## 💡 Gameplay tips

1. Short, well-timed jumps are enough for the cacti.
2. Slide when a bird approaches the hero's head or shoulders.
3. Prepare for a 10% speed boost whenever the score crosses another 250 points.
4. Press `M` anytime if you prefer to play silently.

---

<div align="center">

Made for the love of endless runners and cinematic action. 🔥

<sub>This is a fan-made project. Character imagery belongs to its respective rights holders.</sub>

</div>
