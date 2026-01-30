# Shuttle-Transit-System-
a simulation for a live shuttle system tracker
# 🚐 Soka Shuttle Live

A real-time, responsive shuttle tracking web application designed for the Soka University of America community. This tool helps students and faculty visualize the shuttle's current location, view route paths, and track ETAs for campus and local stops.

---

## ✨ Key Features

* **Real-Time Animation:** Smooth, high-frequency shuttle movement simulation along defined campus routes using Mapbox GL JS.
* **Dynamic ETAs:** Automated calculation of arrival times based on current system time and 15-minute interval scheduling.
* **Adaptive UI/UX:** * **Desktop:** Features a sleek, sidebar-integrated control panel with glassmorphism effects.
    * **Mobile:** Utilizes a bottom-sheet gesture-inspired interface for ergonomic thumb navigation.
* **Mapbox Integration:** High-performance vector maps with custom snapped-to-road route geometries via the Directions API.
* **Geolocation:** One-tap "Find My Location" feature to help users locate themselves relative to the nearest stop.

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **Mapping** | [Mapbox GL JS](https://www.mapbox.com/mapbox-gljs) |
| **Routing** | Mapbox Directions API |
| **Design** | Responsive CSS Media Queries & Flexbox |

---

## 🧪 UX Research & Roadmap

This project is built with a user-centric focus, incorporating principles from my ongoing UX Research studies.



### 1. Research Methodologies
To evolve this prototype, I plan to implement the following:
* **Contextual Inquiry:** Observing students at the Ikeda Library stop to understand real-world usage patterns.
* **Usability Testing:** Conducting "Think Aloud" sessions to verify if the mobile "bottom sheet" toggle is intuitive for first-time users.
* **Accessibility (A11y):** Auditing color contrast for "Soka Blue" against WCAG AA standards and adding ARIA labels for screen readers.

### 2. Future Iterations
* **Route Differentiation:** Color-coding multiple loops (Campus vs. Shopping) to reduce cognitive load.
* **Live Data Integration:** Transitioning from simulated intervals to live GPS-based GTFS-Realtime feeds.
* **Push Notifications:** Alerts when the shuttle is within 2 minutes of the user's "Favorite" stop.

---

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/soka-shuttle-live.git](https://github.com/your-username/soka-shuttle-live.git)
    ```
2.  **Add your Mapbox Token:**
    Replace the `mapboxgl.accessToken` in the script tag with your own token from the [Mapbox Dashboard](https://account.mapbox.com/).
3.  **Launch:**
    Simply open `index.html` in any modern web browser.

---

## 🗺️ Route Information

The application tracks a continuous loop encompassing:
* **Ikeda Library** (Main Campus Hub)
* **Town Center**
* **The Commons**
* **Walmart**
* **300 & 380 Residential Halls**
