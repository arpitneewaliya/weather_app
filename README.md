# Weather App

A simple and elegant weather application built with React that provides real-time weather information for any city.

---

## Screenshot

<img width="1919" height="924" alt="image" src="https://github.com/user-attachments/assets/c1ba1dd9-2d19-42a1-aa3a-8fcd1f6baafd" />

---

## Live Demo

You can view the live demo of the project [here](https://arpitneewaliya.github.io/weather_app/).

---

## Features

- **City Search**: Search for the current weather in any city around the globe.
- **Real-time Weather Data**: Get up-to-date information on temperature, humidity, and wind speed.
- **Dynamic Weather Icons**: The application displays different icons based on the current weather conditions (e.g., clear, clouds, rain, snow).
- **Responsive Design**: The app is designed to be user-friendly across various devices and screen sizes.

---

## Technologies Used

This project is built with a modern tech stack, including:

- **React**: A JavaScript library for building user interfaces.
- **Vite**: A fast build tool and development server for modern web projects.
- **OpenWeatherMap API**: Used to fetch the weather data.
- **CSS**: For styling the application, with a clean and modern design.

---

## Setup and Installation

To run this project locally, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/arpitneewaliya/weather_app.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd weather_app
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```
4.  **Create a `.env` file** in the root of your project and add your OpenWeatherMap API key as shown below.

5.  **Start the development server:**
    ```bash
    npm run dev
    ```

---

## API Key

This application uses the [OpenWeatherMap API](https://openweathermap.org/api) to retrieve weather data. You'll need to obtain a free API key to run the project.

1.  Sign up on the [OpenWeatherMap website](https://home.openweathermap.org/users/sign_up).
2.  Navigate to the 'API keys' tab to get your key.
3.  Create a `.env` file in the root of your project and add your API key like this:

    ```
    VITE_APP_ID="YOUR_API_KEY"
    ```
