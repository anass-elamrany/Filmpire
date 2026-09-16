# Filmpire

Filmpire is a React movie discovery app powered by the TMDB API. It helps users browse popular, top-rated, and upcoming movies, search by title, filter by genre, view movie and actor details, and manage favorites or watchlists after signing in with TMDB.

## Features

- Browse popular, top-rated, and upcoming movies
- Search movies by title
- Filter movies by genre
- View movie details, ratings, trailers, cast, and recommendations
- View actor biographies and related movies
- Sign in with TMDB authentication
- Add movies to favorites or watchlist
- View saved movies on the profile page
- Switch between light and dark mode
- Responsive layout for desktop and mobile

## Tech Stack

- React
- Redux Toolkit and RTK Query
- React Router
- Material UI
- Axios
- TMDB API

## Getting Started

### 1. Clone the project

```bash
git clone https://github.com/your-username/filmpire.git
cd filmpire
```

### 2. Install dependencies

```bash
npm install
```

### 3. Add environment variables

Create a `.env` file in the project root:

```env
REACT_APP_TMDB_KEY=your_tmdb_api_key
ESLINT_NO_DEV_ERRORS=true
```

You can get a TMDB API key from your TMDB account settings.

### 4. Start the app

```bash
npm start
```

Open `http://localhost:3000` in your browser.

## Scripts

```bash
npm start
```

Runs the app in development mode.

```bash
npm run build
```

Builds the app for production.

```bash
npm test
```

Runs the test watcher.

## Project Structure

```text
src/
  app/          Redux store setup
  assets/       Genre icons and static assets
  components/   App pages and reusable UI components
  features/     Redux slices
  services/     TMDB API service
  utils/        API helpers and theme utilities
```

## Notes

- TMDB login is required to use favorites and watchlist features.
- Movie data, posters, trailers, cast, and recommendations come from TMDB.
