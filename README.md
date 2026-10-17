# Triage OS

A gamified "Discipline OS" for habits and tasks, built around NHS shift work. One self-contained file: open `index.html` in any browser, or host it anywhere static (GitHub Pages works). Data stays in your browser's localStorage; use **settings.cfg → Export JSON** to back it up.

Programs: `today.sys` (briefing, loadout, Highlight, laser focus), `triage.exe` (waiting room + urgency board), `habits.exe` (start/end routine levels), `week.log`, `month.map`, `handover.txt` (evening reflection: what I did, what I missed, why, what changes tomorrow), `world.exe` (first-person walk through rooms for each life category), `settings.cfg`.

`world.exe` loads three.js r128 from cdnjs the first time it opens; everything else works offline.

Type into the `C:\TRIAGE>` prompt to admit a task instantly, or type a command (`help`, `laser 25`, `week`, …).
