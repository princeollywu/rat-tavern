# 🐀 Rat Tavern — The Board Game

A digital board game built with HTML, CSS and JavaScript. Play it here: **[princeollywu.github.io/rat-tavern](https://princeollywu.github.io/rat-tavern)**

---

## 🎮 Game Modes

### ⚔️ Battle Mode
Fight monsters AND each other. The last player standing wins the Rat Tavern!

### 🗺️ Adventure Mode
Work your way through the levels, defeating monsters and finding the exit. Can you escape?

---

## 🧑‍🤝‍🧑 Characters

| Character | ⚔️ Attack | 🛡️ Defence | ⚡ Speed | ❤️ HP |
|-----------|-----------|------------|---------|-------|
| 🤖 Robot  | 3         | 8          | 9       | 20    |
| 👁️ Cyclops | 9        | 7          | 3       | 25    |

- **Robot** — A speedy tank. Hard to hurt and hard to hit, but not the strongest hitter.
- **Cyclops** — A slow but devastating bruiser. High attack makes every hit count!

Player 1 and Player 2 must pick different characters.

---

## 🗺️ Level 1 — The Rat Tavern

The Rat Tavern is a creepy inn full of monsters. It has these rooms:

| Room | Monster | Difficulty |
|------|---------|------------|
| Entrance | None | Safe |
| Guest Room | 💀 Skeleton | Weak |
| Cat Room | 💀 Skeleton | Weak |
| Meeting Room | 🐀 Guard Rat | Medium |
| Bedroom | 🐀 Guard Rat | Medium |
| Kitchen | 🐀 Guard Rat | Medium |
| Alley | 💀 Skeleton | Weak |
| Restaurant | 👑 Giant Rat Boss | **BOSS** |
| Exit | None | 🎉 Escape! |

---

## ⚔️ How Combat Works

1. When you enter a room with a monster, you can choose to **Attack!**
2. Both sides roll a **dice (1–6)**
3. Damage = **(Your ATK + your roll) − (Enemy DEF + their roll)**, minimum 1
4. Enemies **counter-attack** automatically after your strike
5. Keep rolling until the monster (or you!) reaches **0 HP**
6. In Battle Mode, you can also attack the **other player** if you're in the same room!

---

## 🕹️ How to Play

1. Choose **Battle Mode** or **Adventure Mode**
2. Player 1 picks a character, then Player 2 picks a different one
3. Both players start at the **Entrance**
4. On your turn, choose a connected room to move to
5. If there's a monster — fight it! If there's another player (Battle Mode) — fight them!
6. Click **End Turn** when you're done

**Adventure Mode win:** Reach the Exit!  
**Battle Mode win:** Be the last player with HP above zero!

---

## 🛠️ How to Run

This is a single-file game — no install needed!

- **Online:** Visit the GitHub Pages link above
- **Locally:** Download `index.html` and open it in any web browser

---

## 🗺️ Planned Levels

- [x] Level 1 — The Rat Tavern
- [ ] Level 2 — *(coming soon!)*
- [ ] Level 3 — *(coming soon!)*

Items and weapons will be introduced in Level 2!

---

## 👾 Made By

Designed by a 12-year-old game designer, coded with Claude (Anthropic).  
Characters drawn by hand ✏️ — Robot (P1) and Cyclops (P2).
