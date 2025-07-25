# 🌦 Weatherly

**Weatherly** is a beautifully designed iOS weather app built with Swift that provides real-time weather updates, forecasts, and intuitive UI to help you plan your day better — rain or shine.

## 📱 Features

- 🧭 Current weather conditions (temperature, humidity, wind speed, etc.)
- 🌤 7-day weather forecast
- 🌍 Location-based weather using GPS
- 🔍 Search by city name
- 🖼 Dynamic backgrounds based on weather conditions
- 🌙 Light & dark mode support
- ⚡️ Fast and responsive UI built with Swift

## 🛠 Built With

- **Swift**
- **UIKit / SwiftUI** *(Choose depending on what you used)*
- **CoreLocation** for GPS-based location tracking
- **OpenWeatherMap API** *(or any other API you used)*
- **URLSession** for API calls
- **MVVM Architecture** *(if used)*

## 📸 Screenshots

*(Add a few screenshots here once available)*

## 🚀 Getting Started

To run the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/weatherly.git
    ```

2. Open `Weatherly.xcodeproj` or `Weatherly.xcworkspace` in Xcode.

3. Make sure you have your API key set in the appropriate file:
    ```swift
    let apiKey = "YOUR_API_KEY"
    ```

4. Build and run on a simulator or your iPhone.

## 🔐 API Key

You will need an API key from your weather data provider (e.g., [OpenWeatherMap](https://openweathermap.org/api)):

- Sign up and get your key.
- Add it to the designated file in the codebase (e.g., `APIService.swift` or `.env` file if you're using one).

## 🧪 Testing

Basic tests for networking and data models can be run using the Xcode testing framework.

## 📄 License

MIT License. See [LICENSE](LICENSE) for more information.

## 🙌 Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/)
- [Apple Developer Documentation](https://developer.apple.com/documentation/)
- [Unsplash](https://unsplash.com/) *(if you use dynamic weather images)*

---

Made with ❤️ by Rishi
