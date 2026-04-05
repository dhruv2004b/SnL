# 🐍 Snakes & Ladders 🪜

<div align="center">

![Snakes & Ladders](https://img.shields.io/badge/Game-Snakes%20%26%20Ladders-f5a623?style=for-the-badge&logo=game-icons&logoColor=white)
![Players](https://img.shields.io/badge/Players-2--8-4ecdc4?style=for-the-badge)
![HTML](https://img.shields.io/badge/Built%20With-HTML%20%2F%20CSS%20%2F%20JS-ff6b6b?style=for-the-badge&logo=html5&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-a29bfe?style=for-the-badge)

**A fully-featured, browser-based Snakes & Ladders game for 2–8 players.**  
No dependencies. No installs. Just open and play.

🎮 **[Play Now → sn-l.vercel.app](https://sn-l.vercel.app/)**

</div>

---

## ✨ Features

- 🎯 **2 to 8 Players** — Select your player count on the setup screen before starting
- 🐍 **10 Snakes & 10 Ladders** — Classic board layout with faithful rules
- 🎲 **Animated Dice** — Rolling animation with realistic dot patterns
- 🏃 **Step-by-step Movement** — Tokens animate square by square across the board
- 🎨 **Unique Player Colors** — Each player gets a distinct colored token
- 📌 **Smart Token Stacking** — Multiple tokens on the same square fan out in a circle
- 📜 **Live Game Log** — Every roll, snake bite, and ladder climb is logged
- 🏆 **Winner Modal** — Celebrate the winner with a replay or new game option
- 📱 **Fully Responsive** — Works on desktop, tablet, and mobile browsers
- ⚡ **Zero Dependencies** — Pure HTML, CSS, and JavaScript — no libraries needed

---

## 🎮 How to Play

1. **Open the game** at [sn-l.vercel.app](https://sn-l.vercel.app/)
2. **Choose the number of players** (2–8) on the setup screen and tap **Start Game**
3. Players take turns — tap **Roll 🎲** to roll the dice
4. Your token moves forward by the rolled number
5. **Land on a ladder base** → climb up to a higher square 🪜
6. **Land on a snake's head** → slide down to a lower square 🐍
7. First player to land on **exactly square 100** wins!
8. If your roll would take you past 100, you stay put and the turn passes

---

## 🗺️ Board Layout

The board follows the classic 10×10 serpentine layout:

- Squares numbered **1–100**, starting from the bottom-left
- Even rows go left → right; odd rows go right → left
- Square **1** is the START, square **100** is the WIN

### 🐍 Snake Positions

| Head (Start) | Tail (End) |
|:---:|:---:|
| 99 | 78 |
| 95 | 75 |
| 93 | 73 |
| 87 | 24 |
| 64 | 60 |
| 62 | 19 |
| 56 | 53 |
| 49 | 11 |
| 47 | 26 |
| 16 | 6  |

### 🪜 Ladder Positions

| Bottom (Start) | Top (End) |
|:---:|:---:|
| 1  | 38 |
| 4  | 14 |
| 9  | 31 |
| 20 | 42 |
| 28 | 84 |
| 40 | 59 |
| 51 | 67 |
| 63 | 81 |
| 71 | 91 |
| 80 | 100 |

---

## 🚀 Getting Started

### Play Online
Just visit **[sn-l.vercel.app](https://sn-l.vercel.app/)** — no setup needed.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/snakes-and-ladders.git

# Navigate into the folder
cd snakes-and-ladders

# Open in your browser
open index.html
```

> No build step, no npm install, no server required. Just open `index.html` in any modern browser.

---

## 🗂️ Project Structure

```
snakes-and-ladders/
│
├── index.html      # Complete game — all HTML, CSS, and JS in one file
└── README.md       # You are here
```

The entire game is self-contained in a single `index.html` file for maximum portability.

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| **HTML5 Canvas** | Board drawing — cells, snakes, ladders, player tokens |
| **Vanilla JavaScript** | Game logic, animations, state management |
| **CSS3** | UI layout, animations, responsive design |
| **Google Fonts** | Fredoka One (headings) + Nunito (body text) |
| **Vercel** | Hosting & deployment |

---

## 🌐 Deployment

This project is deployed on **[Vercel](https://vercel.com/)**.

To deploy your own copy:

1. Fork this repository
2. Go to [vercel.com](https://vercel.com/) and sign in
3. Click **Add New Project** → import your fork
4. Vercel auto-detects it as a static site — click **Deploy**
5. Your game is live! 🎉

---

## 📱 Browser Support

| Browser | Supported |
|---|:---:|
| Chrome | ✅ |
| Firefox | ✅ |
| Safari | ✅ |
| Edge | ✅ |
| Mobile Chrome | ✅ |
| Mobile Safari | ✅ |

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute it.

---

<div align="center">

Made with ❤️ &nbsp;|&nbsp; 🎮 [Play Now](https://sn-l.vercel.app/)

</div>
