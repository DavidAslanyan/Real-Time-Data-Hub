# DailyVisit - Your Daily Dose of Information

The website in hosted via netlify, you can view it by clicking on this link
https://dailyvisit.netlify.app/

Welcome to **DailyVisit**, a dynamic and user-friendly website designed to provide you with useful, real-time information every day. Stay up-to-date with the **weather forecast** for your location, the **latest news**, and **global currency exchange rates**. 

Built with **React**, **TypeScript**, and **Redux**, **DailyVisit** pulls real-time data from reliable third-party APIs to give you a seamless experience.

## Setup & Installation

### Prerequisites
 
- **Node.js**: Make sure you have [Node.js](https://nodejs.org/) installed.
- **npm**: npm comes bundled with Node.js.

### Steps to Get Started

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/DavidAslanyan/Real-Time-Data-Hub.git
    ```
2. Navigate into the project directory if needed:
    ```bash
    cd dailyVisit
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm start
    ```
5. Open your browser and go to [http://localhost:3000](http://localhost:3000) to see the application in action.


## Features

- **Weather Forecast**: Get accurate, up-to-date weather forecasts based on your current location.
- **Daily News**: Stay informed with the latest global news headlines from trusted sources.
- **Currency Exchange Rates**: Monitor real-time exchange rates for various global currencies.
- **Location Detection**: Automatically detects your location to display personalized weather data.
- **Responsive Design**: The app adapts to all screen sizes for a smooth experience on desktop and mobile devices.

## Tech Stack

- **React**: A JavaScript library for building dynamic and responsive user interfaces.
- **TypeScript**: Adds type safety and better tooling support for a smooth development experience.
- **Redux**: Manages the application state and ensures a seamless data flow across the app.
- **Third-party APIs**:
  - [NewsAPI](https://newsapi.org/): Fetches real-time global news.
  - [Meteomatics API](https://www.meteomatics.com/): Provides accurate weather forecast data.
  - [ExchangeRatesAPI](https://exchangeratesapi.io/): Delivers real-time exchange rates for global currencies.

## Usage

- **Weather Forecast**: The weather is automatically retrieved based on your current location. You can see the temperature, humidity, and weather conditions.
- **Daily News**: View headlines and summaries of the latest global news stories.
- **Currency Exchange Rates**: Access real-time exchange rates for a variety of currencies.

## Code Structure

- `src/`: Contains the source code for the application.
  - `components/`: Reusable React components used throughout the app.
  - `features/`: Contains Redux actions, reducers, and the store configuration.
  - `pages/`: Contains main sections of the application. 
  - `utils/`: Helper functions, such as those used to fetch data from external APIs.
  - `App.tsx`: The main component that renders the application and orchestrates the layout.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the **React** and **TypeScript** communities for making web development efficient and fun.
- Special thanks to the third-party APIs for providing valuable real-time data to enhance the user experience.
