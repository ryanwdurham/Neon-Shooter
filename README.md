# ⚡ NEON SHOOTER ⚡

A fast-paced, browser-based aim training game with stunning neon visuals, dynamic backgrounds, and addictive gameplay mechanics.


## 🎮 Play Now

[**Play the Game →**](https://ryanwdurham.github.io/Neon-Shooter/)

## ✨ Features

### 🎯 Core Gameplay
- **Progressive Difficulty** - Targets get faster and more challenging as time progresses
- **Combo System** - Build hit streaks for massive score multipliers and bonuses
- **Multiple Target Types** - 9 unique shapes with varying sizes, speeds, and point values
- **Special Targets**:
  - 🌟 **Golden Targets** - 2x points (rare spawn)
  - 🎁 **Powerup Targets** - Rainbow stars with special abilities
  - ⚠️ **Trap Targets** - Red/black with yellow stripes (avoid these!)

### 💫 Powerups
- **⏱️ Slow Time** (5 seconds) - All targets move 70% slower
- **❄️ Freeze** (3 seconds) - Stops all target movement
- **💥 Clear Screen** (instant) - Removes all targets + bonus points

### 🎨 Dynamic Visuals
- **6 Neon Background Themes** - Automatically changes 4 times per game
- **Smooth Animations** - 60 FPS canvas rendering with particle effects
- **Screen Glow Effects** - Pulsing effects on combo milestones (10x, 20x, 30x)
- **Responsive Design** - Works on desktop, tablet, and mobile

### 🎵 Audio System
- **Background Music** - Electronic/techno soundtrack with smooth fade-out
- **Sound Effects** - Explosions, combo notifications, clock ticking
- **Independent Controls** - Separate mute toggles for music and SFX

### 🏆 Game Modes

#### Easy Mode
- ⏰ 60 seconds
- 📏 20% larger targets
- 🐌 30% slower movement
- ⚠️ 10% trap spawn rate
- 🎁 Combo bonuses at 10, 20, 30 hits

#### Normal Mode
- ⏰ 60 seconds
- 📏 Standard target sizes
- 🏃 Normal speed
- ⚠️ 15% trap spawn rate
- 🎁 Combo bonuses at 10, 15, 20, 25 hits

#### Hard Mode
- ⏰ 45 seconds
- 📏 20% smaller targets
- ⚡ 40% faster movement
- ⚠️ 20% trap spawn rate
- 🎁 Combo bonuses at 15, 25, 40, 60 hits

### 🎖️ Progression System
- **High Score Tracking** - Top 5 scores saved locally
- **Max Combo Display** - Track your best hit streak
- **Accuracy Stats** - See your hit percentage
- **Score Medals** - 🥇 🥈 🥉 for top 3 scores


## 🎯 How to Play

### Controls
- **Mouse**: Click on targets to shoot
- **Touch**: Tap targets on mobile devices
- **SPACE**: Pause/Resume game
- **🎵 / 🔊**: Toggle music/sound effects

### Scoring
- **Small targets** = More points (150 pts)
- **Medium targets** = Moderate points (65 pts)
- **Large targets** = Fewer points (25 pts)
- **Golden targets** = 2x points
- **Traps** = -60 points (avoid!)

### Combo System
- Hit targets consecutively without missing
- Earn bonus points at combo milestones
- Missing a target or hitting a trap resets your combo
- Higher combos = higher point multipliers (up to 12% per combo level)

### Tips for High Scores
1. ✅ Prioritize small, fast targets for max points
2. ✅ Build combos for multiplier bonuses
3. ✅ Grab powerups strategically
4. ✅ Avoid traps at all costs
5. ✅ Use Freeze powerup on small targets
6. ✅ Save Clear Screen for overwhelming moments

## 🛠️ Technical Details

### Built With
- **HTML5 Canvas** - High-performance 2D rendering
- **Vanilla JavaScript** - No dependencies!
- **CSS3** - Modern animations and effects
- **Web Audio API** - Multi-channel sound system

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- 60 FPS rendering on modern hardware
- Optimized particle system
- Efficient canvas clearing
- Hardware-accelerated CSS animations
- Multi-channel audio pooling (15 simultaneous sounds)

### Key Technologies
- `requestAnimationFrame` for smooth 60 FPS gameplay
- `localStorage` for persistent high scores
- Device pixel ratio scaling for high-DPI displays
- Touch and mouse event handling
- CSS gradient animations
- Audio channel pooling for performance

## 📁 Project Structure

```
neon-shooter/
├── index.html              # Main game file (all-in-one)
├── sounds/                 # Audio assets
│   ├── explosion1.mp3     # Hit sound effect
│   ├── electronic2.mp3    # Background music
│   └── clock.wav          # Final countdown clock
└── README.md              # This file
```

## 🎨 Customization

### Change Background Themes
Edit the `BG_THEMES` array in the code to add/modify background colors:
```javascript
const BG_THEMES = [
    {
        name: 'Your Theme',
        gradient1: 'rgba(R, G, B, 0.3)',
        gradient2: 'rgba(R, G, B, 0.3)',
        gradient3: 'rgba(R, G, B, 0.2)'
    }
];
```

### Adjust Difficulty
Modify `DIFFICULTY_SETTINGS` to tweak game balance:
```javascript
const DIFFICULTY_SETTINGS = {
    easy: {
        time: 60,
        sizeMultiplier: 1.2,
        speedMultiplier: 0.7,
        // ... more settings
    }
};
```

### Add Custom Sounds
Replace files in the `sounds/` folder with your own audio files (keep the same names).

## 🐛 Known Issues

- First game may have audio delay on some browsers (autoplay policy)
- **Fix**: Click anywhere on the page before starting

## 🔮 Future Enhancements

- [ ] Online leaderboards
- [ ] Achievement system
- [ ] More powerup types
- [ ] Target skins/themes
- [ ] Daily challenges
- [ ] Sound effect customization
- [ ] Endless mode
- [ ] Two-player mode
- [ ] Mobile app version

## 📝 Changelog

### Version 1.0.0 (Current)
- ✅ Initial release
- ✅ 3 difficulty modes
- ✅ Powerup system
- ✅ Dynamic backgrounds
- ✅ High score tracking
- ✅ Smooth game ending
- ✅ Mobile support
- ✅ Pause functionality

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Ideas
- Add new powerup types
- Create new background themes
- Improve mobile controls
- Add accessibility features
- Optimize performance
- Add new target shapes

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- Website: [your-website.com](https://your-website.com)

## 🙏 Acknowledgments

- Inspired by aim training games like Aim Lab and KovaaK's
- Neon aesthetic inspired by cyberpunk and synthwave culture
- Built with ❤️ and lots of ☕

## 📞 Support

If you encounter any issues:
1. Check the [Known Issues](#-known-issues) section
2. Open an issue on GitHub
3. Contact: your-email@example.com

---

**⭐ If you enjoy the game, please give it a star on GitHub! ⭐**

Made with 💙 by [Your Name]
