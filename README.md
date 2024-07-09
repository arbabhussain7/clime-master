# Weather App 




## Overview

This Weather App is designed for beginners learning asynchronous programming in Dart. Inspired by Olia Gozha’s designs, the app enables users to check live weather for their current location or any city. Throughout this project, you will learn to use async and await, work with Futures, and network with the Dart http package. 

## Features

- **Current Location Weather**: Get live weather updates for your current location.
- **City Weather**: Check the weather for any city by entering its name.
- **User Input**: Use the TextField Widget for user input.
- **Geolocation**: Retrieve live location data using the Geolocator package.
- **Error Handling**: Manage exceptions and errors gracefully.
- **API Integration**: Fetch weather data from a weather API and parse JSON responses.

## Technologies Used

- **Flutter**: For building the cross-platform mobile application.
- **Dart**: The programming language used with Flutter.
- **http package**: For networking and making API calls.
- **Geolocator package**: For accessing live location data.
- **Async and Await**: For handling asynchronous programming.
- **JSON Parsing**: For decoding JSON responses from the API.

## Getting Started

### Prerequisites

- Flutter SDK
- Dart SDK
- API key from a weather service provider (e.g., OpenWeatherMap)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/weather-app.git
    cd weather-app
    ```

2. **Install dependencies**:
    ```bash
    flutter pub get
    ```

3. **Set up API key**:
    - Obtain an API key from a weather service provider.
    - Create a `.env` file in the root directory and add your API key:
      ```
      WEATHER_API_KEY=your_api_key_here
      ```

4. **Run the app**:
    ```bash
    flutter run
    ```

## Usage

1. **Check Current Location Weather**: Launch the app to automatically get the weather for your current location.
2. **Check City Weather**: Enter the name of any city to get the weather details.
3. **Handle Errors**: The app will provide feedback if there are issues with location access or network errors.

## Code Structure

- **main.dart**: The main entry point of the application.
- **weather.dart**: Handles weather data fetching and JSON parsing.
- **location.dart**: Manages geolocation data retrieval.
- **ui/**: Contains UI components and widgets.

## Learning Outcomes

- **Asynchronous Programming**: Understand and use async and await in Dart.
- **Futures**: Work with Futures to manage asynchronous tasks.
- **Networking**: Use the http package to make API calls.
- **Error Handling**: Implement error handling for API calls and location data retrieval.
- **User Input**: Use the TextField Widget for capturing user input.
- **Geolocation**: Retrieve and use live location data.

## Contributing

We welcome contributions from the community. Please read our [Contributing Guidelines](link-to-contributing-guidelines) before submitting a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please feel free to reach out at [arbabhussain414@gmail.com](arbabhussain414@gmail.com)
