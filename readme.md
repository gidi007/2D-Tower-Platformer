# 🎮 JavaScript Tower Platformer

<p align="center">
  <img src="/api/placeholder/800/400" alt="Tower Platformer Banner">
  <br>
  <em>Scale the rotating tower, dodge monsters, and reach for the stars!</em>
</p>

## 🌟 Overview

A modern HTML5 reimagining of the classic C64 game "Nebulus" - climb a mesmerizing rotating tower while avoiding obstacles and enemies. Built entirely with vanilla JavaScript, HTML5 Canvas, and CSS.

<p align="center">
  <a href="#play">🎮 Play Now</a> •
  <a href="#about">📖 Learn More</a> •
  <a href="#source">💻 View Source</a>
</p>

## 🎯 Features

- Smooth tower rotation mechanics
- Platform-based gameplay
- Enemy AI system
- Responsive controls
- Pure JavaScript implementation
- Canvas-based rendering

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅      |
| Firefox | ✅      |
| Safari  | ✅      |
| Edge    | ✅      |
| Opera   | ✅      |

> Requires a modern browser with HTML5 Canvas support

## 🚀 Quick Start

1. Clone the repository
2. Serve with any web server
3. Open in your browser
4. Start climbing! 🧗‍♂️

## 🎯 Roadmap

### Gameplay Enhancements
- [ ] Level exit system
- [ ] Multiple challenging levels
- [ ] Dissolving platforms
- [ ] Elevator mechanics
- [ ] Shortcut doors
- [ ] Countdown timer
- [ ] Game menu interface

### Technical Enhancements
- [ ] Mobile touch controls
- [ ] Sound effects & music
- [ ] Improved sprite animations
- [ ] Enhanced visual effects

## 🔧 Technical Debt & Improvements

### Architecture
- Implement Finite State Machine (FSM) for player states:
  - Standing
  - Moving (Left/Right)
  - Falling
  - Climbing
  - Hurt states

### Optimization
- Convert monster cell storage to array structure
- Implement image-based rendering for:
  - Tower gradients
  - Platform elements
- Create direction-agnostic monster sprites

### Bug Fixes
- Address Firefox/IE ground rendering gap
- Optimize image wrapping boundaries

## 🛠️ Development

```bash
# Start local server
python -m http.server 8000  # or any preferred method

# Access the game
open http://localhost:8000
```

## 🎨 Styling Guide

- Platform colors: `#FF4136` (danger), `#2ECC40` (safe)
- Background gradient: `linear-gradient(#1a1a1a, #4a4a4a)`
- Font family: 'Press Start 2P' for retro feel

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch
3. Implement your changes
4. Submit a pull request

## 📝 License

This project is open source and available under the MIT License.

<p align="center">
  <strong>Ready to start climbing? The tower awaits! 🏰</strong>
</p>

---

<p align="center">
  Made with 💻 and nostalgia by Gideon Bawa
</p>