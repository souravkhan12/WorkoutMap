# 🗺️ Workout Tracker with Leaflet.js

Welcome to the **Workout Tracker**! This project allows users to log their **running** and **cycling** workouts on an interactive map powered by **Leaflet.js**. You can easily switch between workout types, track your progress, and store the workout data for future reference.

## 🚀 Features

- **Interactive Map**: Powered by **Leaflet.js**, track and visualize your workout routes on a map.
- **Workout Types**: Switch between **Running** and **Cycling** workouts.
- **Local Storage**: Save and retrieve your workouts from the browser’s local storage.
- **Class-Based Structure**: Clean, modular code with **ES6 Classes**.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## 🏗️ Project Structure

The project is organized with a focus on clarity and modularity:

- **App Class**: Handles map initialization, event listeners, and user input.
- **Workout Class**: A base class that contains shared workout properties (distance, duration, etc.).
  - **Running Class**: Inherits from `Workout`, adds additional properties for running (cadence, pace).
  - **Cycling Class**: Inherits from `Workout`, adds properties specific to cycling (elevation, speed).

