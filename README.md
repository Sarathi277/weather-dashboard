# Weather Dashboard

A modern, responsive weather application that provides current weather conditions for any city worldwide. Features a beautiful gradient background with animated transitions and a clean, glass-morphism UI design.

![Weather Dashboard Screenshot](https://via.placeholder.com/500x300?text=Weather+Dashboard+Screenshot)

## Features

- Real-time weather data for any city
- Beautiful animated gradient background
- Glass-morphism UI design
- Responsive layout that works on all devices
- Detailed weather information including:
  - Current temperature
  - Feels-like temperature
  - Humidity
  - Wind speed
  - Weather description
- Error handling for invalid city names
- Search by either clicking the button or pressing Enter

## Technologies Used

- HTML5
- CSS3 (with animations and transitions)
- JavaScript (ES6+)
- OpenWeather API (via RapidAPI)
- Font Awesome icons
- Google Fonts (Poppins)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-dashboard.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-dashboard
   ```

3. Open `index.html` in your browser:
   ```bash
   open index.html  # On Mac
   start index.html # On Windows
   ```

## API Configuration

To use this application, you'll need to:

1. Sign up for a free account at [RapidAPI](https://rapidapi.com/)
2. Subscribe to the OpenWeather API
3. Get your API key
4. Replace the placeholder in `script.js`:
   ```javascript
   const API_KEY = 'your-api-key-here';
   ```

## Usage

1. Enter a city name in the search field
2. Click the search button or press Enter
3. View the current weather conditions for that city

## Project Structure

```
weather-dashboard/
├── index.html        # Main HTML file
├── script.js         # JavaScript functionality
├── styles.css        # CSS styles
└── README.md         # Project documentation
```

## Customization

You can easily customize the app by modifying:

- The gradient colors in `styles.css` (look for the `background` property in the `body` selector)
- The glass-morphism effect intensity by adjusting the `backdrop-filter` values
- The weather card appearance in the `.weather-card` class
- The API endpoint if you want to use a different weather service

## Browser Support

The app works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## Acknowledgments

- OpenWeather for the weather data API
- RapidAPI for API hosting
- Font Awesome for icons
- Google Fonts for typography
