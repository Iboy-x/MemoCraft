# Memory Craft 🎮

A Minecraft-themed memory card game built with HTML, CSS, and JavaScript, featuring Firebase integration for global leaderboards. Test your memory by matching pairs of Minecraft items while competing with players worldwide!

## 🌟 Features

### Core Gameplay
- **Multiple Difficulty Levels**
  - Easy (8 pairs)
  - Medium (10 pairs)
  - Hard (12 pairs)
  - Adjustable flip times per difficulty
  - Difficulty-based scoring multipliers

### 🏆 Competitive Features
- **Global Leaderboard System**
  - Top 10 scores for each difficulty
  - Real-time score updates
  - Player name recognition
  - Time and score tracking

- **Advanced Scoring System**
  - Dynamic score calculation based on:
    - Number of matches
    - Moves efficiency
    - Completion time
    - Difficulty multipliers (Easy: 1x, Medium: 1.5x, Hard: 2x)
  - Score popup animations for instant feedback
  - High score and best time tracking per difficulty

### 🎨 Visual and Audio
- **Polished Animations**
  - Smooth card flip transitions
  - Match success effects
  - Wrong match feedback
  - Victory celebration with confetti
  - Score popup animations

- **Theme Customization**
  - Light/Dark mode toggle
  - Minecraft-styled pixelated font
  - Dynamic background
  - Responsive design for all devices

- **Audio Experience**
  - Background music
  - Card flip sounds
  - Match success sounds
  - Wrong match feedback
  - Music controls (Play/Pause)

### 🔄 Game Flow
- **Loading System**
  - Asset preloading
  - Loading progress bar
  - Smooth transition to gameplay

- **Game Over Experience**
  - Victory celebration
  - Score summary
  - Leaderboard qualification check
  - Encouraging messages
  - Quick restart option

## 🎮 How to Play

1. Select your preferred difficulty level
2. Click cards to reveal Minecraft items
3. Match pairs to earn points
4. Complete the game quickly with fewer moves for higher scores
5. Enter your name if you qualify for the leaderboard
6. Try to reach the top 10 in each difficulty!

## 🛠️ Technical Implementation

### Technologies Used
- HTML5 & CSS3
- Vanilla JavaScript
- Firebase (Authentication & Firestore)
- Google Fonts (Pixelify Sans)

### Firebase Features
- Anonymous authentication
- Real-time database
- Secure data storage
- Global leaderboard system

### Performance Optimizations
- Image preloading
- Optimized animations
- Efficient state management
- Responsive layout system
- Progressive loading

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/Iboy-x/memory_craft.git
```

2. Set up Firebase:
   - Create a Firebase project
   - Enable Anonymous Authentication
   - Set up Firestore Database
   - Update Firebase configuration in `index.html`

3. Open `index.html` in your browser or deploy to your preferred hosting service

## 🎨 Customization

You can customize the game by:
- Adding new Minecraft items to the `minecraftItems` array
- Adjusting difficulty settings in `difficultySettings`
- Modifying CSS variables for different themes
- Changing sound effects and background music
- Adjusting animation timings and effects

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Fork the repository
- Create feature branches
- Submit pull requests
- Open issues for bugs or feature requests
- Suggest improvements

## 📝 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

Made with ❤️ by [iboy-x](https://github.com/iboy-x)

---

**Note:** This is a fan project and is not affiliated with Mojang or Microsoft. Minecraft is a registered trademark of Mojang Studios.
