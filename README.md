# 🚀 Siam BitTrack

A modern React-based cryptocurrency tracking application built with Vite.

## Overview

Siam BitTrack is a web application that allows users to track and monitor cryptocurrency prices and information. Built with React and styled for a smooth user experience.

## Features

- 📊 Real-time cryptocurrency data
- 💰 Price tracking and monitoring
- 🔍 Detailed coin information
- 📱 Responsive design
- ⚡ Fast performance with Vite

## Tech Stack

- **Frontend Framework:** React
- **Build Tool:** Vite
- **Styling:** CSS
- **API:** CoinGecko API
- **Linting:** ESLint

## Project Structure

```
crypto-project/
├── src/
│   ├── components/
│   │   └── CryptoCard.jsx      # Reusable crypto card component
│   ├── pages/
│   │   ├── Home.jsx            # Main home page
│   │   └── CoinDetail.jsx      # Detailed coin view
│   ├── api/
│   │   └── coinGecko.js        # CoinGecko API integration
│   ├── utils/
│   │   └── formatter.js        # Utility functions for formatting
│   ├── App.jsx                 # Main App component
│   ├── index.css               # Global styles
│   └── main.jsx                # Entry point
├── public/                     # Static assets
├── index.html                  # HTML template
├── package.json                # Project dependencies
├── vite.config.js              # Vite configuration
└── eslint.config.js            # ESLint configuration
```

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd crypto-project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

### Development

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build

Create a production build:
```bash
npm run build
```

### Linting

Check for code quality issues:
```bash
npm run lint
```

## API Integration

This project uses the **CoinGecko API** to fetch real-time cryptocurrency data. The API integration is handled in [`src/api/coinGecko.js`](src/api/coinGecko.js).

## Components

- **[CryptoCard](src/components/CryptoCard.jsx)** - Displays cryptocurrency information in a card format
- **[Home Page](src/pages/Home.jsx)** - Main landing page with crypto listings
- **[Coin Detail Page](src/pages/CoinDetail.jsx)** - Detailed view of individual cryptocurrencies

## Utilities

- **[Formatter](src/utils/formatter.js)** - Helper functions for formatting prices and data display

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Create a feature branch (`git checkout -b feature/AmazingFeature`)
2. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
3. Push to the branch (`git push origin feature/AmazingFeature`)
4. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the repository.

---

Built with ❤️ for cryptocurrency enthusiasts
