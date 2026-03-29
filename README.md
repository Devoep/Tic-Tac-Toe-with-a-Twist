# ⚡ Chaos Tic-Tac-Toe

A fresh twist on the classic game — the rules randomly change every round, keeping both players on their toes.

**[▶ Play it live →](https://devoep.github.io/Tic-Tac-Toe-with-a-Twist/)** *(replace with your GitHub Pages URL)*

---

## What makes it different?

Every new game draws a random **Chaos Rule** that shakes up the usual 3-in-a-row formula:

| Rule | What happens |
|------|-------------|
| **Normal** | Classic rules — a calm round to plan your comeback |
| **Swap!** | Every 2 moves, all X's and O's on the board flip symbols |
| **Vanish** | You can only hold 3 pieces — placing a 4th removes your oldest |
| **Blocked cell** | One random cell is sealed off for the entire round |
| **Bomb move** | Each player gets one bomb to erase an opponent's piece |
| **Speed round** | 5 seconds per move or your turn is forfeited |

Scores persist across rounds — first to dominate the chaos wins the session.

---

## Tech stack

- **Pure HTML + CSS + JavaScript** — zero dependencies, zero build step
- Single file: `chaos-tictactoe.html`
- Google Fonts (Space Mono + Syne) loaded via CDN
- Works on desktop and mobile

---

## Run locally

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/chaos-tictactoe.git

# Open in browser — no server needed
open chaos-tictactoe.html
```

Or just double-click the file.

---

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your game will be live at `https://YOUR_USERNAME.github.io/chaos-tictactoe`

---

## Controls

- **Click** a cell to place your symbol
- **Bomb move** — when active, click an opponent's piece to destroy it
- **Enter** — start a new game after one ends
- **Escape** — close the how-to-play modal

---

## License

MIT — free to use, fork, and remix.
