# Discipline OS

Better than yesterday. A personal operating system for routines, habits, goals, tasks and focus, built on *Atomic Habits* (James Clear) and *Make Time* (Jake Knapp & John Zeratsky).

It is a separate app from Triage OS in the repo root. It uses its own code, design and storage (`disciplineos.v1` in localStorage), so the two never touch each other's data.

## Run it

One self-contained file. Open `discipline-os/index.html` in any browser, or host the folder anywhere static (GitHub Pages works: `/discipline-os/`). Everything is stored in your browser only, so use **Settings → Back up and restore** now and then.

## Design

You race your own ghost. The top of Today is a two-lane track: you today (solid green) against yesterday's score (a dashed ghost), with your 30-day average marked across it. The headline is set in Anybody, a variable-width typeface, and it gets wider as you pull ahead of yesterday and narrower as you fall behind. Today runs down a timeline (wake, daytime, evening, bed) with a marker showing where you are, and a **Tempted?** button floats on the screen for the moment an urge hits.

Body text is Atkinson Hyperlegible, chosen to be easy to read when you're tired. Colours: green means you, progress and anything done; violet means actions, focus and evenings; lilac means yesterday and averages; crimson is kept for slips and Urgent tasks.

## What's inside

| Section | What it does |
| --- | --- |
| **Today** | The ghost race (your score out of 100 against yesterday and your 30-day average), today's identity vote, the **Highlight**, a quote, then a timeline of the day: morning routine and check-in, today's plan with time blocks, evening routine, and the evening reflection. Bad-habit logging sits at the bottom, with **Tempted?** always on screen. |
| **Habits** | Morning, Evening and Anytime habits, plus **Break** for bad habits. Every habit has a habit-stack cue, a time and place, optional **full** and **2-minute** versions, chosen days, an Energize tag (sleep, move, fuel, daylight), the four laws, and the identity it votes for. Leave any of the four laws blank and it's written for you from the habit (training, study, content, mindfulness, sleep, daylight, water, food, phone-free, tidying, money, keeping in touch, personal care, or general), using your cue, time, place, 2-minute version and identity. Generated laws update when you edit the habit; anything you type yourself is kept. |
| **Tasks** | The master list as three columns: **Urgent**, **Semi-urgent**, **Routine**. Drag a card by its handle to move it (touch and mouse, with edge autoscroll), or tap the urgency tag to cycle it. Add any task to today's plan or make it the Highlight. |
| **Goals** | Daily, weekly, monthly, quarterly and yearly goals. Each one can have a numeric target, support a bigger goal (year → quarter → month → week → day), and vote for an identity. Unfinished goals can be carried over into the next period. |
| **Progress** | Week view: daily score chart against your average, habit grid, slips grid, focus time, time lost, XP, and arrows against last week. Month view: score heatmap calendar, habit completion rates, and the 1% compounding counter. |
| **Pinned line** | A not-average quote pinned under the header on Today, visible while you scroll. Pick one or write your own in Settings. |
| **Quotes** | A quote card on Today (one per day, tap **Another** for more), plus a quote in Laser focus, the urge-surf screen and every level-up. The built-in quotes cover motivation, discipline, Naruto, Dragon Ball Z, One Piece, Demon Slayer and Cristiano Ronaldo. Choose the categories and add your own (`quote — who said it`) in Settings. |
| **Reflect** | Evening reflection: energy and focus ratings, what went well, what got in the way, one adjustment, tomorrow's Highlight (waiting for you in the morning), gratitude. |

## The rules it runs on

- **Votes for identity.** Onboarding asks for "I am someone who…" statements. Each completed habit is a vote, counted on the Habits page.
- **Two-minute rule.** Full earns full XP; the 2-minute version earns 40% and still keeps the streak.
- **Never miss twice.** One missed day holds the streak and shows a warning. Two in a row resets it.
- **Highlight.** One per day, worth 50 XP and 20 of the day's 100 points. **Laser** is the focus timer (15/25/50/90 min) and counts how often you leave the screen.
- **Bad habits.** Log every slip and every urge you resist. Each slip opens a short check-in: why you did it (at least one reason, from presets like *felt tired* or *easier than my planned task*, or your own words), how you felt beforehand, how strong the urge was, how you feel now, and what you should have been doing. It then suggests a next move for that reason and offers to win the day back with a 2-minute habit. Reasons, feelings and how often you felt worse afterwards are summarised for each bad habit and on the week view. Each bad habit shows today, this week vs last week, days clean, a 28-day strip, and for time-based ones the projected hours per year (after 3 tracked days). **Tempted?** opens a 90-second urge-surf with your identity statement and a 2-minute habit to do instead.
- **Daily score.** Habits 50 (2-minute counts 0.7), Highlight 20, planned tasks 15, focus 15 (60 minutes is full marks), minus up to 30 for slips.
- **XP and levels.** Habits, Highlight (50), tasks (10/20/30 by urgency), goals (15 daily to 600 yearly), focus, urges resisted (5, up to 10 a day), reflection (15) and a +10 bonus for beating yesterday's score. Ranks run from Starter to Legend.

The starter habits, tasks and goals are editable examples; tasks and goals marked "example" can be cleared in one tap from the Tasks page.
