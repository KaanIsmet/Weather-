# Weather App with GTK

## Description
This Weather App is a modern desktop application built using **GTK** and **C++**. It allows users to:
- Enter a location to fetch current weather information.
- View details such as temperature, humidity, and other weather conditions.
- Experience a clean and responsive user interface.

The app uses the **OpenWeatherMap API** (or similar) to retrieve weather data in real time.

---

## Features
- **City Search**: Enter a location to get weather information.
- **Weather Details**: Displays temperature, humidity, wind speed, etc.
- **Modern UI**: Clean and visually appealing interface styled with GTK's CSS-like theming system.
- **Expandable**: Add future features such as multi-day forecasts and weather icons.

---

## Prerequisites
### Install Dependencies
- **GTK** (Version 4 or later) and **gtkmm** (C++ bindings for GTK):
  - On Ubuntu/Debian:
    ```bash
    sudo apt install libgtkmm-4.0-dev
    ```
  - On Fedora:
    ```bash
    sudo dnf install gtkmm4-devel
    ```
  - On Windows/Mac: Follow the installation guide from the [GTK official site](https://www.gtk.org/download/).

- **C++ Compiler**:
  - GCC, Clang, or MSVC.

- **HTTP Client Library**:
  - Install **boost**:
    ```bash
    sudo apt update
    sudo apt install -y libboost-all-dev
    ```
---

## Installation
### Clone the Repository
```bash
git clone https://github.com/your-username/weather-app-gtk.git
cd weather-app-gtk
```

### Compile the Code
```bash
g++ weather_app.cpp -o weather_app `pkg-config --cflags --libs gtkmm-4.0`
./weather_app
```

---

## Usage
1. Launch the app.
2. Enter a city or location in the input box.
3. Press the **Fetch Weather** button to retrieve weather data.
4. View weather details displayed below the input box.

---

## File Structure
```plaintext
weather-app-gtk/
├── weather_app.cpp      # Main application code
├── style.css            # CSS-like file for styling
├── README.md            # Documentation
└── LICENSE              # License information
```

---

## Future Enhancements
- **5-Day Weather Forecast**: Add a detailed forecast section.
- **Weather Icons**: Integrate icons for different weather conditions.
- **Error Handling**: Handle API errors and invalid user inputs.
- **Deployment**: Package the app for Windows, Mac, and Linux distributions.

---

## License
This project is licensed under the Apache License. See the `LICENSE` file for details.

---

## Acknowledgements
- **GTK**: For providing a robust GUI framework.
- **OpenWeatherMap API**: For real-time weather data.
- **Boost**: For handling HTTP requests and JSON parsing.

---

## Contributions
Contributions are welcome! Please fork the repository and submit a pull request.

---

## Contact
For questions or suggestions, feel free to reach out:
- **Email**: [ismet.kaan.okul@gmail.com](mailto:ismet.kaan.okul@gmail.com)
- **GitHub**: [your-username](https://github.com/your-username)
