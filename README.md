# 🐍 贪吃蛇 Pro

一个现代化的 HTML5 Canvas 贪吃蛇游戏，具有霓虹风格的视觉效果和流畅的游戏体验。

![Snake Game](https://img.shields.io/badge/HTML5-Canvas-00ff88?style=flat-square&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-ffd93d?style=flat-square&logo=javascript)
![License](https://img.shields.io/badge/License-MIT-6bcb77?style=flat-square)

## ✨ 功能特性

- 🎮 **经典玩法** - 原汁原味的贪吃蛇游戏体验
- 🎨 **霓虹视觉** - 渐变色彩、发光效果、流畅动画
- 🌓 **主题切换** - 深色/浅色主题随意切换
- ⚙️ **三档难度** - 简单/中等/困难，适合不同水平的玩家
- 🏆 **分数记录** - 本地存储最高分，挑战自我极限
- 📱 **移动适配** - 支持触屏操作，手机也能玩
- ⌨️ **键盘控制** - 方向键或 WASD 键均可控制
- ⏸️ **暂停功能** - 随时暂停，继续游戏

## 🎯 操作说明

| 操作 | 按键 |
|------|------|
| 移动方向 | ↑↓←→ 或 WASD |
| 开始/暂停 | 空格键 |
| 移动端 | 屏幕方向按钮 |

## 🚀 快速开始

### 方式一：直接打开

在浏览器中直接打开 `index.html` 文件：

```bash
# Linux
xdg-open index.html

# macOS
open index.html

# Windows
start index.html
```

### 方式二：本地服务器

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (需要安装 http-server)
npx http-server -p 8000
```

然后访问 `http://localhost:8000`

## 📁 项目结构

```
snake-game/
├── index.html    # 游戏主文件（包含 HTML/CSS/JS）
├── plan.md       # 项目设计文档
├── .gitignore    # Git 忽略配置
└── README.md     # 项目说明文档
```

## 🛠️ 技术栈

- **HTML5 Canvas** - 游戏渲染
- **CSS3** - 样式与动画效果
- **JavaScript ES6+** - 游戏逻辑
- **LocalStorage** - 数据持久化

## 📝 游戏配置

在 `index.html` 中可以修改游戏参数：

```javascript
const CONFIG = {
    gridSize: 20,           // 格子大小（像素）
    gridWidth: 30,          // 横向格子数
    gridHeight: 20,         // 纵向格子数
    speeds: {
        easy: 200,          // 简单速度
        normal: 120,        // 中等速度
        hard: 80            // 困难速度
    }
};
```

## 🎨 预览效果

游戏界面包含：
- 霓虹风格的游戏画布
- 实时分数和最高分显示
- 难度选择按钮
- 开始/暂停/重置控制
- 移动端方向控制

## 📄 License

MIT License

---

**Enjoy the game! 🎮**
