# ✨ Fuse — the premium merge puzzle

**Slide. Fuse. Master.** Fuse is a beautiful, addictive take on the most-loved
casual puzzle of all time: slide the tiles, merge equal numbers, and chase
**2048** — and far beyond.

👉 **Play free:** https://rahulatrkm.github.io/fuse/

One tap to start, impossible to put down. Free forever to play — go **Pro** once
to unlock the full experience.

## Why people love it

- **Silky, physical animations** — tiles glide and pop with satisfying weight
- **Instant, no-friction play** — swipe on mobile, arrow keys / WASD on desktop
- **Auto-save** — close the tab, come back, your board is exactly where you left it
- **No ads, no tracking, works offline** — it's a single `index.html`

## Fuse Pro — $4.99, one-time, yours forever

The free game is complete. Pro is for the people who fall in love with it:

| ✨ Feature | What you get |
|-----------|--------------|
| ↶ **Unlimited Undo** | Take back any move, chase the perfect run |
| 🎨 **6 Premium Themes** | Sunset, Emerald, Neon, Royal, Ink, Ocean |
| ⏱️ **Time Attack** | 90 seconds, how high can you score? |
| 📅 **Daily Challenge** | Same seeded board for everyone, every day |
| 🧩 **5×5 Big Grid** | A deeper, meaner challenge |

**Buy Pro:** [rahulatrkm.gumroad.com/l/fuse](https://rahulatrkm.gumroad.com/l/fuse)

### How Pro unlocking works

- Purchase delivers a license key (e.g. `FUSE1A2B`) via Gumroad.
- In-game: **Go Pro → Enter your key → Redeem.** Unlock is stored locally.
- Or deep-link: `https://rahulatrkm.github.io/fuse/?key=XXXXXXXX`.

Keys are offline-verifiable (checksum), so unlocking works with zero backend and
zero tracking. Swap `BUY_URL` in `index.html` for your real Gumroad/Stripe
product, and generate keys that pass the `validKey()` checksum.

## How to play

- **Move:** swipe, or arrow keys / **WASD**
- Two equal tiles that touch when you move will **fuse** into their sum
- Every move drops a new tile — the board fills up
- Reach **2048** to win; keep going for a high score
- **Undo** with the ↶ button or `Ctrl/⌘ + Z` (Pro)

## Tech

A single self-contained `index.html` — HTML5 + vanilla JavaScript, no build step,
no dependencies, no network calls. Ships as a static site; hosts free on GitHub
Pages. Smooth 60fps transform-based tile animations, seeded RNG for the Daily
mode, and `localStorage` for saves, best score, theme and Pro status.

## License

Code and art: MIT — see [LICENSE](LICENSE).
