# 🌼 Dandelions Game

A strategic pen-and-paper game brought to life on the web! Two players compete in an elegant dance of planting flowers and blowing wind across a meadow.

## 🎮 Play Now

[Play the game here](https://bberki.github.io/dandelions_game) *(replace with your actual GitHub Pages URL)*

## 📖 About

Dandelions is a two-player abstract strategy game where:
- **The Dandelions** aim to cover the entire 5×5 meadow with flowers and seeds
- **The Wind** tries to leave at least one square uncovered

Each player takes 7 turns, making strategic decisions that ripple across the board. The Wind can only blow in each direction once, creating a fascinating puzzle of positioning and prediction.

## 🎯 How to Play

### Setup
- 5×5 grid representing a meadow
- 8 directional winds (N, S, E, W, NE, NW, SE, SW)
- 7 rounds of play

### Gameplay
1. **Dandelions' Turn**: Click any square to plant a flower (🌼)
   - You can plant on empty squares or squares with seeds
   
2. **Wind's Turn**: Click a compass direction to blow wind (💨)
   - Seeds spread from ALL flowers in that direction
   - Each direction can only be used once per game

3. **Repeat** for 7 rounds

### Winning
- **Dandelions win** if the entire board is covered with flowers or seeds
- **Wind wins** if any square remains empty after 7 rounds

## 🚀 Running Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/dandelions-game.git
   cd dandelions-game
   ```

2. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click → Open with → Browser, or
   - Drag and drop into browser window

No build process or dependencies required!

## 🎨 Features

- ✨ Clean, intuitive interface
- 🎯 Visual compass rose for wind directions
- 🔄 Real-time game state updates
- 📱 Responsive design
- 🎮 Local multiplayer (pass-and-play)
- ♻️ Quick reset for new games

## 🛠️ Technology

Built with:
- React 18
- Tailwind CSS
- Pure HTML/CSS/JavaScript (no build tools needed)

## 📜 Game Origin

Based on the pen-and-paper game "Dandelions" from the mathematical games collection. The original game explores interesting mathematical properties about grid coverage and strategic wind direction selection.

## 🤝 Contributing

Feel free to fork this project and submit pull requests! Some ideas for enhancements:
- Add different board sizes (6×6, 7×7)
- Implement scoring system
- Add AI opponent
- Create collaborative mode
- Add animations for seed spreading

## 📄 License

MIT License - feel free to use and modify!

## 🌟 Acknowledgments

Original game design from the mathematical pen-and-paper games collection.

---

Made with 🌼 and 💨