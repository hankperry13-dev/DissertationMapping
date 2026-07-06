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
- **Templates** — start a new chapter from a preset structure (Introduction, Literature review, Methodology, Empirical/results, Argument/discussion, IMRaD) instead of a blank canvas.
- **Sub‑maps** — click the *sub‑map* icon (`⤢`) on any node to zoom into a nested map for that idea; nest as deep as you like. Breadcrumbs at the top let you jump back out.
- **Argument panel** — per‑chapter **Research question**, **Thesis / claim**, and **Argument summary** fields to hold your through‑line.
- **Argument‑checker prompts** — give a node a *type* (Claim, Evidence, Counter‑point, Gap, Method, Source, Question, To‑do, Idea) and the details panel asks type‑specific questions ("What evidence backs it up?", "What would a critic say?") with answer boxes and a completeness meter. Free‑form **notes** live here too.
- **Collapse / expand** — fold a node's branch (the `−`/`+` button under it) to hide its descendants and cut visual load; the button shows how many nodes are hidden.
- **Connection styles** — click any connection to set its relationship — *Relates to, Leads to, Supports, Contradicts, Causes, Example of* — each with its own colour, line style and arrow, plus an optional label.
- **Parking lot** (`🅿`) — a shared scratch drawer to dump stray thoughts the moment they occur, without derailing; sort them into a map (or delete them) later.
- **Undo / redo** — full history with the toolbar arrows or `Ctrl/Cmd+Z` and `Ctrl/Cmd+Y` (`Shift` to redo).
- **Print / PDF** (`🖨`) — generate a clean one‑pager for a chapter: title, argument summary, the map, and a text outline. Print to paper or "Save as PDF".
- **Fast, tactile mapping** — double‑click the canvas to add a node, drag the handle on a node to draw a connection (or drop it on empty space to make a linked child), colour‑code nodes, drag to rearrange, pan and zoom.
- **Light / dark theme** (`🌙`/`☀`) and a **dyslexia‑friendly font** toggle (`Aa`).
- **Focus mode** — hide the sidebar (`☰`) to reduce clutter.
- **Local & private** — data lives in your browser via `localStorage`; nothing is sent anywhere. Export/Import gives you portable JSON backups.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| `N` | Add node |
| `C` | Toggle connect mode |
| `F` | Fit map to screen |
| `Ctrl/Cmd+Z` | Undo |
| `Ctrl/Cmd+Y` / `Ctrl/Cmd+Shift+Z` | Redo |
| `Del` / `Backspace` | Delete selected node |
| `Esc` | Exit connect mode / close popovers & panels |
| Double‑click canvas | Add a node where you click |
| `Enter` (editing a node) | Finish editing |

## Tech

Plain HTML, CSS, and JavaScript in one file (`index.html`). No build step and no dependencies.
