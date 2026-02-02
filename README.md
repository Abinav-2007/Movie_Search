# Movie Search App

A simple movie search application that displays top movies and new releases using the OMDB API.

## Setup

1. **Get an API Key:**
   - Sign up for a free API key at [OMDB API](https://www.omdbapi.com/apikey.aspx)
   - The free tier allows 1,000 daily requests

2. **Configure Environment:**
   - Open the `.env` file in your project root
   - Replace `your_api_key_here` with your actual OMDB API key:
     ```
     VITE_OMDB_API_KEY=your_actual_api_key_here
     ```

3. **Run the Application:**
   - Open `index.html` in your web browser
   - Or use a local server for better development experience

## File Structure

```
movie_search/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── config.js           # Configuration and API settings
├── .env               # Environment variables (API key)
└── .gitignore         # Git ignore rules
```

## Features

- Search for movies by title
- Display top movies and new releases
- Responsive design
- Secure API key management

## Security Note

The `.env` file is included in `.gitignore` to prevent your API key from being committed to version control. Never commit API keys to your repository!

## API Usage

This app uses the OMDB API (https://www.omdbapi.com/) which provides movie data including:
- Movie titles and posters
- Release years
- Ratings and plot summaries
- Cast and crew information

## Development

For production deployment, consider using a build tool like Vite or Webpack that can properly handle environment variables and minify your code.