# 🌱 Focus Flow

A tiny, single-file focus timer. Work in Pomodoro-style sprints, track your
tasks, and watch a little plant grow as you complete focus sessions.

## Features

- **Pomodoro timer** with Focus (25 min), Short break (5 min), and Long break (15 min) modes
- **Task list** — add what you're working on and mark the one you're focusing on
- **Growing plant** that advances through six stages as you finish focus sessions
- **Daily stats** — focus sessions, tasks done, and minutes focused
- **Saves your day** automatically in the browser (via `localStorage`), resetting each new day

## Usage

Open `index.html` in any modern web browser — that's it. There's no build step,
no dependencies, and no server required.

## Tips

- Type a task and press **Enter** (or click **+**) to add it.
- Click **focus this** on any task to make completed focus sessions count toward it.
- Each 🍅 next to a task marks one focus session spent on it.
- When a focus session ends you'll hear a short chime and the app rolls you into a break.
- **Reset today** clears the day's tasks, sessions, and plant so you can start fresh.

## Notes

- **Dark mode** is automatic — the app follows your system's light/dark preference.
- Your progress is stored **locally in your browser** and is private to that device;
  nothing is uploaded anywhere.
- Data is kept **per day** and resets automatically when a new day begins.

## Development

Everything lives in `index.html`: markup, styles, and logic are self-contained,
so you can edit it directly and refresh the page to see changes.
