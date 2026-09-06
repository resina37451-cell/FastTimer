# ⏱ Intermittent Fasting Tracker

A minimalist, offline-first app to control your intermittent fasting — no account, no cloud, no internet required.

## ✨ Features

- Log your **first** and **last meal** of the day with a single tap
- See your **current fasting time** updating live in real time
- Automatically detects which **protocol** you fit: 12:12 · 16:8 · 18:6 · 20:4
- Shows the **eating deadline** for each protocol with a progress bar and status badge
- **Timers tab**: countdown of your eating window for each protocol
- **History tab**: daily log with protocol achieved, meal times, and fasting duration
- All data saved locally on the device — works **100% offline**
- Clean dark interface optimized for mobile screens

## 📖 How to use

### Logging meals

1. Tap **🌅 First Meal** when you start eating
2. Tap **🌙 Last Meal** when you finish eating for the day
3. The app automatically calculates your fasting time and shows the matching protocols

### Window timers

1. Go to the **⏳ Timers** tab
2. Tap **Start Countdown** (or log your first meal in the Fasting tab — timers start automatically)
3. See how much time is left inside each protocol's eating window

### History

- Open the **📅 History** tab to see all logged days
- Each entry shows the date, protocol achieved, meal times, and total fasting duration
- Use **Clear all** to wipe the history whenever you want

## 🏗️ Interface

The app has three tabs:

**⏱ Fasting** — log meals, live fasting timer, and protocol cards showing the eating deadline for each protocol.

**⏳ Timers** — countdown timers showing how much time remains in the eating window for each protocol (12:12, 16:8, 18:6, and 20:4).

**📅 History** — list of all logged days with protocol achieved, meal times, and fasting duration.

## 💾 Data and persistence

All data is saved automatically in the device's `localStorage`. No account, no internet connection, and no external service is needed. Data persists between sessions and survives closing the app.

## 🛠️ Technology

Built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step required. Runs entirely on-device via a WebView wrapper.

## 📄 License

MIT — feel free to use, modify, and distribute.

## 🙌 Author

Made by resina37451. Feedback and contributions are welcome!
