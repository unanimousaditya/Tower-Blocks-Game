# 🏗️ Tower Blocks Game

## 🎮 [Play Now!](https://unanimousaditya.github.io/Tower-Blocks-Game/)

A captivating, minimalist Tower Blocks stacking game crafted with pure HTML, CSS, and JavaScript - no frameworks or libraries! Challenge your timing and precision as you build the tallest tower possible.

## ✨ Description

Tower Blocks is an addictive arcade-style game where your goal is to stack blocks as high as possible. Each moving block must be precisely timed and placed on the previous one. The true challenge? Any overhanging portion breaks off and falls away, making your target area progressively smaller with each level. How high can you stack before a critical miss ends your tower-building journey?

## 🎯 Features

- 🖱️ Simple one-click (or spacebar) gameplay - accessible to all ages
- 📱 Fully responsive design that works flawlessly across desktop, tablet, and mobile devices
- 🔢 Real-time score tracking with visual feedback
- 📈 Dynamic difficulty progression - the higher you build, the more precision required
- 🎭 Satisfying visual and animation effects including block splitting and falling physics
- 🚀 Fast loading with zero external dependencies
- 🧩 Clean, modular code structure that's easy to understand and modify

## 🕹️ How to Play

1. 👆 Press the spacebar, click, or tap on the screen to place a block
2. 📊 Try to align each new block perfectly with the one below it
3. ✂️ Watch as any overhanging portion breaks off and falls away
4. 🏆 Your score increases with each successfully placed block
5. 🔄 The game continues until you completely miss placing a block on the stack
6. 🔁 Press refresh or the restart button to play again and beat your high score!

## 💻 Technology Stack

- **HTML5** 📝 - Semantic structure for game elements and UI
- **CSS3** 🎨 - Stylish visuals, transitions, and responsive layouts
- **JavaScript** ⚙️ - Pure vanilla JS powering the game mechanics:
  - Block movement & physics
  - Collision detection & block splitting
  - Score management
  - Game state control
  - Touch & keyboard input handling

## 🛠️ Technical Implementation Details

- **3D Effect** - Clever use of CSS transforms to create perspective and depth
- **Block Physics** - Custom algorithms for calculating block movement and breaking
- **Performance Optimization** - Efficient animation handling using requestAnimationFrame
- **Browser Compatibility** - Tested and functioning across all modern browsers
- **Mobile-First Approach** - Designed with touch interfaces in mind

## ⚡ Installation

To run the game locally:

1. 📂 Clone the repository:
   ```bash
   git clone https://github.com/unanimousaditya/Tower-Blocks-Game.git
   ```

2. 📁 Navigate to the project directory:
   ```bash
   cd Tower-Blocks-Game
   ```

3. 🌐 Open `index.html` in your favorite browser and start stacking!

## 📚 Code Structure

- `index.html` - Main HTML document containing game container and UI elements
- `style.css` - Complete styling including animations, responsive design, and visual effects
- `script.js` - Core game logic including:
  - `initGame()` - Setup game variables and event listeners
  - `moveBlock()` - Handle block movement across the screen
  - `placeBlock()` - Process player input and handle block placement
  - `checkCollision()` - Determine whether blocks align and calculate overlapping
  - `updateScore()` - Manage player score and update UI
  - `gameOver()` - Handle end game state and final score display

## 🎨 Customization Options

You can easily modify the game to match your style:

- 🖌️ **Colors & Theme** - Edit CSS variables at the top of the style.css file
- ⏱️ **Game Speed** - Adjust the blockSpeed variable in the JavaScript file
- 📏 **Block Dimensions** - Modify the block size constants for different gameplay feel
- 🎮 **Difficulty Curve** - Tweak the speed increase rate for a custom challenge
- 🔊 **Add Sound Effects** - Easily integrate audio for a more immersive experience

## 🤝 Contributing

Contributions are enthusiastically welcomed! If you'd like to improve the game:

1. 🍴 Fork the repository
2. 🌿 Create a new branch (`git checkout -b feature/amazing-tower-feature`)
3. ✏️ Make your brilliant changes
4. 💾 Commit your changes (`git commit -m 'Add some amazing tower feature'`)
5. 📤 Push to the branch (`git push origin feature/amazing-tower-feature`)
6. 🔁 Open a Pull Request and describe your improvements

### 💡 Enhancement Ideas
- Add sound effects and background music
- Implement high score tracking with localStorage
- Create different visual themes or block styles
- Add special blocks with unique properties
- Develop level progression with increasing challenges

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- 💫 Inspired by classic arcade stacking games and mobile hits like Stack
- 🙏 Created with passion by [Aditya Raj](https://github.com/unanimousaditya)
- 🌟 Special thanks to the open-source community for inspiration and feedback

## 📞 Contact

- 👨‍💻 GitHub: [@unanimousaditya](https://github.com/unanimousaditya)

---

🎮 Enjoy the challenge and happy stacking! Don't forget to star ⭐ the repo if you enjoyed playing!
