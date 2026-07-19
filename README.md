# 👻 Phantom Vector

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E.svg)](https://www.javascript.com)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/yourusername/phantom-vector/pulls)

> A cyberpunk reimagining of the classic arcade game with time-warping mechanics, hyperspace jumps, and a stunning galactic nebula backdrop. Built entirely with vanilla JavaScript and HTML5 Canvas.

<p align="center">
  <img src="screenshots/gameplay.gif" alt="Phantom Vector Gameplay" width="600">
</p>

## 🎮 Play Now

**▶ [Play Phantom Vector Online](https://yourusername.github.io/phantom-vector)**

Works on desktop (keyboard/mouse) and mobile (touch controls)!

---

## ✨ Features

### Core Gameplay
- **Classic Asteroid Destruction** - Blast apart procedurally generated asteroids
- **Progressive Difficulty** - 8 levels of increasing challenge
- **Combo System** - Chain kills together for score multipliers up to 10x
- **3 Lives System** - Survive as long as you can

### Temporal Abilities
- ⏱️ **Time Warp** - Slow down time, freeze enemies for 1.5 seconds
- 🌌 **Hyperspace Jump** - Create a wormhole that pulls in objects and grants temporary invincibility
- 🛡️ **Shield Power-up** - Temporary protection from asteroid collisions
- ⚡ **Rapid Fire** - Triple-shot spread pattern

### Visual Experience
- **Neon Vector Bloom** - Intense glow effects on all game objects
- **Chromatic Aberration** - RGB split effects during explosions and special abilities
- **Velocity Trails** - Dynamic trailing effects on ship and asteroids
- **Galactic Nebula Background** - Procedurally generated cosmic environment with:
  - 300+ twinkling parallax stars
  - Animated nebula cloud formations
  - Gas filaments and dark matter wisps
  - Energy rifts and cosmic dust
- **Screen Shake** - Impact feedback for explosions and collisions
- **Cyberpunk Grid** - Reactive background grid that warps during special abilities

### Audio (Web Audio API)
- **Dynamic Engine Sound** - Continuous synth that modulates with ship acceleration
- **Retro Laser SFX** - Classic arcade-inspired firing sounds
- **Time Warp Bass Drop** - Deep frequency sweep on activation
- **Hyperspace Whoosh** - Rising sawtooth wave with filter sweep
- **Combo Arpeggios** - Escalating pitch tones for high combos
- **Explosion Noise** - Procedurally generated white noise bursts

### Technical Highlights
- **Zero Dependencies** - Pure vanilla JavaScript, no frameworks or libraries
- **Object Pooling** - Pre-allocated arrays for bullets, particles, and explosions
- **Offscreen Canvas Rendering** - Nebula background rendered to separate canvas
- **Multi-Touch Support** - Properly isolated touch tracking for mobile controls
- **Virtual Joystick** - On-screen joystick with visual feedback
- **Responsive Design** - Adapts to any screen size
- **PWA Ready** - Can be installed as a standalone app

---

## 🎯 How to Play

### Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| **Move** | Click & drag left half of screen | Virtual joystick |
| **Fire** | `Spacebar` | ⚡ Button |
| **Time Warp** | `Q` key | ⏱️ Button |
| **Hyperspace** | `E` key | 🌌 Button |

### Tips
- Chain asteroid kills quickly to build your combo multiplier
- Use Time Warp to freeze dangerous asteroid clusters
- Hyperspace clears all bullets and grants brief invincibility
- Collect power-ups to recharge your special abilities
- Watch your charge meters - Time Warp and Hyperspace require 50% energy

---

## 🚀 Quick Start

### Play Online
Just open `index.html` in any modern browser!

### Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/phantom-vector.git

# Navigate to the directory
cd phantom-vector

# Start a local server (choose one)
python -m http.server 8000
# or
npx serve .
# or
php -S localhost:8000

# Open in browser
open http://localhost:8000