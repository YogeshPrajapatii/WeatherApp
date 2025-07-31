# WeatherApp 🌦️

A clean and functional weather forecasting app created as a practical exercise in mastering native Android development with Kotlin and Jetpack Compose.

## Project Goal

This project focuses on fetching and displaying location-based data from a real-world API. It demonstrates the use of modern Android development techniques to create a visually appealing and useful utility application.

## ✨ Features

* Fetches and displays current weather conditions for a given city.
* Shows key weather metrics like temperature, humidity, and wind speed.
* A beautiful, declarative UI built from scratch with Jetpack Compose.
* Asynchronously fetches data and updates the UI without blocking the main thread.

## 🛠️ Tech Stack & Key Concepts

* **Language:** [Kotlin](https://kotlinlang.org/)
* **UI Toolkit:** [Jetpack Compose](https://developer.android.com/jetpack/compose)
* **Architecture:** MVVM (Model-View-ViewModel)
* **Asynchronous Programming:** Kotlin Coroutines and `StateFlow`.
* **Networking:** [Ktor Client](https://ktor.io/docs/client-overview.html) to interact with the weather API.
* **State Management:** Managed within the `ViewModel` to ensure UI consistency.

## 📄 API Used

This app gets its data from the [OpenWeatherMap API](https://openweathermap.org/api). You will need your own API key to build and run the project.
