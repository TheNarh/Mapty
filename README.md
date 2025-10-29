# Mapty
# 🗺️ Mapty – Location-Based Workout Tracker

Mapty is a **location-aware fitness tracking app** that lets users log their **running and cycling workouts** on an interactive map.  
Built using **modern JavaScript (ES6+), Object-Oriented Programming, and the Leaflet library**, it demonstrates clean architecture, state management, and real-world geolocation logic.

---

## 🚀 Live Demo
🔗 [View Live Project](https://mapty-lud.vercel.app/) 

---

## 🧭 Features

✅ **Track Workouts in Real Time**  
Use your current geolocation to log **running** or **cycling** workouts directly on the map.

✅ **Interactive Map Integration**  
Built with **Leaflet.js**, each workout creates a **marker popup** showing key stats.

✅ **Dynamic Workout List**  
All workouts appear in a scrollable list where you can **edit or delete** them instantly.

✅ **Persistent Local Storage**  
Your workouts remain available even after reloading the page — no backend required.

✅ **Data Visualization Ready**  
Each entry is tied to coordinates, making the app easily extendable to analytics or heatmaps.

---

## 🧠 Technical Highlights

- Built entirely with **Vanilla JavaScript (ES6+)** — no frameworks.
- Applied **OOP design** with class inheritance (`Workout`, `Running`, `Cycling`).
- Implemented **private fields** for encapsulation and data integrity.
- Used **Geolocation API** to fetch user position asynchronously.
- Rendered map layers and markers using **Leaflet.js**.
- Managed application state and UI updates with **event delegation**.
- Persisted data using **LocalStorage API** (JSON serialization).
- Includes **edit and delete functionality** synced with the map and UI.

---

🧩 Flow Logic
<img width="1024" height="1536" alt="mapty" src="https://github.com/user-attachments/assets/e5a381cb-45f7-4177-93ce-3f57f38aa1d8" />

🧰 Installation & Usage

Clone this repository

git clone https://github.com/TheNarh/Mapty.git
cd Mapty


Open the app
Simply open index.html in your browser, and allow location access.

🧑‍💻 What I Learned

Through Mapty, I deepened my understanding of:

Asynchronous JavaScript and browser APIs.

Modular OOP design and private class fields.

DOM manipulation and event-driven programming.

Data persistence using browser storage.

Clean UI and user interaction design.

🚧 Future Improvements

🌐 Add backend with Node.js + MongoDB for user accounts and cloud storage.

📊 Add Chart.js integration for performance analytics.

🧭 Implement a search/filter feature for workouts.

📱 Improve responsive design for mobile users.

🧠 Inspiration

This project was inspired by real-world fitness tracking tools like Strava and Nike Run Club, built as part of my growth in mastering front-end architecture and geolocation-based app logic.


