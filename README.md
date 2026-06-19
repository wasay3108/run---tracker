# run---tracker
A GPS-based running tracker PWA — track runs in real-time, view history with stats and charts, calculate BMI. Built with vanilla JS.
# RunTracker

A lightweight, installable running tracker built as a Progressive Web App — no backend, no frameworks, just HTML, CSS and JavaScript.

## Features

- **Live GPS tracking** — distance, time, and speed tracked in real-time using the Geolocation API
- **Pause / Resume / End** controls for full run management
- **Step counting & calorie estimate** using device motion sensors
- **Run history** — past runs saved locally with date, distance, time and speed
- **Progress chart** — visualizes distance over time
- **Speed per 100m segments** — post-run breakdown of pace consistency
- **BMI Calculator** — supports both metric (kg/cm) and imperial (lb/ft+in) units, with a visual gauge
- **Installable PWA** — add to home screen on mobile, works offline, runs full-screen like a native app

## Tech Stack

- Vanilla JavaScript (no frameworks)
- HTML5 Geolocation API
- DeviceMotion API for step detection
- Chart.js for data visualization
- LocalStorage for persistence
- Service Worker for offline support

## Live Demo

https://lustrous-heliotrope-ec4216.netlify.app/

## What I Learned

Building this taught me the real-world challenges of GPS-based apps — handling location accuracy, filtering GPS jitter/spikes, smoothing noisy sensor data, and the gap between "working in theory" and "working reliably on a real device."

## Run It Locally

Just open `index.html` in any browser. No build step, no dependencies to install.
