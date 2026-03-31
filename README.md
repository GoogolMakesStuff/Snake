<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/20e9755f-afc3-43b4-9014-94c3994b6ef4" />


# Retro Snake Game

A classic Snake game with retro styling and modern features.

## Features

- **Retro arcade styling** with CRT effects and green phosphor display
- **Intro screen** with game instructions
- **Sound effects** for eating apples and game over
- **Barrier walls** to prevent the snake from escaping
- **Score tracking** with persistent high score
- **Progressive difficulty** - game speeds up as you score more points

## How to Play
1. Open **index.html** in the extracted folder
2. Press **SPACE** to start the game
3. Use **ARROW KEYS** to control the snake
4. Use **WASD KEYS** to comtrol the snake too
5. Eat the red apples to grow and increase your score
6. Avoid hitting the walls or your own tail
7. Try to beat your high score!

## Sound Effects

The game includes audio support for:
- **Eat sound**: Plays when the snake eats an apple
- **Death sound**: Plays when the game is over

To enable sound effects, add MP3 files to the `sounds/` directory:
- `sounds/eat.mp3` - Sound for eating an apple
- `sounds/death.mp3` - Sound for game over

You can use any retro-style 8-bit sound effects. Some suggestions:
- Eat sound: A short "beep" or "chomp" sound
- Death sound: A short "explosion" or "game over" sound

## Files Structure

```
snake-game/
├── index.html          # Main HTML file
├── style.css           # Retro styling and animations
├── script.js           # Game logic and mechanics
├── sounds/             # Audio files directory
│   ├── eat.mp3        # Eating sound effect (add this)
│   └── death.mp3      # Game over sound effect (add this)
└── README.md           # This file
```

## Game Controls

| Key | Action |
|-----|--------|
| SPACE | Start game / Restart after game over |
| ↑ | Move snake up |
| ↓ | Move snake down |
| ← | Move snake left |
| → | Move snake right |
| W | Move snake up |
| A | Move snake left |
| S | Move snake down |
| D | Move snake right |

## Scoring

- **+10 points** for each apple eaten
- **High score** is saved locally and persists between sessions
- **Speed increases** gradually as your score increases

## Technical Details

- Built with HTML5 Canvas for smooth graphics
- Responsive design works on different screen sizes
- Uses localStorage for persistent high score
- Retro CRT effects created with CSS animations
- Game speed: 100ms initially, decreases by 2ms per apple (minimum 50ms)

## Browser Compatibility

Works best in modern browsers that support:
- HTML5 Canvas
- CSS3 animations
- LocalStorage
- Audio elements

Enjoy playing this retro Snake game!
