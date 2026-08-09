# KuboOS — Devlogs

## DEVLOG #1 — skeleton + window manager (09 aug 2026)
- repo init, html stub replaced with real structure
- drawn the desktop: dark cyberpunk wallpaper with grid + glow orbs, all pure css
- built kubo-wm: windows that drag, focus, minimize, maximize and close
- taskbar with running-app pills + live clock so it actually feels like an os

## DEVLOG #2 — the apps (09 aug 2026)
- **notes** — scratchpad that autosaves to localStorage (survives refresh)
- **calculator** — fully working with keyboard-style buttons, ÷ × − + ( ) and %
- **terminal** — fake shell with real commands: help, neofetch, sudo (denied, obviously), open
- **devlog** — this app, progress displayed inside the os itself

## DEVLOG #3 — polish + extras beyond the guide (09 aug 2026)
- boot sequence with animated loading bar that fades into the desktop
- start menu (K button) with app grid
- window **resizing** from the corner handle, double-click titlebar to maximize
- no password, no login — anyone who opens the page is in. exactly how the mission wanted it
