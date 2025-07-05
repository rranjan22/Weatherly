# ⛅ Weatherly

**Weatherly** is a fast and simple weather app built with React and Vite. It uses the OpenWeatherMap API to fetch real-time weather data like temperature, humidity, wind speed, and displays relevant weather icons dynamically based on conditions.

---

## 🖼 Screenshot

>![image](https://github.com/user-attachments/assets/4f8d5e4c-9dc2-4065-8a03-217b8f96c112)


![Weatherly Preview](./public/clouds-and-sun.png)

---

## 🌐 Live Demo

> 🚀 [Visit Weatherly on Vercel](https://weatherly-red.vercel.app)

---

## ⚙️ Features

- 🔍 Search by city name
- 🌤 Dynamic weather icons
- 🌡 Displays temperature, humidity, and wind speed
- ⚡ Fast build with Vite
- 🌎 Clean and responsive UI

---

## 🧩 Tech Stack

| Tech       | Description                    |
|------------|--------------------------------|
| React      | Frontend UI framework          |
| Vite       | Lightning-fast dev server      |
| CSS        | Custom styling                 |
| OpenWeatherMap API | Real-time weather data |

---

## 📁 Project Structure

```text
Weatherly/
├── public/
│   └── clouds-and-sun.png          # Placeholder image for preview
│
├── src/
│   ├── assets/
│   │   ├── clear.png
│   │   ├── cloud.png
│   │   ├── drizzle.png
│   │   ├── humidity.png
│   │   ├── rain.png
│   │   ├── search.png
│   │   ├── snow.png
│   │   └── wind.png
│   │
│   ├── components/
│   │   ├── Weather.jsx             # Main weather component
│   │   └── Weather.css             # Component styling
│   │
│   ├── App.jsx                     # App wrapper
│   ├── index.css                   # Global styles
│   └── main.jsx                    # Entry point
│
├── .env                            # Environment variable (API key)
├── .gitignore
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── vite.config.js
└── README.md                       # This file


