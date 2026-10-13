# 🗝️ Escape Room Game

A 3D escape-room game built with **Python, PyOpenGL and GLUT**.
Answer the quiz in the book, unlock the chest, grab the golden key and escape through the door — but a wrong answer wakes the villain and costs you a limb!

![Gameplay screenshot](screenshots/gameplay.png)

## ✨ Features

- 3D room with tiled walls, checkerboard floor, pipes and a locked door
- Quiz system with a 15-second timer per question
- Chest with 4 animated locks that open as you answer correctly
- Golden key you carry in your hand once collected
- Penalty system: wrong answer → collect the saw → lose a limb → move slower
- A villain who chases you after your first mistake
- Top-down camera view, HUD and on-screen hints

## 🎮 Controls

| Key | Action |
|-----|--------|
| `Space` | Start the game |
| `W` / `S` | Move forward / backward |
| `A` / `D` | Turn left / right |
| `E` | Interact (book, chest, saw, door) |
| `1`–`4` or `A`–`D` | Answer a quiz question |
| `V` | Toggle top view |
| `R` | Restart |
| `Esc` | Quit |

## 🚀 Getting Started

### Requirements
- Python 3.8+
- PyOpenGL
- On Windows: `freeglut.dll` placed next to `escape_game.py` (download freeglut for Windows and copy the 64-bit `freeglut.dll`)

### Install & run

```bash
git clone https://github.com/<your-username>/escape-room-game.git
cd escape-room-game
pip install -r requirements.txt
python escape_game.py
```

## 🧠 How to play

1. Walk to the book on the north side of the room and press `E`.
2. Answer all 4 questions correctly to open every lock on the chest.
3. Take the golden key from the chest.
4. Go to the door and press `E`, then walk out to win.
5. Answer wrong or run out of time? Find the glowing red-ringed saw and press `E` — and run from the villain!

## 🛠️ Built with

- [Python](https://www.python.org/)
- [PyOpenGL](https://pyopengl.sourceforge.net/)
- GLUT / freeglut

## 📄 License

Released under the MIT License.
