# 🎮 BODMAS Quest

> An interactive game that teaches the **Order of Operations (BODMAS)** through visual puzzles, drag-and-drop challenges, and step-by-step walkthroughs — all in a single HTML file.

---

## 🌐 Live Demo

**[▶ Play Now →](https://YOUR-USERNAME.github.io/bodmas-quest/bodmas_game.html)**

---

## 🎯 How to Play

Three game modes, one expression at a time:

| Mode | What you do |
|------|-------------|
| 🚌 **Arrange Steps** | Drag & drop the operations into the correct BODMAS order |
| 🎯 **What's Next?** | Pick which operation should be solved first (MCQ) |
| 🔢 **Calculate** | Work it out and type the final answer |

After every question, a **step-by-step walkthrough** shows exactly how the expression should be solved — great for learning from mistakes.

---

## 📐 BODMAS Reference

| Letter | Stands For | Priority |
|--------|------------|----------|
| **B** | Brackets | 1st |
| **O** | Orders (Powers & Roots) | 2nd |
| **D** | Division | 3rd (left → right) |
| **M** | Multiplication | 3rd (left → right) |
| **A** | Addition | 4th (left → right) |
| **S** | Subtraction | 4th (left → right) |

---

## ✨ Features

- 🚌 **Bus Route analogy** — an animated visual showing BODMAS priority as bus stops in order
- 🎨 **Color-coded operations** — each letter has its own distinct color throughout the game
- 📖 **Step-by-step solution reveal** — shown after every answer with animated steps
- 💡 **Hint system** — get a nudge at the cost of bonus points
- ❤️ **Lives + scoring** — 3 lives, score multiplies with difficulty level
- ⭐ **4 difficulty levels** — from simple `2 + 3 × 4` up to `2 × (3 + 4²) − 1`
- 🎉 **Confetti** on correct answers
- 📱 **Fully responsive** — works on mobile, tablet, and desktop

---

## 🚀 Running the Game

No installation, no server, no dependencies needed.

```bash
# Just open the file in any browser
bodmas_game.html → double click → done
```

Or serve it locally:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

---

## 📁 Files

```
bodmas-quest/
├── bodmas_game.html   ← entire game lives here
└── README.md
```

---

## 🛠️ Built With

- HTML5
- CSS3 (animations, drag-and-drop UI)
- Vanilla JavaScript (game logic, state, Drag & Drop API)

---

*Made for making maths actually fun. 💜*
