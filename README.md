# Mapty // Workout Tracker 🏃‍♂️🚴‍♀️

A location-based web application that allows users to log and track their running and cycling workouts on an interactive map. This project was developed as a core part of the **Advanced JavaScript Course by Jonas Schmedtmann** to master complex DOM manipulation, asynchronous logic, and OOP architecture.

## 🚀 Live Demo
**[View Project Live]** -> (https://mapty-murex.vercel.app/)

---

## ✨ Features
* **Geolocation Integration:** Real-time tracking of the user's current position using the Browser Geolocation API.
* **Interactive Mapping:** Click-to-log functionality powered by the Leaflet.js library.
* **Dynamic Forms:** Context-aware input forms that change based on workout type (Running/Cycling).
* **Data Persistence:** Integrated Local Storage API to keep workout history safe across browser refreshes.
* **Smooth UX:** Automatic map panning to workout locations upon selection from the sidebar.

## 🛠️ Technical Stack
* **Language:** JavaScript (ES6+)
* **Mapping Library:** [Leaflet.js](https://leafletjs.com/)
* **Pattern:** Model-View-Controller (MVC) inspired architecture.
* **Programming Paradigm:** Object-Oriented Programming (OOP) using ES6 Classes and Private Class Fields.
* **CSS:** Modern Responsive Design.

## 🏗️ Technical Highlights
* **Class Inheritance:** Used a parent `Workout` class with specialized `Running` and `Cycling` subclasses to handle different metrics (Cadence vs. Elevation Gain).
* **Private Class Fields:** Implemented `#` private properties to encapsulate application logic and protect the internal state.
* **Event Handling:** Managed multi-level event delegation for list interactions and map markers.
* **API Integration:** Successfully handled external library integration and asynchronous coordinate fetching.

## 🎓 Project Context
This project was completed during **"The Complete JavaScript Course 2024: From Zero to Expert!"** taught by Jonas Schmedtmann on Udemy. It served as a deep-dive into how real-world JavaScript applications are architected using clean code principles.

