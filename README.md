
# ⏱ CS Kettlebell EMOM Timer

A free, no-subscription EMOM (Every Minute On the Minute) timer built specifically for kettlebell workouts.

Built by **clarenceos** using **Claude AI as Developer and ChatGPT 5.2 as Architect**.

## 🔗 Live App

👉 **[Launch the timer](https://clarenceos.github.io/EMOM/)**

Add it to your home screen for a native app experience — no install required.

---

# 🚀 What’s New in Version 3

Version 3 is a major reliability and usability upgrade based on extensive real-world testing, especially on iPhone PWA. The timer is now significantly more stable, more readable, and more powerful.

### Major Improvements

* **Ultra-Reliable Wake Lock**
  Screen stays awake consistently throughout workouts, even across app switches and screen locks.

* **Hardened Audio System (iOS-optimized)**
  Interval beeps now recover automatically after backgrounding. No restart required.

* **Fully Accurate Wall-Clock Timing**
  Timer stays perfectly synced even if you lock your phone, switch apps, or return later.

* **100 Sets Support**
  Build extremely long EMOMs without hitting limits.

* **Duplicate Exercise Button**
  Quickly clone movements or complexes without rebuilding manually.

* **Configurable Start Countdown**
  Choose 3, 5, 10, or 15 seconds.

* **Improved Complex Display**
  Complex movements are now stacked vertically for better readability during workouts.

* **Larger Exercise Names**
  Designed to be readable from across the room.

* **Delete Complex Support**
  Safely delete saved complexes without breaking existing workouts or logs.

* **Completion Screen Stability Fixes**
  Workout completion now renders reliably on all devices.

* **Improved Progress Bar Visibility**
  Clearer round and set boundaries.

* **Improved Audio Timing Accuracy**
  Consistent Low-Low-High (3-2-1) countdown cues per interval.

These changes make Version 3 the most stable and production-ready version yet.

---

## Why This Exists

I got tired of paying $20/year for a countdown timer. I just love doing kettlebell EMOMs — it's simple, it's effective, and it doesn't need a subscription.

There are more powerful timers out there with broader scope. But if kettlebell EMOMs are your thing, this app is built exactly for that.

**No ads. No subscriptions. No tracking. Just you, your kettlebell, and a timer that works.**

---

# Features

## Workout Builder

* Exercise Library — 30 pre-loaded kettlebell exercises + add your own
* Favorites — Star frequently used exercises
* Duplicate Exercise Button — Quickly clone movements
* Complex Builder — Create multi-movement complexes
* Delete Complex Support — Safely remove unused complexes
* Drag Reordering — Rearrange exercises easily
* Sets — Repeat circuits up to 100 sets
* Save & Load Workouts
* Volume Tracking — reps × weight
* Copy Summary — One-tap sharing

---

## Timer Engine

* Ultra-Reliable Wake Lock
* Wall-Clock Accurate Timer
* Automatic Catch-Up After Screen Lock or App Switch
* Configurable Countdown (3, 5, 10, 15 seconds)
* Low-Low-High 3-2-1 Audio Cues
* Mute Toggle (persistent)
* Double-Tap Pause
* Skip / Previous Navigation

---

## Workout Experience

* Large, readable exercise names
* Clear complex movement display
* Improved progress bar visibility
* Dynamic color timer ring
* Completion summary screen
* Active Time vs Total Time tracking

---

## Logs and Stats

* Automatic workout logging
* Lifetime volume tracking
* Movement-specific statistics
* Stats dashboard (for reference only, not training prescription)

---

## Mobile Optimization

* PWA installable
* Works offline
* Optimized for iPhone and Android
* Swipe navigation
* Haptic feedback (Android)

---

## Privacy

* No ads
* No tracking
* No analytics
* No cloud sync
* All data stays on your device (localStorage only)

---

# How to Use

1. Select an exercise or complex
2. Set reps and weight
3. Tap **+** to add to workout
4. Repeat for all exercises
5. Set number of sets
6. Press **START**

---

# Add to Home Screen

Recommended for best experience.

**iPhone / iPad**
Safari → Share → Add to Home Screen

**Android**
Chrome → Menu → Add to Home Screen

---

# Tech

* Single HTML file architecture
* React 18 via CDN
* No build tools required
* Web Audio API
* Wake Lock API
* localStorage persistence
* Fully offline capable

---

# Version History

**v3.2.5 — Reliability Hardening Release**

* Wake Lock lifecycle stability improvements
* Audio recovery improvements for iOS PWA
* Prevent silent audio corruption after app switching
* Timer catch-up accuracy fixes
* Completion screen rendering fixes
* Improved audio lifecycle handling

---

**v3.2 — Major Usability and Stability Upgrade**

* Complex deletion support
* Duplicate exercise button
* Configurable countdown duration
* Increased set limit to 100
* Improved complex readability layout
* Larger exercise name display
* Progress bar visibility improvements
* Exercise display standardization

---

**v3.1 — Builder and Workflow Improvements**

* Complex builder refinements
* Improved UI responsiveness
* Storage and persistence improvements

---

**v2.1 — Usability and UX Upgrade**

* Favorites
* Copy summary
* Swipe gestures
* Double-tap pause
* Haptic feedback
* UI polish

---

**v2.0 — Logging and Statistics**

* Workout logs
* Stats dashboard
* Wake lock support
* Wall-clock timing
* Workout summary screen

---

**v1.0 — Initial Release**

* Core EMOM timer
* Exercise library
* Workout builder
* Volume tracking

---

Free and open source. Fork it, modify it, make it yours.

---


