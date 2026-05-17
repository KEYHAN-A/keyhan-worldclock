# World Clock — Multi-Zone

A modern, glassmorphism-styled multi-timezone world clock with live weather, holiday tracking, and Persian (Solar Hijri) / Gregorian calendars.

## ✨ Features

- 🕐 **Live clocks** for Maku (Iran), Istanbul (Turkey), Hamburg (Germany), and Washington D.C. (US)
- 🌤️ **Real-time weather** via Open-Meteo API (no key required)
- 🎉 **Holiday tracking** for all regions
- 📅 **Persian (Solar Hijri) calendar** with month navigation
- 📅 **Gregorian calendar** with month navigation
- 🌐 **Responsive design** — works on desktop, tablet, and mobile
- 📱 **PWA support** — install to home screen
- 🎨 **Glassmorphism UI** with animated gradient backgrounds

## 🌍 Live Demo

Visit **[time.keyhan.info](https://time.keyhan.info)**

## 🛠️ Tech Stack

- Single-file HTML/CSS/JS application
- Open-Meteo API for weather data
- Jalali calendar conversion (Solar Hijri)
- PWA manifest + service worker for offline support

## 🚀 Local Development

```bash
# Clone the repo
git clone https://github.com/KEYHAN-A/keyhan-worldclock.git
cd keyhan-worldclock

# Serve locally (any static server works)
npx serve .
```

## 📦 Deployment

1. Push to `main` branch
2. On server: `git pull origin main`
3. Copy `index.html` to the Nginx document root

## 📄 License

MIT
