# Polther Project

## Introduction
Polther is a web-based Pollution + Weather monitoring platform that presents environmental information through a clean, responsive, and interactive frontend. The name “Polther” is derived
from POL (Pollution) and THER (Weather), reflecting the system’s dual focus. The project aims to simplify how users access environmental data by combining pollution indicators and weather
conditions in one easily understandable interface.

## Problem Statement
Users often rely on multiple apps or websites to check pollution levels and weather updates, which can be inconvenient. Many dashboards are complex or cluttered. There is a strong need for a
unified, lightweight, and visually clear dashboard that shows AQI, temperature, humidity, windspeed, and pollution severity instantly and efficiently.

## Objectives
- To design a responsive and user-friendly web interface for pollution and weather monitoring.
- To display AQI, weather parameters, and environmental indicators.
- To implement modular HTML, CSS, and JavaScript code for future backend/API integration.
- To provide pollution severity visualization using colors, icons, and clean UI cards.
- To support future IoT or API-based real-time data integration.

## System Overview
- index.html: Main dashboard displaying pollution & weather info.
- overall.html: Global pollution overview.
- ind.html: India-focused environment data view.
- JavaScript files (script.js, overa.js) manage UI interaction.
- CSS files (style.css, over.css, etc.) create the modern responsive design.
The current version uses demo/static data but is structured for real-time API connectivity later.

## Methodology
Frontend Development:
- HTML5 used for structure.
- CSS3 used for layout, colors, transitions, and responsiveness.
- JavaScript used for page interaction and dynamic content handling.
Data Flow:
- Static demo data displayed for AQI and weather.
- Code prepared for future API requests.
Future Integration:
- Real AQI and weather data from OpenWeatherMap, IQAir, or government APIs.
- IoT sensors like MQ135, DHT11 integrated via a backend (Node.js, Python Flask).

## Features
- Pollution dashboard with color-coded AQI levels.
- Multi-page structure: Global, India-specific, and homepage view.
- Weather parameters: temperature, humidity, wind.
- Smooth UI transitions and responsive layout.
- Lightweight, fast-loading frontend.

## Applications
- Environmental awareness platforms.
- Smart city dashboards.
- IoT-based pollution monitoring systems.
- Weather and AQI display panels.
- Public health advisory systems.

## Future Enhancements
- Full API-based real-time AQI & weather data.
- Machine learning-based pollution forecasting.
- User location auto-detection.
- Historical data graphs and analytics.
- Mobile app version using React Native or Flutter.

## Conclusion
Polther successfully demonstrates a clean and user-friendly pollution and weather monitoring interface. Although it currently operates using static data, its modular architecture makes it highly scalable for real-world integration with APIs and IoT sensors. The project highlights strong frontend development skills and serves as a solid foundation for further expansion into a complete
environmental monitoring platform.
