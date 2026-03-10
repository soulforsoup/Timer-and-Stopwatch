# Timer App

## Description
A beautiful, highly fluid, and responsive single-file web timer application built with Alpine.js and Tailwind CSS. It features both a stopwatch and a countdown mode, complete with milliseconds display, dark and light themes, and a minimal design optimized for ultra-large typographic scales. The entire application runs entirely in the browser with a zero-build architecture.

## Features
- **Dual Modes:** Includes both Stopwatch and Countdown modes.
- **Fluid Typography:** Scales seamlessly across different screen sizes and allows manual scaling factor adjustments.
- **Dark and Light Themes:** Toggle between themes, with ambient glow effects in dark mode and system preference detection.
- **Tabular Figures:** Implements `tabular-nums` so numbers remain static in width, preventing layout jitter as digits change.
- **State Persistence:** Automatically saves your preferences (theme, mode, sound, scale, and duration) using `localStorage`.
- **Audio Alerts:** Uses native Web Audio API to play an alarm when the countdown finishes.
- **Fullscreen Support:** Enter distraction-free mode to utilize the entire screen.
- **Keyboard Shortcuts:**
  - `Space`: Play or pause the timer.
  - `R`: Reset the timer.
  - `F`: Toggle fullscreen mode.

## Technologies Used
- HTML5 / CSS3 / JavaScript
- Tailwind CSS (via CDN)
- Alpine.js (via CDN)
- Google Fonts (Inter)

## How to Use
1. Clone or download the repository.
2. Open `timer.html` directly in any modern web browser.
3. Use the on-screen controls or keyboard shortcuts to operate the timer.
4. Adjust your preferences such as milliseconds display, sound alerts, and typography scale directly in the app.

## Customization
Since the application relies on Alpine.js and Tailwind CSS via CDNs, you can easily tweak the design by editing the `tailwind.config` script block or modifying the custom CSS inside the `<style>` section of the `timer.html` file.
​
