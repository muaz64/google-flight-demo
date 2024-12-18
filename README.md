# Google Flights Clone ✈️

Welcome !! here is a fully responsive clone of Google Flights, built using React, TypeScript, Vite, and Material UI, with live flight data fetched from the Sky Scrapper API via RapidAPI.

![Screenshot](./public/googleflightsclone.netlify.app.jpeg)

## Features

- **Flight Search**: Search for flights between two locations with options for round-trip or one-way.
- **Dynamic Filters**: Choose travel class, number of passengers, and travel dates.
- **Responsive Design**: Fully optimized for all screen sizes.
- **Real-Time Data**: Fetches live flight information using the Sky Scrapper API.
- **Modern UI**: Built with Material UI for an elegant and user-friendly interface.

## Tech Stack

- **Frontend Framework**: React + TypeScript.
- **Vite**: Lightning-fast bundling and development.
- **UI Library**: Material UI
- **API**: [Sky Scrapper API](https://rapidapi.com/apiheya/api/sky-scrapper)
- **Styling**: Material UI and custom CSS
- **Hosting**: Netlify

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/muaz64/google-flight-demo.git
   cd google-flights-clone
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Add API Key**:
   - Sign up for the Sky Scrapper API on RapidAPI.
   - Create a `.env` file in the root directory and add your API key:
     ```
     VITE_API_KEY=your_api_key
     ```

4. **Start the Development Server**:
   ```bash
   npm run dev
   ```

5. Open the app in your browser at `http://localhost:5173`.

## Deployment

To deploy the project, you can use services like **Netlify**, **Vercel**, or **GitHub Pages**. Here's an example for Netlify:

1. Build the project:
   ```bash
   npm run build
   ```

2. Deploy the `dist` folder to Netlify.

## Usage

1. Enter your flight details (e.g., departure, destination, date, class).
2. Click the Explore button to search for flights.
3. View the search results with detailed flight information, including:

- Departure/arrival time
- Duration
- Airline
- Price

## Project Structure

```plaintext
src/
├── components/       # Reusable components (e.g., Navbar, FlightCard)
├── pages/            # Application pages
├── utils/            # Helper functions and API services
├── styles/           # Custom CSS and styling files
├── App.jsx           # Main application file
└── main.jsx          # Entry point
```

## API Integration

The app fetches flight data using the Sky Scrapper API. For detailed documentation, refer to the [Sky Scrapper API docs](https://rapidapi.com/apiheya/api/sky-scrapper).


## Live Demo

Check out the live demo: [Google Flights Clone](https://googleflightsclone.netlify.app)

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

