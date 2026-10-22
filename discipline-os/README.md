# Discipline OS

Better than yesterday. A personal operating system for routines, habits, goals, tasks and focus, built on *Atomic Habits* (James Clear) and *Make Time* (Jake Knapp & John Zeratsky).

It is a separate app from Triage OS in the repo root. It uses its own code, design and storage (`disciplineos.v1` in localStorage), so the two never touch each other's data.

## Run it

One self-contained file. Open `discipline-os/index.html` in any browser, or host the folder anywhere static (GitHub Pages works: `/discipline-os/`). Everything is stored in your browser only, so use **Settings → Back up and restore** now and then.

## What's inside

| Section | What it does |
| --- | --- |
| **Today** | Today's identity statement, your score out of 100 against yesterday and your 30-day average, the **Highlight**, morning and evening routines, today's plan with time blocks, the dopamine guard, and the evening reflection prompt. The order follows the time of day. |
| **Habits** | Morning, Evening and Anytime habits, plus **Break** for bad habits. Every habit has a habit-stack cue, a time and place, a **full** and a **2-minute** version, chosen days, an Energize tag (sleep, move, fuel, daylight), the four laws, and the identity it votes for. |
| **Tasks** | The master list as three columns: **Urgent**, **Semi-urgent**, **Routine**. Drag a card by its handle to move it (touch and mouse, with edge autoscroll), or tap the urgency tag to cycle it. Add any task to today's plan or make it the Highlight. |
| **Goals** | Daily, weekly, monthly, quarterly and yearly goals. Each one can have a numeric target, support a bigger goal (year → quarter → month → week → day), and vote for an identity. Unfinished goals can be carried over into the next period. |
| **Progress** | Week view: daily score chart against your average, habit grid, slips grid, focus time, time lost, XP, and arrows against last week. Month view: score heatmap calendar, habit completion rates, and the 1% compounding counter. |
| **Reflect** | Evening reflection: energy and focus ratings, what went well, what got in the way, one adjustment, tomorrow's Highlight (waiting for you in the morning), gratitude. |

## The rules it runs on

- **Votes for identity.** Onboarding asks for "I am someone who…" statements. Each completed habit is a vote, counted on the Habits page.
- **Two-minute rule.** Full earns full XP; the 2-minute version earns 40% and still keeps the streak.
- **Never miss twice.** One missed day holds the streak and shows a warning. Two in a row resets it.
- **Highlight.** One per day, worth 50 XP and 20 of the day's 100 points. **Laser** is the focus timer (15/25/50/90 min) and counts how often you leave the screen.
- **Bad habits.** Log every slip (in minutes or times, with the trigger) and every urge you resist. Each bad habit shows today, this week vs last week, days clean, a 28-day strip, and for time-based ones the projected hours per year. **Tempted?** opens a 90-second urge-surf with your identity statement and a 2-minute habit to do instead.
- **Daily score.** Habits 50 (2-minute counts 0.7), Highlight 20, planned tasks 15, focus 15 (60 minutes is full marks), minus up to 30 for slips.
- **XP and levels.** Habits, Highlight (50), tasks (10/20/30 by urgency), goals (15 daily to 600 yearly), focus, urges resisted (5, up to 10 a day), reflection (15) and a +10 bonus for beating yesterday's score. Ranks run from Starter to Legend.

The starter habits, tasks and goals are editable examples; tasks and goals marked "example" can be cleared in one tap from the Tasks page.
