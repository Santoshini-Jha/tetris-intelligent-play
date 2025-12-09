# tetris-intelligent-play 🎮

 A browser-based Tetris game with a built‑in AI player, created using pure HTML, CSS, and JavaScript — no external libraries required. The AI evaluates every possible placement of the current piece and picks the best move based on common Tetris heuristics.

<img width="1903" height="968" alt="Screenshot 2025-12-09 195226" src="https://github.com/user-attachments/assets/29c01224-e790-4eb4-9b4c-7c06f145800b" />

# 🎮 Features
 . Fully playable Tetris (manual mode with arrow keys + space)
 . Built‑in AI player that can play automatically
 . Adjustable AI weights to modify gameplay style
 . Adjustable fall speed & AI decision delay
 . Clean, single‑file implementation (index.html)
 . Responsive UI with real-time score, lines, and level tracking

# 🧠 AI Logic
 The AI evaluates all legal rotations and positions of a piece using a heuristic:
 score = (linesCleared * wLines)
        - (aggregateHeight * wHeight)
        - (holes * wHoles)
        - (bumpiness * wBumpiness)
 You can tweak all weights in the UI to experiment with how the AI plays.

# 📂 Repository Structure
 Tetris-AI/
    ├── index.html   # Main game file (HTML + CSS + JS)
    └── README.md    # Game documentation

# ▶️ How to Run
 1. Download or copy index.html from the repository.
 2. Open it in any modern browser (Chrome, Edge, Firefox, etc.)
 3. Start playing or enable the AI.

# ⌨️ Controls
 . Left Arrow → Move piece left
 . Right Arrow → Move piece right
 . Down Arrow → Soft drop
 . Up Arrow → Rotate piece
 . Space → Hard drop

# 🤖 AI Mode
 . Click Start AI to let the AI play automatically. You can change:
 . AI decision delay (ms)
 . Lines / Height / Holes / Bumpiness weights for the heuristic

# 🚀 Future Improvements
 . Add next‑piece lookahead for stronger AI
 . Add sound effects
 . Improve UI with better theming
 . Add leaderboard / high-score save

Convert into a React app

# 📜 License
 MIT License — free to use, modify, and distribute.

 Enjoy playing and experimenting with Tetris-AI!
