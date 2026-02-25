# 🕹️ P2P Web Arcade

A high-fidelity, multiplayer arcade suite built with vanilla JavaScript and PeerJS. This project features real-time, peer-to-peer gaming without the need for a centralized game server.

## 🚀 Live Demo
**[Click here to play the games!](https://abosaad55555555-afk.github.io/chessgame/)**

---

## 🎱 Featured Games

### 1. Pro Pool (Billiards)
A 100% physics-complete pool simulation.
* **Physics engine:** Features sub-stepping (300Hz), impulse-based elastic collisions, and vector-based cushion reflections.
* **Aiming:** Dynamic cue stick with power pull-back and ghost-ball trajectory guides.
* **Rules:** Full 8-ball logic, turn-persistence (pocket a ball to go again), and scratch handling.

### 2. Grandmaster Chess
* **Features:** Full move validation, turn-syncing, and a clean, responsive UI.
* **Connectivity:** Instant board synchronization across devices.

### 3. Strategy Suite
* **Checkers:** Classic 8x8 board with jump logic.
* **Tic-Tac-Toe:** Quick-play 3x3 match.

---

## 🛠️ How to Play Multiplayer
This arcade uses **Peer-to-Peer (P2P)** technology. To play with a friend:
1. Open a game (e.g., `pool.html`).
2. **Player 1:** Look at the unique 4-digit ID generated on your screen.
3. **Player 2:** Type Player 1's code into the "Join" box and hit **Connect**.
4. Once connected, the game state will sync automatically!

## 💻 Tech Stack
* **Language:** HTML5, CSS3, JavaScript (ES6+)
* **Networking:** [PeerJS](https://peerjs.com/) (WebRTC)
* **Physics:** Custom Vector Math engine (no external physics libraries)
* **Hosting:** GitHub Pages

---
*Created by abosaad55555555-afk*
