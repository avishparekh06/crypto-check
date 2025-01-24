
# CryptoCheck

CryptoCheck is a dynamic React application that showcases real-time cryptocurrency market data. Leveraging the CoinGecko API, it provides key metrics such as prices, 24-hour changes, and market capitalization for over 10,000 cryptocurrencies. The app features an intuitive and interactive user interface with robust search and filtering capabilities for real-time data visualization.

<img width="1512" alt="image" src="https://github.com/user-attachments/assets/8f9d6681-ec65-450c-a262-90bff966c72f" />

## Features

- Real-Time Cryptocurrency Data: Fetches live market data using the CoinGecko API.
- Interactive UI: Includes search and filtering functionalities to quickly find relevant data.
- Responsive Design: Optimized for various screen sizes for a seamless user experience.
- Data Visualization: Displays metrics like price, market cap, and daily percentage changes.
- Accessibility and Customization: Provides a clean and visually appealing interface using CSS.


## Technology Used

-	Frontend: React.js
-	State Management: Context API and custom hooks
-	API Integration: CoinGecko API
-	Styling: CSS (including custom styles and responsive design)
## Installation

To set up and run the project locally, follow these steps:

Clone the repository:
```bash
  git clone https://github.com/yourusername/cryptocheck.git
  cd cryptocheck
```
Install dependencies:
```bash
  npm install
```
Start the development server:
```bash
  npm start
```
Open the app in your browser:
```bash
  http://localhost:3000
```
    
## Usage

- View live data for thousands of cryptocurrencies.
- Use the search bar to find specific coins by name.
- View price changes, market caps, and 24-hour trends in an easy-to-read table.


## File Structure
Key Files:
- index.css: Global styles for the application.
- Navbar.css and Navbar.jsx: Styling and logic for the navigation bar.
- Home.css and Home.jsx: Styles and layout for the main dashboard displaying cryptocurrency data.
- CoinContext.jsx: Context API logic for managing global state and API data.
- main.jsx: Entry point of the React application.
