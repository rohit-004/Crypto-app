# Coin Tracker Web App

This project is a web application built with React.js for tracking cryptocurrency prices, market data, and related information. It utilizes Chakra UI for styling and Chart.js for displaying price charts.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/coin-tracker.git

2. Navigate into the project directory:

   ```bash
   cd coin-tracker

3. Install dependencies using npm or yarn:

   ```bash
   npm install
   ```bash
   yarn install
   
4. Start the development server:

   ```bash
   npm start
   ```bash
   yarn start

5. Open your browser and visit http://localhost:3000 to view the application.

## Project Structure

- **index.js**: Entry point of the application. Renders the main `<App />` component wrapped in a `<ChakraProvider />` for styling.
- **App.js**: Main component that sets up routing using React Router. Includes the header, footer, and routes to different sections of the application.
- **components/Header.jsx**: Header component containing navigation links to home, exchanges, and coins sections.
- **components/Chart.jsx**: Component for displaying price charts using Chart.js library.
- **components/CoinDetails.jsx**: Component for displaying detailed information about a specific cryptocurrency, including charts and related data.
- **components/Footer.jsx**: Footer component for displaying additional information or links.

## Dependencies

- React: A JavaScript library for building user interfaces.
- React Router: Declarative routing for React applications.
- Chakra UI: A simple, modular and accessible component library for React applications.
- Chart.js: Simple yet flexible JavaScript charting library for designers & developers.
- Axios: Promise-based HTTP client for the browser and Node.js.

## Credits

This project utilizes data from the CoinGecko API ([https://www.coingecko.com/api/documentation](https://www.coingecko.com/api/documentation)) for fetching cryptocurrency information.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
