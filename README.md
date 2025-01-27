# 🎮 Rock Paper Scissors Game
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

An interactive Rock Paper Scissors game built with HTML, CSS, and vanilla JavaScript. Play against the computer in this classic hand game with a modern digital twist!

## ✨ Features

### Gameplay
- 🎲 Play against computer opponent
- 🎯 Real-time score tracking
- 💫 Interactive choice selection
- 🎨 Visual feedback for game outcomes
- 🔄 Continuous play functionality

### User Interface
- 🖼️ Clean and intuitive design
- 📱 Responsive layout
- 🎨 Dynamic color feedback for wins/losses
- 👆 Interactive hover effects
- 📊 Clear score display

## 🎯 Game Rules
1. Choose your move: Rock, Paper, or Scissors
2. Computer randomly selects its move
3. Winner is determined by classic rules:
   - Rock crushes Scissors
   - Scissors cuts Paper
   - Paper covers Rock
4. Score updates automatically after each round

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, etc.)
- Image files for rock, paper, and scissors in an `images` folder

### Installation
1. Clone the repository
```bash
git clone https://github.com/your-username/rock-paper-scissors.git
```

2. Ensure image files are in the correct location:
```
images/
  ├── rock.png
  ├── paper.png
  └── scissors.png
```

3. Open `index.html` in your web browser

## 🔧 Technical Details

### File Structure
```
rock-paper-scissors/
├── index.html
├── style.css
├── app.js
└── images/
    ├── rock.png
    ├── paper.png
    └── scissors.png
```

### Key Functions
- `genCompChoice()`: Generates computer's random choice
- `playGame()`: Main game logic handler
- `showWinner()`: Updates UI based on game outcome
- `drawGame()`: Handles tie scenarios

## 🎨 Styling Highlights
- Dark theme with `#081b31` primary color
- Circular choice buttons with hover effects
- Responsive design using Flexbox
- Dynamic message colors for game outcomes:
  - Green for wins
  - Red for losses
  - Default blue for draws

## 🖥️ Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements
- Add sound effects
- Implement game history
- Add difficulty levels
- Include multiplayer mode
- Add animations for selections

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments
- Classic Rock Paper Scissors game concept
- Modern web development practices
- User interface design principles

---
<div align="center">
Made with ❤️ | Play and Enjoy! 🎮
</div>
