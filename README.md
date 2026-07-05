# Dissertation Mapping

A visual, distraction-friendly mind‑mapping tool for planning dissertation chapters — built for visual learners and people with ADHD.

Create a map for each chapter, nest **sub‑maps** inside any node to break big ideas down, and keep each chapter's **research question, thesis, and argument summary** right above the canvas so you never lose the through‑line.

## How to use it

It's a single self‑contained file — no install, no account, no internet needed.

- **Open it:** double‑click `index.html` (or open it in any modern browser).
- **Host it:** push to GitHub and enable GitHub Pages to get a shareable link.

Everything you type is saved automatically in your browser on that device. Use **Export** to download a backup file (recommended often — it's your dissertation!) and **Import** to restore it or move to another computer.

## Features

- **Chapters** — one map per chapter, each with its own colour, listed in the sidebar.
- **Sub‑maps** — click *Open sub‑map* on any node to zoom into a nested map for that idea; nest as deep as you like. Breadcrumbs at the top let you jump back out.
- **Argument panel** — per‑chapter **Research question**, **Thesis / claim**, and **Argument summary** fields to hold your through‑line.
- **Fast, tactile mapping** — double‑click the canvas to add a node, drag the purple handle on a node to draw a connection (or drop it on empty space to make a linked child), colour‑code nodes, drag to rearrange, pan and zoom.
- **Focus mode** — hide the sidebar (`☰`) to reduce clutter.
- **Local & private** — data lives in your browser via `localStorage`; nothing is sent anywhere. Export/Import gives you portable JSON backups.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| `N` | Add node |
| `C` | Toggle connect mode |
| `F` | Fit map to screen |
| `Del` / `Backspace` | Delete selected node |
| `Esc` | Exit connect mode / close popovers |
| Double‑click canvas | Add a node where you click |
| `Enter` (editing a node) | Finish editing |

## Tech

Plain HTML, CSS, and JavaScript in one file (`index.html`). No build step and no dependencies.
