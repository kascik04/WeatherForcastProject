# WeatherForcastProject

## Source Code
[Download the Source Code](https://drive.google.com/file/d/1DwqCol5334UTzWne0p6hK4BXc4Fm-s_I/view?usp=sharing)

---

## Introduction
The Weather App allows users to enter a city name and view weather information. The app uses the OpenWeather API to fetch weather data and is divided into three main components:

- **Form 1:** Displays general city information.
- **Form 2:** Provides a 5-day weather forecast.
- **Form 3:** Shows detailed hourly weather for a selected day within the 5-day forecast.

## System Requirements
- **Programming Language:** C#
- **IDE:** Visual Studio
- **Framework:** .NET Core or .NET Framework
- **API:** OpenWeather API
- **UI Tools:** Windows Forms
- **Internet Connection:** Required for fetching weather data

## Features

### Form 1:
- Displays city and country details such as temperature, weather conditions, sunrise/sunset times, humidity, wind speed, and air pressure.
- Customization options: Language selection, country selection, city selection, light/dark mode toggle, and a 5-day forecast option.
- **Controls:**
  - **ComboBox:** For selecting language, country, and city.
  - **Buttons:** For toggling light/dark mode and switching to the 5-day forecast.
  - **Labels:** Display temperature, humidity, and weather conditions.

### Form 2:
- Displays a 5-day weather forecast including temperature and weather conditions.
- **Controls:**
  - **Labels:** Display temperature and weather conditions.
  - **Buttons:** Show detailed weather for a selected day within the forecast.

### Form 3:
- Displays hourly weather details for a selected day within the 5-day forecast.
- **Controls:**
  - **Labels:** Display temperature and weather conditions.

## System Architecture
### UI Layer:
- **ComboBox:** Allows users to select the app's display language, country, and city.
- **PictureBox:** Displays images corresponding to the current weather condition.
- **Buttons:**
  - Toggle between light and dark modes.
  - Exit the application with confirmation.
  - Display detailed weather for a selected day.
- **Labels:** Display temperature, humidity, air pressure, weather conditions, sunrise, and sunset times.

### Logic Layer:
- **API Requests:** Uses the "http" class to send requests to OpenWeather API to fetch weather data based on location and time.
- **Data Parsing:** Parses JSON data from API responses into structured objects representing temperature, humidity, and weather conditions.

## APIs Used

1. **Google Translate API:** Translates text between different languages.
   - **Endpoint:** `https://translation.googleapis.com/language/translate/v2`

2. **APILayer Geo API:** Fetches country and city information.
   - **Endpoints:**
     - Convert country name to ISO code: `https://api.apilayer.com/geo/country/name/{countryName}`
     - Get list of cities by country ISO code: `https://api.apilayer.com/geo/country/cities/{countryIsoCode}`

3. **OpenWeatherMap API:** Fetches weather data for a specific city.
   - **Endpoint:** `https://api.openweathermap.org/data/2.5/weather`

## Results
### Form 1 Execution
- Selecting language, country, and city.
- Switching languages (e.g., English → Chinese).
- Changing country and city (e.g., Spain → Galicia).
- Light/Dark mode toggle.
- Exit button functionality.
- Viewing the 5-day forecast.

### Form 2 Execution
- Light/Dark mode toggle in the 5-day forecast form.
- Viewing detailed weather for a specific day in the forecast.

## Evaluation
### Pros:
- **Accuracy:** Weather data is correctly displayed based on OpenWeather API responses.
- **Usability:** Users can easily enter a city name, view the 5-day forecast, and check hourly forecasts.
- **Interface:** Simple and intuitive, with clear functional divisions.

### Cons:
- **Incomplete API Information:** Some API responses may lack details.
- **UI Optimization:** Manual assignment of text to labels causes redundancy and maintenance difficulties as components increase.


## License
This project is licensed under the MIT License.

## Contributors
- **Tran Minh Khang** - Developer
- **Nguyen Trong Duc** - User Interface
- **Huynh Bao Dien** - API, Developer
- **Ca Diep Thanh Binh** - Logic, Developer

## Contact
For any inquiries, contact kasick.0404@gmail.com.
