# 🥚 EGG Catcher - Dragon Adventure Game

![Python](https://img.shields.io/badge/Python-3.6+-blue.svg)
![Pygame Zero](https://img.shields.io/badge/Pygame%20Zero-1.3+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 🐉 About The Game

**EGG Catcher** is an exciting arcade-style adventure game built with Pygame Zero where you play as a brave hero on a daring mission to collect magical eggs from sleeping dragons! Test your courage and reflexes as you navigate through a dangerous dungeon filled with fire-breathing dragons.

![Gameplay](https://img.shields.io/badge/Gameplay-Action--Strategy-orange)

## 🎮 Features

- **🎯 Three Difficulty Levels** - Easy, Medium, and Hard dragons with unique behaviors
- **🐉 Dynamic Dragon AI** - Dragons sleep and wake up at different intervals
- **⭐ Strategic Gameplay** - Risk vs reward system with different egg values
- **❤️ Health System** - 3 lives to complete your mission
- **🏆 Win Condition** - Collect 10 eggs to win
- **🎵 Immersive Audio** - Sound effects and background music
- **🔄 Restart System** - Quick restart functionality
- **🎨 Visual Feedback** - Clear UI with score and health indicators

## 🕹️ How to Play

### Controls:
- **↑ ↓ ← → Arrow Keys** - Move your character
- **R Key** - Restart game
- **Q Key** - Quit game

### Objectives:
1. **Move your character** to collect eggs from sleeping dragons
2. **Avoid awake dragons** - they'll damage you and reduce health!
3. **Collect 10 eggs** to win the game
4. **Don't lose all 3 health points**

### Dragon Behaviors:
| Dragon | Wake Interval | Sleep Duration | Eggs | Difficulty |
|--------|---------------|----------------|------|------------|
| Easy 🐲 | 6 seconds | 8 seconds | 1 egg | 🌱 |
| Medium 🐉 | 4 seconds | 6 seconds | 2 eggs | ⚡ |
| Hard 🔥 | 2 seconds | 4 seconds | 3 eggs | 🔥 |

## 🚀 Installation

### Prerequisites
- Python 3.6 or higher
- Pygame Zero library

### Quick Start
```bash
# Clone the repository
git clone https://github.com/yourusername/egg-catcher.git
cd egg-catcher

# Install dependencies
pip install pgzero

# Run the game
python main.py
```

### Manual Installation
1. **Install Python** from [python.org](https://python.org)
2. **Install Pygame Zero**:
   ```bash
   pip install pgzero
   ```
3. **Download the game files**
4. **Run the game**:
   ```bash
   python main.py
   ```

## 📁 Project Structure
```
egg-catcher/
├── main.py                 # Main game file
├── images/                 # Game sprites and assets
│   ├── hero.png            # Player character
│   ├── dragon-asleep.png   # Sleeping dragon
│   ├── dragon-awake.png    # Awake dragon
│   ├── one-egg.png         # Easy dragon egg
│   ├── two-eggs.png        # Medium dragon egg
│   ├── three-eggs.png      # Hard dragon egg
│   ├── egg-count.png       # Egg counter icon
│   ├── life-count.png      # Health icon
│   └── dungeon.png         # Background
├── sounds/                 # Audio files
│   ├── background.mp3      # Background music
│   ├── dragon_fire.wav     # Dragon wake sound
│   ├── egg_collected.wav   # Egg collection sound
│   ├── egg_respawned.wav   # Egg respawn sound
│   ├── game_over.wav       # Game over sound
│   ├── game_win.wav        # Victory sound
│   └── hero_hit.wav        # Damage sound
└── README.md              # Project documentation
```

## 🎯 Game Strategy

### Tips for Success:
- **Start with easy dragons** to build your egg count safely
- **Watch the patterns** - learn each dragon's sleep cycle
- **Be patient** - wait for the right moment to strike
- **Use screen wrapping** to escape dangerous situations
- **Prioritize survival** - losing health is worse than missing eggs

### Scoring:
- **Easy Dragon**: 1 egg
- **Medium Dragon**: 2 eggs  
- **Hard Dragon**: 3 eggs
- **Target**: 10 eggs to win

## 🛠️ Development

### Built With:
- **Python** - Programming language
- **Pygame Zero** - Game framework
- **Object-Oriented Design** - Clean code architecture

### Customization:
You can easily modify game parameters:
```python
# In main.py
speed = 3                    # Player movement speed
Health = 3                   # Starting health
win_condition = 10           # Eggs needed to win
```

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

### Feature Ideas:
- [ ] More dragon types and behaviors
- [ ] Power-ups and special abilities
- [ ] Different levels and environments
- [ ] High score system
- [ ] Mobile device support

### How to Contribute:
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Troubleshooting

### Common Issues:
**"Module not found error"**
```bash
pip install --upgrade pgzero
```

**"No images directory found"**
- Ensure all asset folders are in the same directory as main.py
- Check that image and sound files have correct names

**Game runs slowly**
- Close other applications to free up system resources
- Reduce screen resolution if needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Pygame Zero](https://pgzero.readthedocs.io/) framework
- Inspired by classic arcade games
- Thanks to the Python game development community

## 📞 Support

If you have any questions or issues:
1. Check the [Troubleshooting](#🐛-troubleshooting) section
2. Open an [Issue](https://github.com/yourusername/egg-catcher/issues)
3. Contact the development team

---

<div align="center">

**⭐ If you like this game, please give it a star!**

*"Dare to enter the dragon's den and become the ultimate Egg Catcher!"* 🥚⚔️🐉

</div>
