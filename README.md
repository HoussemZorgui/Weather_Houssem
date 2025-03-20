<!-- Improved compatibility of back to top link-->
<a name="readme-top"></a>
[![es](https://img.shields.io/badge/Idioma-Español-red.svg)](/README-ES.md)



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/JuanAntBuit/WeatherProject">
    <img src="images/logo.webp" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">WeatherProject</h3>

  <p align="center">
    WeatherProject is a Kotlin Android app that gathers data from the OpenWeatherMap API and showcases global weather information
    <br />
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#technologies-used">Technologies used</a></li>
        <li><a href="#images">Images</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#design">Design</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

### Features

* Real-time weather data
* 4-day forecast
* Search engine for worldwide locations
* Change of measurement system between Metric/Celsius, Imperial/Fahrenheit and Standard/Kelvin.
* GPS integration to easily locate the weather in your location
* English and Spanish support
* Save up to 3 locations for easy access to their information

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Technologies used

* **Kotlin**: Modern programming language for Android development known for concise and expressive syntax
  
* **Android SDK**: Software Development Kit that provides tools and APIs for building Android applications
  
* **MVVM architecture**: A design pattern that separates an app into three parts - Model, View, and ViewModel - making code more organized and maintaining a smooth user experience. It helps manage data, user interface, and business logic effectively
  
* **Shared Preferences**: Mechanism in Android for storing small amounts of data persistently, often used for app settings
  
* **ViewModel**: MVVM architecture component that holds UI-related data, surviving configuration changes, and lifecycle events
  
* **LiveData**: Architecture component that allows data observation for UI components, automatically updating when the underlying data changes
  
* **ViewBinding**: Library that generates binding classes for XML layouts, enabling direct interaction with views while improving type safety
  
* **Coroutines**: Kotlin library for managing asynchronous tasks more concisely and safely, simplifying multithreaded programming
  
* **Flows**: Kotlin reactive streams that handle asynchronous data streams with support for flow control and error handling
  
* **Retrofit**: Networking library for Android that simplifies HTTP requests and responses, often used for communicating with APIs
  
* **MPAndroidChart**: Powerful ibrary for creating various types of charts and graphs in Android applications
  
* **Glide**: Image loading library for efficient image loading and caching in Android apps
  
* **Algolia Search API Client**: Client library for integrating Algolia's search services into Android applications, enabling powerful search functionalities

* **Firebase Crashlytics**: A tool for real-time crash reporting that helps developers track and analyze app crashes.

* **Dagger Hilt**: A dependency injection framework for Android that simplifies dependency management and improves modularity, testability and maintainability of code.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Images

<img src="images/english/english_light.jpg" alt="Logo" width="800">
<img src="images/english/english_dark.jpg" alt="Logo" width="800">


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Android Studio.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/JuanAntBuit/WeatherProject.git
   ```
   
2. Create a local.properties file in the project root if it does not exist
   
4. Get a free OpenWeatherMap API Key at [https://home.openweathermap.org/users/sign_in](https://home.openweathermap.org/users/sign_in)
   
5. Enter your API key in `local.properties`
   ```kt
   OPENWEATHER_KEY=your_openweather_key
   ```
   
6. You will need to create a free account on <a href="https://www.algolia.com/es/">Algolia</a>. Then, create an application
   
7. Generate a search API key, save the ID of the app you have created, and then create an index under that app. You will need to save the index name to set up the search functionality in this app

8. Next, populate the index with the following <a href="https://drive.google.com/file/d/1ImLwmPhV83evkeQs1zu2iR8N6k7bQ-Je/view?usp=sharing">records</a>

9. Enter your Algolia API key, app id and index name in `local.properties`   
   ```kt
   ALGOLIA_KEY=your_algolia_key
   ALGOLIA_APP_ID=your_app_id
   ALGOLIA_INDEX_NAME=your_index_name
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- Testing

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Design -->
## Design

The design of the main screen is inspired by the [Weather App Freebie](https://www.uplabs.com/posts/weather-app-freebie) concept by [Raman Yv](https://www.uplabs.com/ramandesigns9).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GPL-3.0 license. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Juan Antonio Buitrago B. - houssemzorgui10@gmail.com

Linkedin: https://www.linkedin.com/in/engineer-houssem-zorgui

Project Link: [https://github.com/HoussemZorgui/Weather_Houssem](https://github.com/HoussemZorgui/Weather_Houssem)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-url]: https://github.com/HoussemZorgui/Weather_Houssem
[product-screenshot]: images/screenshot.png
