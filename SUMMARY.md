**Weather Dashboard** is a production-ready weather application built with Node.js that fetches real-time weather data from the Open-Meteo API.

## 🌟 Highlights

- **Real-time Data** - Current weather conditions and 7-day forecasts
- **Multi-City Support** - Display weather for multiple locations
- **Data Export** - Save data as JSON or CSV
- **Fully Tested** - Comprehensive test coverage
- **Production Ready** - CI/CD pipelines and deployment automation
- **Easy to Use** - Simple CLI interface with beautiful formatting

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/hassonshareef-png/Rundown.git
cd Rundown

# Install
npm install

# Run weather dashboard
npm run weather

# Weather for specific city
npm run weather:city "New York" 40.7128 -74.006
```

## 📊 Features

### Current Weather
- Temperature and "feels like"
- Humidity and wind speed
- Weather condition description
- Last update timestamp

### 7-Day Forecast
- High/low temperatures
- Weather conditions
- Precipitation probability
- Wind speeds

### Data Export
- JSON export
- CSV export
- File persistence

### CI/CD Pipeline
- Automated testing on Node 18 & 20
- ESLint code quality checks
- npm audit security scanning
- Automatic deployments

## 📁 Project Files

```
src/
├── index.js          # Main application entry point
├── index.test.js     # Application tests
├── weather.js        # Weather API integration
└── dashboard.js      # Dashboard display
```

## 🧪 Tests

```bash
npm test
```

## 📚 Full Documentation

See README.md for complete documentation.

## 🤝 Contributing

See CONTRIBUTING.md for contribution guidelines.

## 📄 License

MIT License - see LICENSE file

---

**Weather Dashboard** - Your go-to weather application! 🌤️
