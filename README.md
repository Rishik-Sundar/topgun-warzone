# Top Gun: War Zone

A browser-based aerial combat game inspired by Top Gun. Fly an F-14 Tomcat, dogfight enemy planes, drop bombs, dodge SAMs, and battle bosses across 5 zones.

**Play it live:** open `index.html` in any modern browser, or visit the GitHub Pages site (enable in repo settings).

## Features

- **Solo / Local 2P / Online 2P** — play alone, splitscreen on one keyboard, or over the internet with a friend via room codes
- **4 Levels** — Pacific, Desert, Mountains, Night Ops
- **3 Difficulties** — Easy (150 HP, slow enemies) / Medium / Hard (60 HP, fast enemies)
- **Normal vs Practice** — Normal tracks your weekly highscore for the 🏆 Golden Wings prize
- **Online Versus mode** — bounded-arena dogfight, first to 5 kills wins
- **Online Co-op mode** — both players take on the AI together
- **5 enemy types** — fighters, bombers, helis, AAA ground bases, SAM silos, boss waves
- **Powerups** — rapid fire, shield, extra bombs

## Controls

- **P1**: WASD to move, SPACE to shoot, X to drop bomb, F to release flares
- **P2 (local)**: IJKL to move, ENTER to shoot, B to bomb, G to flare
- **P2 (online)**: WASD/SPACE/X/F (your local keys)
- V to cycle camera, R to restart, M to return to menu

## Online Multiplayer Setup

1. Pick **ONLINE 2P** in the menu
2. Choose **CO-OP** or **VERSUS**
3. One player clicks **HOST GAME** → share the 8-character code
4. Other player pastes the code and clicks **JOIN**
5. Both jets in the air. Have fun.

Online multiplayer uses [PeerJS](https://peerjs.com/) (WebRTC) — peer-to-peer, no server costs.

## Tech

Pure HTML5 Canvas + JavaScript. No build step, no framework. Single file (`index.html`) is the entire game.

## License

MIT
