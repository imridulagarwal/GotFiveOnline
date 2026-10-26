# Got Five! — Multiplayer Web Edition

A light-themed, responsive (Mobile, Tablet, and Desktop) multiplayer logic and deduction web game inspired by *Got Five!* by Yoann Levet (Blue Orange Games).

## Features
- **Auto-Assigned Random Player IDs** (`PLR-XXXX`) on entry
- **2–4 Player Multiplayer Rooms** (`G5-XXXX`) powered by PeerJS (WebRTC) + BroadcastChannel
- **1-Click Invite Links** (`?room=G5-XXXX`) that auto-join friends on mobile, tablet, or desktop
- **Individual Per-Player Turn Timers** (`10s–300s` per seat)
- **Smart Auto-Deduce & Cross-Off Helpers**

## Quickstart: Host on GitHub Pages in 60 Seconds
1. Create a new public repository on GitHub (https://github.com/new) named `got-five-game`.
2. Upload `index.html`, `.nojekyll`, and `README.md` to the root of your repository and click **Commit changes**.
3. Go to **Settings → Pages**, set **Source** to **Deploy from a branch**, select **`main`** and **`/ (root)`**, and click **Save**.
4. Your live multiplayer game will be ready at `https://<your-username>.github.io/got-five-game/`!
