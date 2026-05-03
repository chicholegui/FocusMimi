# Focus Mimi 🐱

Mimi is a cat. A studious one. And she's figured out something most people spend years trying to learn — if you want to actually get something done, you need to stop pretending you can do everything at once.

So I built this solution.

---

## What it does

The moment you leave the Focus Mimi tab, it takes a photo of you and sets off an alarm. No warnings. No "are you sure?" dialogs. Just immediate, cat-approved consequences.

While you're working, it tracks how long you've stayed focused and counts every time you slipped away. That's it. Simple by design.

---

## Features

- 📸 **Distraction detection** — tab visibility is monitored in real time; leave the tab and you get photographed
- 🚨 **Alarm trigger** — an alarm fires the instant a distraction is detected
- ⏱️ **Focus timer** — tracks your total focused time continuously
- 📊 **Distraction counter** — keeps a running count of how many times you've wandered off
- 🔒 **No fluff** — no habit streaks, no motivational quotes, no gamification. Just the work.

---

## Why it works

The concept is borrowed from something Mina takes seriously: **single-tasking**. There's a real cost to splitting your attention — context switching kills depth, and depth is where actual progress happens. This app doesn't block distractions. It just makes them uncomfortable enough that you stop reaching for them.

---

## How it works (technically)

Focus Mimi detects when the tab loses focus. On detection, it:

- Activates the device camera and captures a still frame
- Triggers an audio alarm
- Logs the distraction with a timestamp
- Resumes the focus timer when you return

Everything runs client-side. No data is sent anywhere. The photos stay in your browser session and disappear when you close the tab.

---

## Roadmap

There's more coming. Current priorities:

- [ ] Mobile optimization (touch-friendly UI, better camera handling on iOS/Android)
- [ ] Session history and distraction log export
- [ ] Custom alarm sounds
- [ ] Adjustable grace period before alarm fires

## License

MIT — do whatever you want with it. Mina asks only that you actually use it.
