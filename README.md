# 🎮 霓虹迷宫 | Neon Maze

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-HTML5-green.svg)](https://github.com/jianRY/migong)

> A stunning HTML5 maze game with cyberpunk neon aesthetics
> 一个精美绝伦的 HTML5 迷宫游戏，采用赛博朋克风格设计

## 📺 游戏预览 | Game Preview

```
┌─────────────────────────────────────┐
│  ✨ 霓虹迷宫 ✨                     │
│  ⏱️ 00:00  👣 0步  🔥 17×17      │
│  ┌─────────────────────────────┐    │
│  │ ▦ ▦ ▦ ▦ ▦ ▦ ▦ ▦ ▦ ▦    │    │
│  │ ▦ ··· ·▦ ··· ·▦ ····   │    │
│  │ ▦ ▦ ▦ ▦▦▦ ▦ ▦▦ ▦ ▦ │    │
│  │ ▦ ·· ·· ·· ·▦ ·· ···· │    │
│  │ ▦ ▦ ▦▦▦ ▦ ▦ ▦▦ ▦ ▦    │    │
│  │            🔴              │    │
│  └─────────────────────────────┘    │
│  [🎮 开始] [🔄 重来] [🔊 音效]   │
└─────────────────────────────────────┘
```

## 🎯 游戏目标 | Objective

Find the path from start to goal. Reach the **purple light** to win!
找到从起点到终点的正确路径，抵达紫色光点即可获胜！

## 🕹️ 操作说明 | Controls

| Input 输入 | Action 操作 |
|-----------|-----------|
| ↑↓←→ / WASD | Move 移动 |
| Touch 触屏 | Swipe 滑动 |
| R | Restart 重新开始 |
| Esc | Pause/Continue 暂停/继续 |
| Space | Start/Continue 开始/继续 |

## ✨ 功能特色 | Features

### 🎲 迷宫系统 | Maze System
- **Random Generation 随机生成** - DFS algorithm 算法
- **Dynamic Difficulty 动态难度** - 5×5 to 41×41
- **Unique Path 唯一解** - Guaranteed solvable 有解路径

### 🎨 视觉风格 | Visual Styles

#### 🧱 20种墙壁样式 | 20 Wall Styles

| # | Style 样式 | # | Style 样式 |
|---|-----------|---|-----------|
| 0 | 霓虹墙 Neon | 10 | 石头墙 Stone |
| 1 | 像素墙 Pixel | 11 | 冰霜墙 Frost |
| 2 | 渐变墙 Gradient | 12 | 火焰墙 Fire |
| 3 | 蜂窝墙 Honeycomb | 13 | 森林墙 Forest |
| 4 | 圈圈墙 Circles | 14 | 星星墙 Stars |
| 5 | 闪电墙 Lightning | 15 | 爱心墙 Heart |
| 6 | 三角墙 Triangle | 16 | 彩虹墙 Rainbow |
| 7 | 渐蓝墙 Blue | 17 | 海洋墙 Ocean |
| 8 | 卡通墙 Cartoon | 18 | 金币墙 Coin |
| 9 | 砖块墙 Brick | 19 | 科技墙 Tech |

#### 🐱 20种玩家 | 20 Player Icons

Rabbit · Tiger · Robot · Star · Cat · Dog · Alien · Panda · Chick · Frog
兔子 · 老虎 · 机器人 · 星星 · 小猫 · 小狗 · 外星人 · 熊猫 · 小鸡 · 青蛙

Fox · Lion · Bear · Butterfly · Bee · Turtle · Gecko · Crab · Pumpkin
狐狸 · 狮子 · 狗熊 · 蝴蝶 · 蜜蜂 · 乌龟 · 壁虎 · 螃蟹 · 南瓜

#### 🚪 20种终点 | 20 Goal Icons

Door · Trophy · Crown · Diamond · Star · Heart · Coin · Key · Ring · Gift
门 · 奖杯 · 皇冠 · 钻石 · 星星 · 爱心 · 金币 · 钥匙 · 戒指 · 礼物

Medal · Target · Star · Crystal · Gem · Tent · Castle · Coaster · Carousel · Ferris Wheel
奖牌 · 靶心 · 亮星 · 水晶球 · 宝石 · 帐篷 · 城堡 · 过山车 · 木马 · 摩天轮

### 🔊 音效系统 | Sound System
- Move Sound 移动音效
- Win Sound 胜利音效
- Wall Hit 撞墙音效
- Toggle On/Off 可开关

### 🎆 特效系统 | Effects
- Particle Trail 移动粒子
- Starfield Background 动态星空
- Neon Glow 霓虹发光
- Smooth Animation 平滑动画
- Fireworks 胜利烟花

## 🚀 在线预览 | Live Preview

Open in browser 在浏览器中打开: [maze.html](./maze.html)

```bash
# Clone the repo 克隆仓库
git clone https://github.com/jianRY/migong.git

# Open 打开
cd migong && open maze.html
```

## 🛠️ 技术栈 | Tech Stack

| Tech 技术 | Description 描述 |
|----------|----------------|
| HTML5 Canvas | Rendering 渲染 |
| Vanilla JS | Game Logic 游戏逻辑 |
| DFS Algorithm | Maze Generation 迷宫生成 |
| Web Audio API | Sound 音效 |

### 代码结构 | Code Structure
```
maze.html (Single File 单一文件)
├── CSS Styles 样式 (Neon/Cyberpunk 霓虹/赛博朋克)
├── Game Logic 游戏逻辑 (Generation/Movement 生成/移动)
├── Renderer 渲染 (Wall/Player/Goal 墙/玩家/终点)
├── 20 Styles 20种样式切换
└── Effects 特效 (Particle/Firework 粒子/烟花)
```

## 📱 响应式 | Responsive

- 🖥️ Desktop 桌面端
- 📱 Mobile 移动端
- 👆 Touch Support 触屏支持

## 🤝 贡献 | Contribute

Issues and PRs welcome! 欢迎提交 Issue 和 Pull Request！

## 📝 更新日志 | Changelog

### v1.0.0
- ✅ Basic Maze Game 基础迷宫游戏
- ✅ 20 Wall/Player/Goal Styles 20种墙壁/玩家/终点样式
- ✅ Sound System 音效系统
- ✅ Particle/Firework Effects 粒子/烟花特效
- ✅ Touch Controls 触屏控制

## 📄 许可证 | License

MIT License - Free to use, star welcome! 自由使用，欢迎 Star ⭐

---

Made with ❤️ by [jianRY](https://github.com/jianRY)