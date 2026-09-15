# لعبة الثعبان 🐍

An interactive Snake game in Arabic with modern features and smooth gameplay.

## Features ✨

- **Smooth Controls**: Keyboard arrows or touch-friendly buttons
- **Pause/Resume**: Pause the game anytime with the pause button
- **High Score Tracking**: Automatically saves your best score using localStorage
- **Difficulty Levels**: Choose between Easy, Medium, and Hard
  - 🟢 **Easy**: 150ms per frame
  - 🟡 **Medium**: 100ms per frame (default)
  - 🔴 **Hard**: 60ms per frame
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Beautiful UI**: Dark theme with neon green accents
- **RTL Support**: Full Arabic language support with right-to-left layout

## How to Play 🎮

1. **Start**: The game begins automatically when you open it
2. **Move**: Use arrow keys or tap the directional buttons
3. **Eat**: Move the snake head to the red food squares
4. **Survive**: Don't hit the walls or yourself
5. **Score**: Each food eaten increases your score by 1

## Controls 🕹️

| Method | Controls |
|--------|----------|
| **Keyboard** | ⬆️ ⬅️ ⬇️ ➡️ Arrow keys |
| **Touch** | Tap direction buttons on screen |
| **Pause** | Click pause button or press [Space] |
| **Reset** | Click new game button |

## Game Mechanics 📋

- ✅ Prevents 180° instant death (can't turn directly backward)
- ✅ Collision detection for walls and self
- ✅ Smooth queued direction input
- ✅ Food spawns randomly on grid
- ✅ Score updates in real-time
- ✅ High score persists between sessions

## Technical Stack 🛠️

- **HTML5**: Game structure
- **CSS3**: Responsive styling with animations
- **Vanilla JavaScript**: Game logic and canvas rendering
- **LocalStorage**: High score persistence

## Installation 📦

Simply open `index.html` in any modern web browser. No dependencies required!

Or play it live on GitHub Pages:
```
https://cloroxaldressi-boop.github.io/snake-game/
```

## File Structure 📁

```
snake-game/
├── index.html    # Complete game (HTML + CSS + JavaScript)
└── README.md     # This file
```

## Browser Compatibility 🌐

- Chrome/Chromium ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## Tips for High Scores 🏆

1. **Start on Medium** for balanced difficulty
2. **Plan ahead** - don't make reactive decisions
3. **Use corners** - trap food near walls for easier collection
4. **Take your time** - Easy mode is great for practice
5. **Progressive difficulty** - master each level before advancing

## Future Enhancements 🚀

Potential features for future updates:
- Sound effects and background music
- Multiple difficulty presets
- Leaderboard system
- Different game modes
- Power-ups and obstacles
- Mobile app version

## License 📜

This project is open source and available for personal and educational use.

---

**Enjoy the game! 🎮** 

Made with ❤️ for Arabic gaming enthusiasts
