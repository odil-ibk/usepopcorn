# usePopcorn 🍿

A movie search and watchlist app built with React while following a React course on Udemy. Search for movies, see their details, rate them, and keep track of what you've watched.

## Features

- Search movies by title using the OMDb API
- View movie details (poster, plot, cast, IMDb rating)
- Rate movies with a reusable star rating component
- Keep a watched list with summary stats
- Watched list is saved in the browser

## What I practiced

- Fetching data with `useEffect`
- Handling loading and error states
- Cleanup functions and race conditions
- Building custom hooks
- Reusable components
- Syncing state with `localStorage`
- Conditional rendering

## Tech stack

- React
- JavaScript (ES6+)
- CSS
- OMDb API

## Run locally

```bash
git clone https://github.com/odil-ibk/usepopcorn.git
cd usepopcorn
npm install
npm start
```

You need your own free API key from [omdbapi.com](https://www.omdbapi.com/apikey.aspx). Add it to the project as described in the code, then start the app.

If the project uses Vite, run `npm run dev` instead of `npm start`.

## Acknowledgements

Built as a practice project while learning from a Udemy React course.
