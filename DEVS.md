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

## DEVLOG #4 — the humanise pass, v1.1 (09 aug 2026)
- generated a proper **wallpaper** — aurora + city lights, with vignette and grid overlay
- new **welcome app** that greets by time of day ("good evening, akshat") and shows on first boot
- **toast notifications** — "note saved", plus custom os-styled dialogs instead of browser confirm()
- windows **animate** in, snap to the top edge to maximize, drag a maximized window down to restore it
- calculator got **keyboard support** (just type to calculate), terminal got `joke`, `hi`, `kubo` commands
- warmer palette, proper fonts (Inter + Space Grotesk), gradient app tiles, friendlier copy everywhere

## DEVLOG #5 — lockscreen + it stops sounding like a robot, v1.2 (09 aug 2026)
- added a **lockscreen** — the os asks your name, stores it, and greets you with it
- your name shows up in the welcome app, the start menu, the terminal (whoami, neofetch) and the boot line
- killed every emoji, rewrote all the copy so it sounds like a person wrote it, not an ai
- returning users get a one-tap unlock: "good to see you, [name]. no password, just hit enter."
