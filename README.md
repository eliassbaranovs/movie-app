# Movie Search App

This is a **Movie Search App** built with **React** and **Tailwind CSS**. It allows users to search for movies and view trending movies. The app uses the **TMDB API** for fetching movie data and **Appwrite** for managing search counts.

## Features

- 🔍 Search for movies by title
- 🎬 View trending movies
- 📱 Responsive design
- ⏳ Debounced search input
- ⏳ Loading spinner for asynchronous operations

## Project Structure

```plaintext
MovieSearchApp/
│-- src/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   ├── Search.jsx
│   │   ├── Spinner.jsx
│   ├── api/
│   │   ├── appwrite.js
│   │   ├── getTrendingMovies.js
│   │   ├── updateSearchCount.js
│   ├── App.jsx
│   ├── index.js
│-- public/
│-- .env.local
│-- package.json
│-- tailwind.config.js
│-- eslint.config.js
│-- README.md
```plaintext

## Installation

### Clone the repository

```sh
git clone https://github.com/eliassbaranovs/movie-app
```

### Install dependencies

```sh
npm install
```

### Create a `.env.local` file in the root directory and add your TMDB API key and Appwrite project details

VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id

```

## Usage

### Start the development server

```sh
npm run dev
```

Open your browser and navigate to **[http://localhost:3000](http://localhost:3000)**.

## Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview the production build

## Configuration

- **Tailwind CSS** is configured in `tailwind.config.js`.
- **ESLint** is configured in `eslint.config.js`.

## Components

- `App.jsx` - Main component that renders the app
- `Search.jsx` - Search input component
- `MovieCard.jsx` - Component for displaying individual movie details
- `Spinner.jsx` - Loading spinner component

## API Integration

- `appwrite.js` - Contains functions for interacting with Appwrite
- `getTrendingMovies.js` - Fetches trending movies from Appwrite
- `updateSearchCount.js` - Updates the search count for a movie in Appwrite

## License

This project is licensed under the **MIT License**.

# movie-app
Movie searching app with trending movies and database(appwrite)
