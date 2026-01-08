# 🐉 Dragon Repeller - RPG Game

An interactive browser-based RPG game where you embark on an epic quest to defeat the dragon terrorizing the town. Battle monsters, upgrade your weapons, and become the hero the town needs!

## ✨ Features

### 🎮 Gameplay
- **Multiple Locations**: Explore the town square, visit the store, venture into dangerous caves
- **Combat System**: Engage in turn-based battles with various monsters
- **Progressive Difficulty**: Face increasingly challenging enemies from slimes to the mighty dragon
- **Weapon Upgrades**: Purchase and collect powerful weapons to increase your combat effectiveness
- **Resource Management**: Balance your health, gold, and XP strategically

### 🎨 Enhanced UI/UX
- **Modern Design**: Beautiful gradient backgrounds with glowing effects and smooth animations
- **Interactive Elements**:
  - Animated character and monster icons
  - Real-time progress bars for health and XP
  - Visual inventory system with weapon icons
  - Hover effects and button animations
- **Responsive Layout**: Fully responsive design that works on desktop, tablet, and mobile devices
- **Visual Feedback**: Color-coded stats, animated transitions, and dynamic monster displays

### 📊 Game Mechanics
- **Experience System**: Gain XP from defeating monsters with visual progress tracking
- **Health Management**: Buy health potions and monitor your vitality through progress bars
- **Economy**: Earn gold from battles and spend it wisely on weapons and health
- **Inventory System**: Collect and manage multiple weapons with visual indicators
- **Easter Egg**: Discover a hidden mini-game for bonus rewards

## 🎯 Weapons

| Weapon | Icon | Power | Cost |
|--------|------|-------|------|
| Stick | 🪵 | 5 | Starting weapon |
| Dagger | 🗡️ | 30 | 30 gold |
| Claw Hammer | 🔨 | 50 | 30 gold |
| Sword | ⚔️ | 100 | 30 gold |

## 👾 Monsters

| Monster | Icon | Level | Health |
|---------|------|-------|--------|
| Slime | 💧 | 2 | 15 |
| Fanged Beast | 🐺 | 8 | 60 |
| Dragon | 🐉 | 20 | 300 |

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installations required!

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/roleplay-game.git
```

2. Navigate to the project directory:
```bash
cd roleplay-game
```

3. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or simply drag and drop the `index.html` file into your browser.

## 🎮 How to Play

1. **Starting Out**: You begin in the town square with 100 health, 50 gold, and a basic stick
2. **Visit the Store**: Use your gold to buy health potions (10 gold) or upgrade weapons (30 gold)
3. **Enter the Cave**: Fight slimes and fanged beasts to gain experience and gold
4. **Combat Actions**:
   - **Attack**: Deal damage to the monster (may miss occasionally)
   - **Dodge**: Avoid the monster's attack
   - **Run**: Flee back to town square
5. **Weapon Mechanics**: Your weapon can break during combat (10% chance per attack)
6. **Final Challenge**: When ready, challenge the dragon from the town square
7. **Win Condition**: Defeat the dragon to win the game!

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with:
  - CSS Grid & Flexbox for layouts
  - CSS Animations and Transitions
  - Linear gradients and box shadows
  - Media queries for responsive design
- **Vanilla JavaScript**: Game logic and DOM manipulation

### Project Structure
```
roleplay-game/
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
├── script.js           # Game logic and functionality
└── README.md          # Project documentation
```

### Key Features Implementation
- **Progress Bars**: Dynamic width updates based on health/XP percentages
- **Inventory Display**: Real-time DOM updates showing weapon collection
- **Monster Icons**: Dynamic emoji changes based on enemy type
- **Responsive Design**: Mobile-first approach with breakpoints at 768px
- **Animations**: CSS keyframe animations for floating, shaking, glowing effects

## 🎨 UI Enhancements

The game features a rich, immersive interface with:
- Glowing title with pulsing animation
- Gradient backgrounds with purple/blue color scheme
- Interactive stat cards with hover effects
- Smooth transitions between game states
- Visual weapon inventory with active weapon highlighting
- Monster display with animated icons during combat
- Progress bars for health, XP, and monster health

## 🤝 Contributing

Contributions are welcome! Here are some ways you can contribute:
- Report bugs and issues
- Suggest new features or improvements
- Submit pull requests with enhancements
- Improve documentation

## 📜 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

This project is inspired by the *JavaScript Algorithms and Data Structures* course from [freeCodeCamp](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/), enhanced with modern UI/UX improvements.

## 📧 Contact

Feel free to reach out if you have any questions or suggestions!

---

**Enjoy your adventure in Dragon Repeller! May your blade stay sharp and your health bar full! 🗡️✨**
