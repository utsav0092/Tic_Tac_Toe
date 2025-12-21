# Tic-Tac-Toe Game - Retro Edition

A classic Tic-Tac-Toe game with two game modes: **Two Player** and **AI Opponent** featuring an unbeatable AI powered by the Minimax algorithm. Experience retro-inspired gameplay with a vibrant 8-bit aesthetic!

## 🎮 Features

- **Two Game Modes:**
  - Two Player Mode: Play against a friend locally
  - AI Opponent Mode: Challenge an unbeatable AI powered by the Minimax algorithm
- **Retro Aesthetic:** Inspired by classic arcade games with pixel-perfect visuals
- **Responsive Design:** Works seamlessly on desktop and mobile devices
- **Intelligent AI:** The AI uses the Minimax algorithm to guarantee optimal play

## 📋 Game Rules

- **Board:** 3x3 grid
- **Players:**
  - Human: Plays as 'O' (always goes first)
  - AI/Second Player: Plays as 'X'
- **Winning Condition:** Align three of your symbols in a row, column, or diagonal
- **Draw:** Game ends in a tie if the board is full with no winner

## 🤖 AI: Minimax Algorithm

The AI opponent uses the Minimax algorithm, a decision-making strategy that evaluates all possible future moves:

**Scoring System:**
- Win: +10 points
- Lose: -10 points
- Draw: 0 points

The algorithm simulates future game states recursively, choosing moves that maximize the AI's chances of winning while minimizing the opponent's chances. This guarantees the AI will never lose—it either wins or forces a draw.

## 🎯 How to Play

1. Open `index.html` in your web browser
2. Select your game mode:
   - Click **Two Player** for local multiplayer
   - Click **AI Opponent** to play against the computer
3. Players take turns clicking empty squares to place their symbol
4. The game automatically detects wins and draws
5. Click **Play Again** to restart or **Main Menu** to switch modes

## 📁 Project Structure

```
Tic_Tac_Toe/
├── index.html      # Main HTML file with game layout
├── script.js       # Game logic and AI implementation
├── style.css       # Retro-themed styling
└── README.md       # Project documentation
```

## 🛠️ Technical Details

### Files Description

- **index.html** - Contains the DOM structure with landing page and game page sections
- **script.js** - Implements game mechanics, win detection, turn management, and the Minimax algorithm
- **style.css** - Provides retro 8-bit styling with scanline effects and vibrant colors

### Key Functions

- `selectMode(mode)` - Initiates the selected game mode
- `turnClick(square)` - Handles player moves
- `minimax(newBoard, player)` - Executes the Minimax algorithm for AI decision-making
- `checkWin(board, player)` - Checks if a player has won
- `checkTie()` - Determines if the game has ended in a draw

## 🚀 Getting Started

No installation required! Simply:

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start playing!

## 🎨 Styling

The game features a retro arcade aesthetic with:
- Classic "Press Start 2P" bitmap font
- Scanline effect for that authentic arcade feel
- Vibrant neon colors (pink, cyan, yellow)
- Pixel-perfect shadows and borders

## 🔮 Future Enhancements

- **Difficulty Levels:** Add easy, medium, and hard modes by making the AI play sub-optimally
- **Score Tracking:** Keep track of wins, losses, and draws across sessions
- **Sound Effects:** Add retro beep and boop sounds
- **Animations:** Smooth transitions and move animations
- **Mobile Optimization:** Enhanced touch controls for mobile devices