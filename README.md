# 🌌 Milky Way Galaxy - Space Shooter Game

A classic space shooter game built with **Python** and **Pygame**. This project was created to **solidify Python programming skills** through hands-on game development.

## 🎮 About The Project

I built this game as a practical exercise to practice:

- Object-Oriented Programming (OOP)
- Game loop and frame rate management
- Collision detection
- Event handling and keyboard input
- Sprite rendering and animation
- Sound and music integration
- File I/O for high score storage

## ✨ Features

- Smooth player movement with arrow keys
- 4 different enemy types
- Explosion effects with sound
- Background music (Stranger Things theme)
- High score tracking
- Auto-scaling for different screen sizes
- Persian font support

## 🎯 Controls

| Key | Action |
|-----|--------|
| ← / → | Move left/right |
| Space | Shoot |
| Enter | Start / Restart |
| ESC | Exit |

## 🛠️ How to Run

### Requirements
- Python 3.8+

### Steps

1. Clone the repository:
```bash
git clone https://github.com/sevin-sarem/MySpaceShooter.git
cd MySpaceShooter
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the game:
```bash
python main.py
```

## 🎮 Gameplay

- Destroy enemies to earn points
- Each enemy = +1 point
- Game over when enemy reaches the bottom
- Enter your name to save high score

## 📦 Build Executable (Windows)

```bash
pip install pyinstaller
pyinstaller --onefile --windowed --icon=icon.ico --add-data "background-wallpaper1.jpg;." --add-data "bullet.png;." --add-data "enemy1.png;." --add-data "enemy2.png;." --add-data "enemy3.png;." --add-data "enemy4.png;." --add-data "explosion.wav;." --add-data "laser.wav;." --add-data "player.png;." --add-data "stranger-things.mp3;." --add-data "Vazirmatn-Black.ttf;." --add-data "icon.png;." main.py
```

## 📄 License

MIT License

## 🙏 Acknowledgments
- Pygame community
- Stranger Things theme music
- Vazirmatn font
