# TypeMaster Pro 🎮⚡

A modern, high-performance typing speed game built with vanilla HTML, CSS, and JavaScript. Test your typing skills across multiple difficulty levels and game modes with stunning visual effects and real-time statistics.

## Features ✨

### 🎯 Multiple Game Modes
- **Words Mode**: Type individual words as quickly and accurately as possible
- **Sentences Mode**: Challenge yourself with full sentences for more complex typing

### 📊 Three Difficulty Levels
- **Easy** (60s): Perfect for beginners - 100+ simple words and sentences
- **Medium** (45s): Intermediate challenge - 140+ medium-length words
- **Hard** (30s): Expert level - 120+ complex vocabulary and advanced sentences

### 🎨 Theme System
- **Dark Theme** (Default): Classic dark mode
- **Neon**: Cyberpunk-inspired cyan and blue
- **Sunset**: Warm orange and red tones
- **Forest**: Natural green palette
- **Ocean**: Cool blue ocean vibes

### 📈 Real-Time Statistics
- **WPM**: Words per minute calculation
- **Accuracy**: Real-time accuracy percentage
- **Combo**: Track your consecutive correct words
- **Score**: Points with combo multipliers
- **Progress Bar**: Visual time remaining indicator

### 🔊 Audio Feedback
- Success sound (C5 note) for correct words
- Error sound for mistakes
- Start/End game sounds
- Toggle audio on/off with the sound button

### 📱 Responsive Design
- Works seamlessly on desktop and mobile devices
- Touch-friendly controls
- Optimized for all screen sizes

## How to Play 🎮

1. **Select Difficulty**: Click the difficulty button to choose between Easy, Medium, or Hard
2. **Choose Mode**: Switch between Words or Sentences mode
3. **Pick a Theme**: Click any theme button to change the visual style
4. **Start Game**: Click "Start Game" to begin
5. **Type Fast**: Type the displayed word/sentence as quickly and accurately as possible
6. **Beat the Clock**: Complete as many words as you can before time runs out
7. **View Results**: Your final score and statistics appear when time expires

## Game Mechanics ⚙️

### Scoring System
- **Base Points**: Character count × Level Multiplier
- **Combo Bonus**: Every 5 correct words grants +50% bonus on base points
- **Level Multipliers**: 
  - Easy: 1x
  - Medium: 1.5x
  - Hard: 2x

### Time Limits
- Easy: 60 seconds
- Medium: 45 seconds
- Hard: 30 seconds

### Accuracy Calculation
- Tracked based on correct keystrokes vs. total keystrokes
- Real-time feedback with visual indicators

## Technical Stack 🛠️

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with:
  - CSS Variables for theming
  - Flexbox & Grid layouts
  - Animations & transitions
  - Glassmorphism effects
  - Gradient backgrounds
- **Vanilla JavaScript**: 
  - No external dependencies
  - Web Audio API for sound effects
  - Event-driven architecture
  - Class-based game logic

## File Structure 📁

```
typing-speed/
├── modern_typing_game.html   # Main game file (all-in-one)
├── vercel.json               # Vercel deployment configuration
└── README.md                 # This file
```

## Deployment 🚀

### Deploy on Vercel (Recommended)
1. Push this repository to GitHub
2. Visit [vercel.com](https://vercel.com)
3. Click "Add New" → "Project"
4. Import the `CTIVO/typing-speed` repository
5. Vercel auto-detects `vercel.json` configuration
6. Click "Deploy" — your game goes live!

### Deploy Locally
Simply open `modern_typing_game.html` in your web browser. No server required!

## Performance Optimizations ⚡

- Single HTML file for quick loading
- CSS animations use GPU acceleration
- Efficient game loop with 100ms update interval
- Audio context suspension handling for battery efficiency
- Debounced theme switching

## Browser Support 🌐

- Chrome/Chromium (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers with Web Audio API support

## Future Enhancements 🔮

- [ ] Leaderboard system
- [ ] User accounts & statistics tracking
- [ ] Multiplayer mode
- [ ] Custom word lists
- [ ] Achievements & badges
- [ ] Keyboard sound effects
- [ ] Dark/Light mode toggle
- [ ] Language selection
- [ ] Speed progression tracking

## Credits 👤

**Created by**: CTIVO KARIS

## License 📄

This project is open source and available for personal and educational use.

## Tips for High Scores 💡

1. **Warm up**: Start with Easy mode to get comfortable
2. **Focus on accuracy**: Accuracy % contributes to your WPM score
3. **Build combos**: Consecutive correct words grant bonus points
4. **Practice regularly**: Improve your muscle memory over time
5. **Use themes**: Switch themes to stay visually engaged
6. **Sound feedback**: Keep sound on for better rhythm and feedback

---

**Ready to test your typing skills?** Start playing now and become a TypeMaster Pro! 🏆
