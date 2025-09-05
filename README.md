# Weather Forecast Application

A comprehensive Windows Forms application built with C# that provides real-time weather forecasting with multi-language support and AI-powered chat functionality.

## 🌟 Features

### Core Weather Functionality
- **Real-time Weather Data**: Current weather conditions and 5-day forecasts
- **Global Coverage**: Support for cities worldwide with dynamic location selection
- **Detailed Forecasts**: Hourly weather breakdowns with comprehensive data
- **Weather Visualization**: Custom weather icons and visual representations

### Advanced Features
- **Multi-language Support**: 15+ languages including English, Vietnamese, Chinese, French, Spanish, German, Japanese, Korean, and more
- **AI Chat Integration**: Weather-related conversations powered by Google Generative AI
- **Theme Support**: Light and dark theme options with custom styling
- **Real-time Translation**: Automatic text translation using Google Translate API

### User Experience
- **Responsive Interface**: Modern Windows Forms design with smooth interactions
- **Loading States**: Visual feedback during API calls and data loading
- **Error Handling**: Comprehensive error management with user-friendly messages
- **Intuitive Navigation**: Easy-to-use interface with logical flow

## 🛠️ Technical Stack

### Programming & Framework
- **Language**: C# (.NET Framework 4.7.2)
- **UI Framework**: Windows Forms
- **Architecture**: Multi-form application with modular design

### Libraries & Dependencies
- **RestSharp**: HTTP client for API communications
- **Newtonsoft.Json**: JSON data processing
- **Google Generative AI SDK**: AI chat functionality
- **System.Net.Http**: Additional HTTP operations

### External APIs
- **OpenWeatherMap API**: Weather data provider
- **Google Translate API**: Multi-language translation
- **Google Generative AI**: Chat functionality
- **APLayer Geo API**: Country and city data

## 📋 Requirements

- Windows Operating System
- .NET Framework 4.7.2 or higher
- Internet connection for API access
- Valid API keys for external services

## 🚀 Installation & Setup

1. Clone the repository
2. Open `WeatherForecast.sln` in Visual Studio
3. Restore NuGet packages
4. Configure API keys in the respective files:
   - OpenWeatherMap API key in `Form1.cs`
   - Google APIs keys in relevant forms
   - APLayer API key in `Form1.cs`
5. Build and run the application

## 📱 Application Structure

### Forms Overview
- **Form1**: Main application interface with country/city selection and current weather display
- **Form2**: Multi-day weather forecast view with navigation options
- **Form3**: Detailed hourly weather information display
- **Form4**: AI-powered chat interface for weather conversations

### Key Components
- **ThemeManager**: Centralized theme management for light/dark modes
- **WeatherDetail**: Data model for weather information
- **Translation System**: Multi-language support infrastructure

## 🌍 Supported Languages

English, Vietnamese, Chinese (Simplified), Chinese (Traditional), French, Spanish, Indonesian, Italian, German, Ukrainian, Russian, Armenian, Japanese, Thai, Korean

## 📊 Project Highlights

### Development Skills Demonstrated
- Windows Forms application development
- RESTful API integration and consumption
- Asynchronous programming patterns
- Multi-language internationalization (i18n)
- AI/ML service integration
- Custom UI component development
- Software architecture and design patterns
- Error handling and user experience design

### API Integration Complexity
- Multiple concurrent API calls
- Data transformation and mapping
- Error handling and retry logic
- Rate limiting and performance optimization

## 🔧 Configuration

The application requires API keys for:
1. **OpenWeatherMap**: For weather data access
2. **Google Translate**: For multi-language support
3. **Google Generative AI**: For chat functionality
4. **APLayer**: For geographical data


---

*This project demonstrates proficiency in C# development, API integration, multi-language support, and modern application architecture patterns.*
