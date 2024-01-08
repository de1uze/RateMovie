# usePopcorn Project

Welcome to the usePopcorn project! This React-based application is designed to provide movie enthusiasts with a seamless experience to search for movies, rate them, and manage a personal watchlist.

## Features

- **Movie Search**: Easily find your favorite movies with our responsive search feature.
- **User Ratings**: Rate movies and see how others have rated them with our integrated star rating system.
- **Watchlist Management**: Keep track of movies you've watched and those you want to see with a personalized watchlist.

## Components

Our application is composed of several reusable components, each serving a unique purpose within the app:

- `Box`: A versatile container that can be toggled open or closed.
- `ErrorMessage`: Displays error messages in a user-friendly manner.
- `Loader`: Indicates loading status to keep users informed during data retrieval.
- `Logo`: Showcases the usePopcorn logo, adding a visual identity to the app.
- `Main`: The core layout component that structures the main view of the application.
- `Movie`: Presents movie information succinctly.
- `MovieDetails`: Offers an in-depth look at a movie's details.
- `MovieList`: Lists movies based on search results or watchlist contents.
- `NavBar`: Navigates through the app with ease.
- `NumResults`: Shows the number of movies found from a search query.
- `Search`: A search input field to find movies quickly.
- `StarRating`: Allows users to rate movies and view existing ratings.
- `WatchedMovie`: Details information about movies you've watched.
- `WatchedMoviesList`: Compiles a list of all the movies you've watched.
- `WatchedSummary`: Summarizes your watched movies and ratings.

## Hooks

To enhance functionality and maintain clean code, we've implemented custom hooks:

- `useKey`: Manages keyboard events for improved accessibility and control.
- `useLocalStorageState`: Preserves state between sessions using LocalStorage.
- `useMovies`: Fetches movie information from the API efficiently.

## Installation and Setup

To get started with usePopcorn, clone the repository and install the dependencies:

```bash
git clone https://github.com/AmirrMahmoudi/usepopcorn.git
cd usepopcorn
npm install
npm start
```

## About the Project

usePopcorn is built with the following technologies:

- **React**: For building a dynamic and responsive UI.
- **JavaScript**: The scripting language providing interactivity.
- **CSS**: For styling and visually enhancing the application.
- **HTML**: The markup language used to structure content on the web.

## Contributing

We welcome contributions! If you have suggestions or want to improve the app, feel free to fork the repository and submit a pull request.

## License

usePopcorn is open-source software licensed under the MIT license.

## Live Demo

Experience the usePopcorn app in action! Check out the live demo:

[![usePopcorn Live Demo](https://usepopcorn.netlify.app/)](https://usepopcorn.netlify.app/)

## Movies You've Watched

Keep track of the movies you've watched:

- **Total Movies**: 0 movies
- **Average Rating**: 0.00 ⭐️
- **Total Stars**: 0.00 🌟
- **Total Watch Time**: 0 min ⏳

Visit the live demo to start adding movies to your watched list and rate them!

---

We hope you enjoy using usePopcorn as much as we enjoyed creating it. For any questions or contributions, please refer to the "Contributing" section above.

---

Thank you for checking out the usePopcorn project. We hope you enjoy using the application as much as we enjoyed building it!
