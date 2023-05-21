# MyMovies Watchlist React App

The web can be checked out here  https://animeocean.netlify.app/

## File Structure

- public
  - index.html
- src
  - Components
    - Airing.js
    - AnimeItem.js
    - Gallery.js
    - Homepage.js
    - Popular.js
    - Sidebar.js
    - Upcoming.js
  - context
    - App.test.js
  - global.js
  - setupTests.css
  - App.js
  - Gloabalstyle.js
  - index.js
* index.js: The entry point of the application where the React app is rendered to the DOM.
* index.css: The CSS file for the root component.
* App.js: The main component that acts as a router and contains the routes for different pages.
* components: A directory containing reusable components used in the app.
    * Home.js: A component representing the home page of the app, displaying a list of movies.
    * Watchlist.js: A component representing the watchlist page, displaying saved movies.
    * MovieDetails.js: A component representing the movie details page, showing details of a specific movie.
* context: A directory containing the React context for managing favorite movies.
    * FavoriteMovies.js: A context provider component for managing favorite movies.

## Must-Have Features

- [x] Responsive app
- [x] Using an API to fetch data
- [x] Home Page: The home page displays a list of Animes fetched from an API. It allows users to search for movies by keyword and filter movies .
- [x] Movie Details Page: The movie details page shows detailed information about a specific movie, including its title, Rank , runtime, release date, and description.
- [x] Can also check the anime characters and their images and watch a trailer about the anime .

## Nice-to-Have Features
- [x] Anime Trailer: Show a trailer for each anime .
- [x] A short descreption about the anime 
- [x] Sorting and Filtering: Add options to sort anime by popularity,

## Getting Started
To run the React app locally, follow these steps:

1. Clone the repository.
2. Install dependencies by running npm install.
3. Start the development server with npm start.
4. Open the app in your browser at http://localhost:3000.

