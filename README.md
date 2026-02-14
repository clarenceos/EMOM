# ⏱ CS Kettlebell EMOM Timer

A free, no-subscription EMOM (Every Minute On the Minute) timer built specifically for kettlebell workouts.

Built by **clarenceos** using **Claude AI**.

## 🔗 Live App

👉 **[Launch the timer](https://clarenceos.github.io/EMOM/)**

Add it to your home screen for a native app experience — no install required.

## Why This Exists

I got tired of paying $20/year for a countdown timer. I just love doing kettlebell EMOMs — it's simple, it's effective, and it doesn't need a subscription.

There are more powerful timers out there with broader scope. But if kettlebell EMOMs are your thing, this app is built exactly for that.

**No ads. No subscriptions. No tracking. Just you, your kettlebell, and a timer that works.**

## Features

- **Exercise Library** — 30 pre-loaded kettlebell exercises + add your own custom exercises
- **Favorites** — Star your go-to exercises for quick access
- **Workout Builder** — Set reps, weight, and build your round list with drag reordering
- **Sets** — Repeat your circuit 1–10 times (5 exercises × 4 sets = 20 rounds)
- **Volume Tracking** — Total volume (reps × kg) with intensity meter
- **Save & Load** — Save favorite workouts and reload them anytime
- **Dynamic Timer Ring** — Color-coded countdown (green → yellow → orange → red)
- **3-2-1 Countdown** — Gives you time to get to your spot before the workout starts
- **Double-Tap Pause** — Tap the timer ring to quickly pause or resume
- **Skip / Previous** — Jump rounds without affecting elapsed time
- **Wake Lock** — Screen stays on during your workout
- **Wall-Clock Timer** — Timer stays accurate even if you switch apps or lock your phone
- **Workout Logs** — Every session auto-logged with date, exercises, volume, and elapsed time
- **Stats Dashboard** — Lifetime volume and per-movement stats (sortable by reps or volume)
- **Mute Toggle** — Silence beeps when needed (persists between sessions)
- **Copy Summary** — One-tap copy of workout results for sharing
- **Haptic Feedback** — Vibration on round transitions and scroll pickers (Android)
- **Swipe Navigation** — Swipe from left edge to go back on menu screens
- **Works Offline** — Single HTML file, no server needed

## How to Use

1. Select an exercise from the dropdown (star your favorites for quick access)
2. Set reps and weight with the scroll pickers
3. Tap **+** to add it to your round list
4. Repeat for each exercise in your circuit
5. Adjust sets if you want to repeat the circuit
6. Hit **START** and get after it

## Add to Home Screen

For the best experience, add the app to your home screen:

- **iPhone/iPad**: Open in Safari → Share button → *Add to Home Screen*
- **Android**: Open in Chrome → Three dots → *Add to Home Screen*

## Tech

- Single HTML file — no build tools, no frameworks to install
- React 18 loaded from CDN
- All data stored in localStorage (stays on your device)
- Wake Lock API for screen-on during workouts
- Wall-clock timing for accuracy across app switches

## Version History

- **v1.0** — Core timer with exercise library, save/load, volume tracking, dynamic ring
- **v2.0** — Logs, stats, menu system, wake lock, wall-clock timer, 3-2-1 countdown, mute toggle, workout summary
- **v2.1** — Favorites, copy summary, swipe gestures, double-tap pause, haptic feedback, bug fixes, UI polish

---

*Free and open source. Fork it, modify it, make it yours.*
