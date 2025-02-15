# Mapty-OOP

## Description

Mapty is a web application that allows users to log and visualize their running and cycling workouts on an interactive map. The app leverages the browser's geolocation API and local storage to provide a seamless and persistent experience. The application is designed with a focus on Object-Oriented Programming (OOP) principles in JavaScript.


## Features

- Track running and cycling workouts with distance, duration, and other relevant details.

- Automatically calculate pace (for running) and speed (for cycling).

- Store workout history in the browser's local storage.

- Display workouts on an interactive map using Leaflet.js.

- View workout details and move to a specific workout location on the map.

- Toggle between different workout types dynamically.


## Technologies used

- **JavaScript (ES6+):** Core language for app logic.

- **Leaflet.js:** Interactive map rendering.

- **Geolocation API:** Fetch user's current location.

- **Local Storage API:** Persist workouts across page reloads.

- **HTML & CSS:** Structuring and styling the user interface.


## Usage

1. Allow location access when prompted.

2. Click on the map to add a new workout.

3. Fill in the details (type, distance, duration, etc.).

4. Submit the form to save and visualize the workout.

5. Click on a workout entry to move to its location on the map.


## Code structure

The application follows an object-oriented approach with the following classes:

- Workout: Base class for workout properties.

- Running: Extends Workout and calculates pace.

- Cycling: Extends Workout and calculates speed.

- App: Manages the application flow, map interactions, and local storage.
