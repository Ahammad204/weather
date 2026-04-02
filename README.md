# 🌤️ Weather App

A modern, responsive weather application that provides real-time weather information for any city in the world. Built with vanilla JavaScript, HTML, and CSS using the OpenWeatherMap API.

**Live Demo:** [https://ahammad204.github.io/weather/](https://ahammad204.github.io/weather/)

---

## ✨ Features

- 🔍 **City Search** - Search weather information for any city in the world
- 🌡️ **Real-time Temperature** - Get current temperature in Celsius
- 💧 **Humidity Information** - View current humidity levels
- 💨 **Wind Speed** - Track wind speed in km/h
- 🎨 **Dynamic Weather Icons** - Automatic icons based on weather conditions
- ✅ **Error Handling** - User-friendly error messages for invalid city names
- 📱 **Responsive Design** - Works seamlessly on all device sizes
- 🎯 **Beautiful UI** - Modern gradient background with smooth animations

---

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **API:** OpenWeatherMap API
- **Design:** Responsive and mobile-first approach
- **Font:** Poppins (Google Fonts)

---

## 📋 Supported Weather Conditions

The app displays different icons for various weather conditions:
- ☁️ Clouds
- ☀️ Clear
- 🌧️ Rain
- 💧 Drizzle
- 🌫️ Mist

---

## 🚀 How to Use

1. Visit the [live demo](https://ahammad204.github.io/weather/)
2. Enter any city name in the search bar
3. Click the search button
4. View the current weather information including:
   - Temperature
   - Humidity
   - Wind Speed
   - Dynamic weather icon

---

## 💻 Installation & Setup

### Prerequisites
- A modern web browser
- No additional installations required!

### Running Locally

1. Clone the repository
   ```bash
   git clone https://github.com/ahammad204/weather.git
   cd weather
   ```

2. Open `index.html` in your web browser or use a local server
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   http-server
   ```

3. Navigate to `http://localhost:8000` and start checking the weather!

---

## 📁 Project Structure

```
weather/
├── index.html          # Main HTML file with embedded JavaScript
├── style.css           # Styling for the weather app
├── images/             # Weather icons and UI images
│   ├── clear.png
│   ├── clouds.png
│   ├── cloudy.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   ├── snow.png
│   └── wind.png
└── README.md           # This file
```

---

## 🔌 API Integration

The app uses the **OpenWeatherMap API** to fetch real-time weather data.

**API Endpoint:**
```
https://api.openweathermap.org/data/2.5/weather?units=metric&q={city_name}&appid={api_key}
```

**Response Data Used:**
- `data.name` - City name
- `data.main.temp` - Temperature in Celsius
- `data.main.humidity` - Humidity percentage
- `data.wind.speed` - Wind speed in km/h
- `data.weather[0].main` - Weather condition

---

## 🎨 Design Features

- **Color Scheme:** Beautiful gradient (from #00feba to #5b548a)
- **Layout:** Centered card-based design with max-width of 470px
- **Typography:** Poppins font for modern aesthetics
- **Responsive:** 90% width with proper scaling on smaller devices
- **Smooth UX:** Clear error messages and loading states

---

## 📝 Code Highlights

### JavaScript Functionality
- Asynchronous API calls using `fetch()`
- Dynamic DOM manipulation
- Event listeners for user interactions
- Real-time error handling with user feedback
- Weather-based icon switching

### CSS Features
- Flexbox layout for responsive design
- Gradient backgrounds
- Border-radius for modern appearance
- Smooth transitions and hover effects
- Cross-browser compatibility

---

## ⚙️ Customization

### Change the Default City
Edit the default city in `index.html`:
```javascript
checkweather("London"); // Replace with your preferred city
```

### Modify API Key
To use your own weather API key, replace the existing key in the script section of `index.html`.

### Customize Colors
Update the gradient in `style.css`:
```css
background: linear-gradient(135deg, #your_color_1, #your_color_2);
```

---

## 🐛 Known Limitations

- Requires an active internet connection
- Limited to 60 API calls per minute (free OpenWeatherMap tier)
- Shows weather in Celsius only

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork this project and submit pull requests.

---

## 📄 License

This project is open source and available under the MIT License.

---

## 👨‍💻 Author

**Ahammad**
- GitHub: [ahammad204](https://github.com/ahammad204)
- Project Link: [Weather App](https://github.com/ahammad204/weather)

---

## 🙏 Acknowledgments

- OpenWeatherMap for their amazing API
- Icons and assets used in the app
- The open-source community for inspiration

---

## 📞 Support

If you encounter any issues or have suggestions, please open an issue on GitHub or reach out to the author.

---

**Built with ❤️ by Ahammad**
