# 🎮 Neon Maze

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-HTML5-green.svg)](https://github.com/jianRY/migong)

> A stunning HTML5 maze game with cyberpunk neon aesthetics

[中文版本](./README.md)

## 📺 Game Preview

```
┌─────────────────────────────────────┐
│  ✨ Neon Maze ✨                     │
│  ⏱️ 00:00  👣 0 steps  🔥 17×17    │
│  ┌─────────────────────────────┐     │
│  │ ▦ ▦ ▦ ▦ ▦ ▦ ▦ ▦ ▦ ▦ │     │
│  │ ▦ ··· ·▦ ··· ·▦ ····   │     │
│  │ ▦ ▦ ▦ ▦▦▦ ▦ ▦▦ ▦ ▦ │     │
│  │ ▦ ·· ·· ·· ·▦ ·· ···· │     │
│  │ ▦ ▦ ▦▦▦ ▦ ▦ ▦▦ ▦ ▦    │     │
│  │            🔴               │     │
│  └─────────────────────────────┘    │
│  [🎮 Start] [🔄 Restart] [🔊 SFX]  │
└─────────────────────────────────────┘
```

## 🎯 Objective

Find the path from start to goal. Reach the **purple light** to win!

## 🕹️ Controls

| Input | Action |
|-------|--------|
| ↑↓←→ / WASD | Move |
| Touch Swipe | Move |
| R | Restart |
| Esc | Pause/Continue |
| Space | Start/Continue |

## ✨ Features

### 🎲 Maze System
- **Random Generation** - DFS algorithm
- **Dynamic Difficulty** - 5×5 to 41×41
- **Unique Path** - Guaranteed solvable

### 🎨 Visual Styles

#### 🧱 20 Wall Styles

| # | Style | # | Style |
|---|-------|---|-------|
| 0 | Neon | 10 | Stone |
| 1 | Pixel | 11 | Frost |
| 2 | Gradient | 12 | Fire |
| 3 | Honeycomb | 13 | Forest |
| 4 | Circles | 14 | Stars |
| 5 | Lightning | 15 | Heart |
| 6 | Triangle | 16 | Rainbow |
| 7 | Blue | 17 | Ocean |
| 8 | Cartoon | 18 | Coin |
| 9 | Brick | 19 | Tech |

#### 🐱 20 Player Icons

Rabbit · Tiger · Robot · Star · Cat · Dog · Alien · Panda · Chick · Frog · Fox · Lion · Bear · Butterfly · Bee · Turtle · Gecko · Crab · Pumpkin

#### 🚪 20 Goal Icons

Door · Trophy · Crown · Diamond · Star · Heart · Coin · Key · Ring · Gift · Medal · Target · Star · Crystal · Gem · Tent · Castle · Coaster · Carousel · Ferris Wheel

### 🔊 Sound System
- Move Sound
- Win Sound
- Wall Hit (Toggle)

### 🎆 Effects
- Particle Trail
- Starfield Background
- Neon Glow
- Smooth Animation
- Fireworks

## 🚀 Live Preview

Open in browser: [maze.html](./maze.html)

```bash
# Clone the repo
git clone https://github.com/jianRY/migong.git

# Open
cd migong && open maze.html
```

## 🛠️ Tech Stack

| Tech | Description |
|------|------------|
| HTML5 Canvas | Rendering |
| Vanilla JS | Game Logic |
| DFS Algorithm | Maze Generation |
| Web Audio API | Sound |

## 📱 Responsive

- 🖥️ Desktop
- 📱 Mobile
- 👆 Touch Support

## 🤝 Contribute

Issues and PRs welcome!

## 📝 Changelog

### v1.0.0
- ✅ Basic Maze Game
- ✅ 20 Wall/Player/Goal Styles
- ✅ Sound System
- ✅ Particle/Firework Effects
- ✅ Touch Controls

## 📄 License

MIT License - Free to use, star welcome ⭐

---

Made with ❤️ by [jianRY](https://github.com/jianRY)