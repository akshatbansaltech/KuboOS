# KuboOS

KuboOS is a web-based operating system built from scratch with HTML, CSS, and JavaScript. It runs entirely in the browser with no frameworks or dependencies.

I built it as part of the **Make Your Own OS** workshop.

**Live:** https://akshatbansaltech.github.io/KuboOS/

## Features

* Boot sequence with an animated loading bar
* Lockscreen that remembers your name
* Draggable and resizable windows
* Minimize, maximize, close, and window snapping
* Taskbar with running apps and a live clock
* Start menu and desktop icons
* Toast notifications and custom dialogs
* Data saved locally using `localStorage`
* Multiple webpages: `lockscreen.html`, `index.html` (desktop), and each app is its own page in `apps/`

### Apps

* **Notes** — autosaves notes locally
* **Calculator** — basic calculator with keyboard support
* **Terminal** — custom commands including `neofetch`, `whoami`, `clear`, and `sudo`
* **Welcome** — personalized welcome screen
* **About** — information about KuboOS

## Run locally

There is no setup required.

Clone the repository:

```bash
git clone https://github.com/akshatbansaltech/KuboOS.git
```

Then open `index.html` in your browser.

## How it works

KuboOS doesn't use React, Electron, or any other framework. It's a set of plain HTML pages:

* `lockscreen.html` — asks your name, then opens the desktop
* `index.html` — the desktop: window manager, taskbar, start menu, boot sequence
* `apps/*.html` — each app is its own page, loaded inside a draggable window

The window manager, apps, animations, taskbar, start menu, and terminal are all written in vanilla JavaScript. App pages talk to the desktop through a tiny API (`window.kuboOS`).

## License

MIT — see [LICENSE](https://github.com/akshatbansaltech/KuboOS/blob/main/LICENSE).
