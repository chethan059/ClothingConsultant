# Clothing Consultant 🌤️👔

An intelligent RPA (Robotic Process Automation) solution that provides clothing recommendations based on real-time weather conditions. Built with UiPath, this automation helps you decide what to wear based on the current weather in your location.

## Features

- 🌍 Real-time weather data retrieval for any city
- 🌡️ Temperature-based clothing recommendations
- ☔ Weather condition analysis (rain, snow, etc.)
- 👕 Smart outfit suggestions based on weather conditions
- 🤖 Automated web scraping of weather information

## Requirements

- UiPath Studio (version 22.4.3.0 or higher)
- Windows Operating System
- Internet connection for weather data retrieval

## Setup and Installation

1. Clone this repository to your local machine
2. Open UiPath Studio
3. Navigate to the project directory
4. Open the project by selecting the `project.json` file
5. Make sure all dependencies are properly restored
6. Run the `Main.xaml` workflow

## How It Works

1. The automation prompts you to enter a city name
2. It automatically searches for current weather conditions using web automation
3. Retrieves temperature and weather conditions for the specified location
4. Analyzes the weather data using predefined rules:
   - Temperature < 40°F: Suggests winter clothing
   - Temperature > 80°F: Suggests summer clothing
   - Considers precipitation for additional recommendations (raincoat, umbrella, etc.)
5. Provides appropriate clothing recommendations based on the analysis

## Usage

1. Run the `Main.xaml` workflow
2. Enter the name of your city when prompted
3. Wait for the automation to gather weather data
4. Receive clothing recommendations based on current weather conditions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

ALLU CHETHAN REDDY
