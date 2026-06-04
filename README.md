<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0EA5E9,50:38BDF8,100:7DD3FC&height=220&section=header&text=Weather%20App&fontSize=72&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Real-Time%20Weather%20%7C%20OpenWeatherMap%20API%20%E2%9B%85&descAlignY=58&descAlign=50" width="100%"/>

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap_API-FF6B35?style=for-the-badge&logo=openweathermap&logoColor=white)](https://openweathermap.org/api)

<br/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Search+any+city+for+live+weather+%F0%9F%8C%8D;Temperature+%2B+humidity+%2B+wind+speed+%F0%9F%8C%A1%EF%B8%8F;Dynamic+weather+icons+%E2%98%81%EF%B8%8F+%F0%9F%8C%A7%EF%B8%8F+%E2%98%80%EF%B8%8F;OpenWeatherMap+API+integration+%F0%9F%94%8C;Clean+responsive+card+UI+%E2%9C%A8" alt="Typing SVG" />
</p>

<br/>

<blockquote>
A clean, responsive weather app that fetches <strong>real-time weather data</strong> for any city using the OpenWeatherMap API. Displays temperature, humidity, wind speed, and dynamically swaps weather icons based on current conditions.
</blockquote>

<br/>

</div>

---

## 🌟 Features

<table>
  <tr>
    <td align="center" width="220">🌡️<br/><strong>Live Temperature</strong><br/><sub>Real-time temperature in °C for any searched city</sub></td>
    <td align="center" width="220">💧<br/><strong>Humidity</strong><br/><sub>Current humidity percentage fetched from the API</sub></td>
    <td align="center" width="220">💨<br/><strong>Wind Speed</strong><br/><sub>Live wind speed in km/h for the searched location</sub></td>
  </tr>
  <tr>
    <td align="center" width="220">🖼️<br/><strong>Dynamic Icons</strong><br/><sub>Weather icon changes based on condition — clear, clouds, rain, drizzle, mist</sub></td>
    <td align="center" width="220">❌<br/><strong>Error Handling</strong><br/><sub>Shows a friendly message for invalid or misspelled city names</sub></td>
    <td align="center" width="220">📱<br/><strong>Responsive UI</strong><br/><sub>Clean card layout that works on all screen sizes</sub></td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

| Technology | Role |
|-----------|------|
| **HTML5** | App structure & layout |
| **CSS3** | Card styling & responsive design |
| **Vanilla JavaScript** | API calls, DOM updates, event handling |
| **OpenWeatherMap API** | Real-time weather data source |

</div>

---

## ☁️ Weather Conditions Supported

| Condition | Icon |
|-----------|------|
| ☀️ Clear | `clear.png` |
| ☁️ Clouds | `clouds.png` |
| 🌧️ Rain | `rain.png` |
| 🌦️ Drizzle | `drizzle.png` |
| 🌫️ Mist | `mist.png` |

---

## 🚀 Getting Started

### 1. Get a free API key

Sign up at [openweathermap.org](https://openweathermap.org/api) → go to **My API Keys** → copy your key.

### 2. Clone & configure

```bash
git clone https://github.com/Tanyaagarg/weather_app.git
cd weather_app
```

Open `index.html` and replace the API placeholders:

```javascript
const apiKey = "YOUR_API_KEY_HERE";
const apiUrl = "https://api.openweathermap.org/data/2.5/weather?units=metric&q=";
```

### 3. Run

```bash
# Open directly in browser — no build step needed
open index.html
```

---

## 📁 Project Structure

```
weather_app/
├── index.html        # App structure + JavaScript logic
├── style.css         # Card UI styling
└── images/
    ├── search.png    # Search button icon
    ├── clear.png     # Sunny weather icon
    ├── clouds.png    # Cloudy weather icon
    ├── rain.png      # Rainy weather icon
    ├── drizzle.png   # Drizzle weather icon
    ├── mist.png      # Mist weather icon
    ├── humidity.png  # Humidity indicator icon
    └── wind.png      # Wind speed indicator icon
```

---

## 🔌 API Reference

This app uses the **OpenWeatherMap Current Weather API**:

```
GET https://api.openweathermap.org/data/2.5/weather?units=metric&q={city}&appid={API_KEY}
```

**Key response fields used:**

| Field | Description |
|-------|-------------|
| `data.name` | City name |
| `data.main.temp` | Temperature in °C |
| `data.main.humidity` | Humidity % |
| `data.wind.speed` | Wind speed km/h |
| `data.weather[0].main` | Weather condition string |

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/add-forecast`
3. Commit your changes: `git commit -m 'Add 5-day forecast'`
4. Push: `git push origin feature/add-forecast`
5. Open a Pull Request

---


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0EA5E9,50:38BDF8,100:7DD3FC&height=120&section=footer" width="100%"/>

<sub>Built with ☁️ OpenWeatherMap API · HTML · CSS · JavaScript</sub>

</div>
