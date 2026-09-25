<div align="center">

```text
     ██╗██╗  ██╗███╗   ███╗██╗  ██╗
     ██║╚██╗██╔╝████╗ ████║╚██╗██╔╝
     ██║ ╚███╔╝ ██╔████╔██║ ╚███╔╝ 
██   ██║ ██╔██╗ ██║╚██╔╝██║ ██╔██╗ 
╚█████╔╝██╔╝ ██╗██║ ╚═╝ ██║██╔╝ ██╗
 ╚════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝
```

</div>

## Hi, I'm Jome 👋

Thailand · TH / EN · 30s

I build small desktop tools that fix things that annoy me, and then I
actually use them. Mostly Python, some JavaScript.

### How I work

Most of the code here is **AI-assisted**. I build with coding agents rather
than typing every line myself, and I'd rather say that up front than have you
work it out from the commit history.

What that means in practice:

```text
  ┌──────────────┐    ┌──────────────┐    ┌──────────────┐    ┌──────────────┐
  │ I decide     │    │ an agent     │    │ I run it,    │    │ it ships,    │
  │ what & why,  │───>│ writes the   │───>│ try to break │───>│ and I use it │
  │ and spec it  │    │ code         │    │ it           │    │ myself       │
  └──────────────┘    └──────────────┘    └──────┬───────┘    └──────────────┘
          ^                                      │
          └────── not right yet? push back ──────┘
```

When the tool supports it, commits carry a `Co-Authored-By:` trailer as
well, so it shows up per-commit and not just on this page.

### What I'm into

- **Python** — where I spend most of my time
- **JavaScript** — when it has to run in a browser
- **Gaming** 🎮 — probably too much of it. A fair few of these tools started
  life as "I wish my game did this"

### Things I've built

#### [Kanban Overlay](https://github.com/sirawitbm/kanban-overlay)

![Kanban Overlay: a small bar docked inside the Windows taskbar, beside the tray](https://raw.githubusercontent.com/sirawitbm/kanban-overlay/main/docs/bar.png)

A planning board that lives *inside* the Windows taskbar. Most of the time
it's just that strip beside the clock — what's due today, what's overdue.
Click it and the board unfolds: tasks grouped by when they're due, splitting
themselves into weeks and then days as a month fills up. The panels detach
and float anywhere, and a ghost mode keys the background out entirely so
clicks fall straight through to whatever you're actually working in.

Built because I wanted my task list on screen while I kept using everything
else — without giving it a window of its own.

**[Download for Windows](https://github.com/sirawitbm/kanban-overlay/releases/latest)**
· Python, no dependencies

---

#### [Aldur Rune Tracker](https://github.com/sirawitbm/aldur-rune-tracker)

<img align="right" width="96" src="https://raw.githubusercontent.com/sirawitbm/aldur-rune-tracker/main/data/RA.jpg" alt="Aldur Rune Tracker logo">

A small overlay for **Path of Exile 2** Grand Expeditions. Hover a rune slot,
press a hotkey, and it reads the rune straight off the tooltip, remembers
which Aldur Runes carry forward through the chain, and warns you when the
slot you're about to pick isn't passable.

It deliberately won't tell you which rune to choose. That part stays yours.

**[Download for Windows](https://github.com/sirawitbm/aldur-rune-tracker/releases/latest)**
· Python · PySide6 · Windows OCR

<br clear="right">

---

#### [Turbo Tracker](https://github.com/sirawitbm/dota2-turbo-tracker)

<img align="right" width="260" src="https://raw.githubusercontent.com/sirawitbm/dota2-turbo-tracker/main/docs/recap.png" alt="Turbo Tracker recap card: Victory as Pudge, 14/5/21">

A game log for **Dota 2 Turbo**, the mode most stat sites barely bother
with. It listens to Dota's official Game State Integration, so the moment a
match ends a recap card pops up: result, K/D/A, and *"3rd game on Pudge
today, 2-1 on him"*. Over time it builds your per-hero record, win rate and
streaks, and it checks OpenDota so practice games never pollute the Turbo
numbers.

It only ever sees your own hero. No input, no memory reading, nothing a
stats site couldn't show you.

**[Download for Windows](https://github.com/sirawitbm/dota2-turbo-tracker/releases/latest)**
· Python · PySide6

<br clear="right">
