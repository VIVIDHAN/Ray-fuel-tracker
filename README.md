# RayTracker: Smart Fuel & Mileage Dashboard

<p align="center">
  <img src="screenshot.png" alt="RayTracker App Screenshot" width="300">
</p>

A sleek, mobile-first web app for tracking vehicle fuel consumption, logging trips, and calculating real-time mileage. Features an interactive fluid tank UI, offline local storage, and detailed data charts.

## 📱 Features
- **Mobile-First Design:** Fluid, app-like experience with bottom navigation, animations, and iOS-safe notch areas.
- **Realistic Tank UI:** Glassmorphic animated fuel tank that visualizes current capacity and changes color dynamically.
- **Trip Recorder:** Start and end specific journeys to automatically calculate distance, fuel consumed, and trip cost.
- **Deep Analytics:** Tracks total distance, total petrol added, total amount spent, and gives a realistic mileage calculation.
- **Interactive Charts:** Visualizes mileage trends and distance progress using zero-dependency HTML5 Canvas.
- **Smart Data Entry:** Automatically calculates liters added when you input petrol rate and total amount paid. Triggers iOS decimal numpads for fast data entry.
- **100% Offline:** All data is safely stored in your device's `localStorage`. No accounts, no servers, zero latency.

## 🚀 How to Use
1. Download the `yamaha-ray-fuel-tracker-v3.html` file.
2. Open it in any modern mobile browser (Safari, Chrome).
3. **Pro-tip for iPhone:** Tap the Share button in Safari and select **"Add to Home Screen"** to use it as a fullscreen standalone app!
4. Complete the one-time initial setup with your current odometer and estimated mileage.
5. Log your regular rides or refills, and watch your dashboard update!

## 🛠 Tech Stack
- **HTML5:** Pure semantic markup.
- **CSS3:** Custom properties, CSS grid, flexbox, glassmorphism, keyframe animations.
- **JavaScript (ES6):** No frameworks, no external libraries. Pure vanilla JS for extreme speed and portability.
- **Fonts & Icons:** Google Material Icons Round, Inter, and Rubik Distressed.

## 🔒 Privacy
This app operates 100% client-side. Your fuel logs, travel distances, and expenses never leave your device.
