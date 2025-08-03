# 🐍 Snake Game

A classic Snake game implementation built with Python and Pygame. Guide the snake to eat food, grow longer, and avoid colliding with walls or yourself!

## 📖 Description

This is a simple yet engaging recreation of the timeless Snake game. Built using Python and the Pygame library, it features smooth gameplay, score tracking, and classic snake mechanics that will bring back nostalgic memories of early mobile gaming.

## 🎮 Features

- **Classic Gameplay**: Navigate the snake using arrow keys
- **Score System**: Track your high score as you eat food
- **Collision Detection**: Game ends when snake hits walls or itself
- **Smooth Animation**: 60 FPS gameplay for responsive controls
- **Food Generation**: Random food placement for continuous challenge
- **Growing Snake**: Snake length increases with each food consumed

## 🛠️ Technologies Used

- **Python 3.x**: Core programming language
- **Pygame**: Game development library for graphics and input handling

## 📋 Prerequisites

- Python 3.6 or higher
- Pygame library

## 🚀 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/aliyanissohaib/snake-game.git
cd snake-game
```

2. Install Pygame:
```bash
pip install pygame
```

3. Run the game:
```bash
python snake_game.py
```

## 🎯 How to Play

- Use **Arrow Keys** to control the snake's direction
- Eat the red food to grow and increase your score
- Avoid hitting the walls or the snake's own body
- Try to achieve the highest score possible!

## 🎮 Controls

| Key | Action |
|-----|--------|
| ↑ | Move Up |
| ↓ | Move Down |
| ← | Move Left |
| → | Move Right |
| ESC | Quit Game |

## 📊 Game Rules

1. The snake starts with a length of 3 segments
2. Each food eaten increases the snake's length by 1 segment
3. Each food eaten adds 10 points to your score
4. Game ends if the snake collides with:
   - The boundary walls
   - Its own body

## 🖼️ Screenshots

```
┌─────────────────────────┐
│  Score: 150             │
│                         │
│    ████                 │
│    ████                 │
│    ████                 │
│    ████ ██              │
│         ██              │
│         ██              │
│         ████████        │
│                         │
│         🍎              │
│                         │
└─────────────────────────┘
```

## 🔧 Customization

You can easily modify the game by adjusting these variables in the code:
- `WINDOW_WIDTH` & `WINDOW_HEIGHT`: Change game window size
- `SNAKE_SIZE`: Adjust snake segment size
- `SNAKE_SPEED`: Control game speed/difficulty
- `COLORS`: Customize snake, food, and background colors

## 🤝 Contributing

Contributions are welcome! Ideas for improvements:
- Add sound effects
- Implement difficulty levels
- Create a start menu
- Add power-ups
- Save high scores to file
- Add different food types

## 🐛 Known Issues

- None currently reported

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the classic Nokia Snake game
- Built as a learning project to understand game development basics

## 🏷️ Tags

`python` `pygame` `snake-game` `game-development` `classic-games` `arcade` `2d-game` `beginner-project`

---

*Enjoy the game and happy coding! 🎮*
