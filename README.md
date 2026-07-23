# 🌌 Planet Particle Animation

A mesmerizing 3D particle planet animation built with vanilla JavaScript and HTML5 Canvas. Watch a stunning cosmic scene with a rotating planet, orbital rings, satellites, shooting stars, nebula clouds, and more!

![Planet Animation Preview](https://img.shields.io/badge/Status-Active-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

## ✨ Features

### Visual Effects
- 🌍 **3D Rotating Planet** - 4000+ particles distributed evenly on a sphere using Fibonacci spiral
- 💍 **Orbital Rings** - Golden, shimmering ring system around the planet
- 🛰️ **Orbiting Satellites** - Two satellites with solar panels, blinking lights, and comet trails
- 🌟 **Shooting Stars** - Random meteors streaking across the sky
- 🌌 **Nebula Clouds** - Colorful, drifting cosmic clouds in the background
- ✨ **Atmospheric Glow** - Pulsing glow effect around the planet
- 🌈 **Dynamic Color Shifting** - Particles subtly change colors over time
- 🌙 **Realistic Sun/Moon** - Sun with animated rays, moon with craters (time-based)

### Interactive Features
- 🖱️ **Click to Explode** - Click anywhere to create colorful particle explosions
- 🔍 **Zoom** - Scroll up/down to zoom in/out (0.5x to 3x)
- ⌨️ **Keyboard Controls** - Arrow keys to manually rotate the view
- 🖐️ **Mouse Repulsion** - Move mouse near particles to see them react

## 🎮 Controls

| Input | Action |
|-------|--------|
| **Click** | Create particle explosion |
| **Scroll** | Zoom in/out |
| **Arrow Keys** | Rotate view |
| **Mouse Move** | Repel nearby particles |

## 🚀 Getting Started

### Quick Start
Simply open `planet-particles.html` in any modern web browser:

```bash
# Clone the repository
git clone https://github.com/antono4/PlanetParticleAnimation.git

# Navigate to folder
cd PlanetParticleAnimation

# Open in browser (macOS)
open planet-particles.html

# Open in browser (Linux)
xdg-open planet-particles.html

# Open in browser (Windows)
start planet-particles.html
```

### No Dependencies Required
This is a pure vanilla JavaScript project with no external dependencies. Just open the HTML file!

## 📱 Responsive Design

The animation automatically adjusts to different screen sizes:
- **Desktop**: 4000 planet particles, 3000 ring particles, 350 stars
- **Mobile**: Reduced particle count for smoother performance

## 🛠️ Technical Details

### Particle System
- **Fibonacci Spiral Distribution**: Ensures even particle distribution on sphere
- **3D Projection**: Orthographic projection with manual rotation controls
- **Depth Sorting**: Proper z-index rendering for 3D illusion
- **Performance Optimized**: Efficient rendering for smooth 60fps animation

### Color Palette
- **Planet**: Cyan & white tones (#4fc3f7, #00b0ff, #81d4fa)
- **Rings**: Gold & amber (#ffd54f, #ffca28, #ffe082)
- **Background**: Deep space (#050510, #1a1a2e)
- **Nebulas**: Purple, blue, pink, teal, orange

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📝 Credits

Created with ❤️ using vanilla JavaScript and HTML5 Canvas.

---

⭐ Don't forget to star this repo if you like it!
