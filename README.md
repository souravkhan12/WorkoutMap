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

## 🖥️ Installation

To run the project locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/workout-tracker.md
    ```

2. **Navigate to the project directory**:
    ```bash
    cd workout-tracker.md
    ```

3. **Open the app**:  
   Simply open the `index.html` file in your browser.

---

## 📦 Technologies Used

- **JavaScript (ES6)** for core functionality
- **Leaflet.js** for map rendering
- **HTML5 & CSS3** for layout and design
- **localStorage** API for persisting data in the browser


## 🔧 Usage

- **Add a Workout**: Click on the map to set a location, fill in the workout details (distance, duration, etc.), and select the type (running or cycling).
- **View Workouts**: Workouts will appear as markers on the map and as a list on the side panel.
- **Switch Workout Type**: Select either **running** or **cycling** from the form, and the fields will adjust accordingly.
- **Persistent Data**: All workout data is stored using `localStorage`, so the workouts will remain even after refreshing the page.
