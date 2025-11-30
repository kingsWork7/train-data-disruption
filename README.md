# 🚆 Train Disruption Data in Netherlands

An interactive visualization tool designed to help residents, commuters, experts, and newcomers understand patterns in Dutch train disruptions. By analyzing historical and real-time data, the project provides insights into the causes, routes, and train lines most affected, supporting better travel planning and smarter decisions about where to live.

---

## 📖 Overview

Train disruptions are a frequent challenge in the Netherlands, often causing professionals to miss work and students to miss school. For those newly relocating to the country or choosing where to live, understanding the scale and causes of these disruptions is essential.

This project aims to make that information accessible by visualizing disruption patterns across the country. It highlights:

* Common causes of train disruptions
* Frequent problem routes and train lines
* Geographic distribution of incidents

The final outcome is a clear and intuitive visualization tool that supports both personal commuting decisions and infrastructure planning.

---

## 🎯 Key Features

* **Interactive Map (Leaflet.js):** Displays Dutch railway stations and disruption markers.
* **Station Selection:** Choose a departure and arrival station to view relevant incidents.
* **Hover Insights:** Each bubble represents a disruption; hovering reveals the cause.
* **Data-Driven Visualization:** Uses data collected from *Rijden de Treinen* and *NS*.
* **Supports Urban & Transit Planning:** Provides meaningful insights for citizens, researchers, and policymakers.

---

## 🛠️ Tech Stack

* **HTML & CSS** — UI layout and styling
* **JavaScript** — Logic, data handling & map interactions
* **Leaflet.js** — Rendering the Netherlands map and visual markers
* **Rijden de Treinen / NS Data** — Source of disruption information
* **GitHub** — Version control & collaboration

---

## 🧭 How Users Interact

1. Select a **departure station** on the map.
2. Select an **arrival station**.
3. View the displayed **bubbles** representing disruptions.
4. Hover over a bubble to read details about its cause.

This workflow allows users to quickly understand patterns, helping them plan better commutes or select rental locations with lower disruption rates.

---

## 📁 Project Structure

```
root/
├── index.html
├── css/
│   └── styles.css
├── modules/
│   ├── day-data.mjs
│   ├── fetch.mjs
│   ├── render-causes.mjs
│   ├── render-control.mjs
│   ├── route-ranking.mjs
│   ├── script.mjs
│   └── station-coords.mjs
├── assets/
│   └── icons/ images/ data/
└── README.md
```

root/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── assets/
│   └── icons/ images/ data/
└── README.md

````

---

## 🚀 Getting Started
### Prerequisites
- A modern browser
- Optional: VS Code + Live Server extension

### Installation
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
````

### Run the Project

* Open `index.html` in a browser, or
* Use **Live Server** for auto-refresh:

  * Right‑click → **Open with Live Server**

* Via **Netlify** with this link : [train-disruption.netlify.app/](https://train-disruption.netlify.app/)

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request with a clear description of the improvements.

---

## 📄 License

MIT, Apache or GPL

---

## 👩‍💻 Author

**Kingsley and Donald**
Frontend Developers | UX/UI Design

---
