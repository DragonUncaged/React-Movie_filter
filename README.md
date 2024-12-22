# React-Movie_filter

# Movie Filter App

This is a simple React application that displays a list of movies and allows the user to filter them by genre. The app includes three main components: `App`, `MovieList`, and `GenreFilter`.

## Features

- Displays a table of movies with their titles, genres, and release years.
- Allows the user to filter movies by genre using genre filter buttons.
- Filters the movie list based on the selected genre.
- Logs the selected genre to the console when a genre button is clicked.

## Project Components

1. **App**: The root component that renders the entire app, including the `MovieList` and `GenreFilter` components.
2. **MovieList**: A component that displays a table with the list of movies, showing each movie’s title, genre, and year.
3. **GenreFilter**: A component that renders genre filter buttons. When a button is clicked, it logs the selected genre to the console and updates the displayed movie list based on the selected genre.

## Installation

### Prerequisites

Ensure you have Node.js and npm installed. If not, you can download and install them from [here](https://nodejs.org/).

### Steps to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/movie-filter-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd movie-filter-app
    ```

3. Install the required dependencies:
    ```bash
    npm install
    ```

4. Run the app:
    ```bash
    npm start
    ```

    This will start the development server and open the app in your browser at `http://localhost:3000`.

## Project Details

### Movies Array

The app uses the following array of movies:

```javascript
const movies = [
    { title: 'The Shawshank Redemption', genre: 'Drama', year: 1994 },
    { title: 'The Godfather', genre: 'Crime', year: 1972 },
    { title: 'The Dark Knight', genre: 'Action', year: 2008 },
    { title: '12 Angry Men', genre: 'Drama', year: 1957 },
    { title: 'Schindler\'s List', genre: 'Drama', year: 1993 },
    { title: 'The Lord of the Rings: The Return of the King', genre: 'Fantasy', year: 2003 },
    { title: 'The Good, the Bad and the Ugly', genre: 'Western', year: 1966 },
    { title: 'Forrest Gump', genre: 'Drama', year: 1994 },
    { title: 'Inception', genre: 'Science Fiction', year: 2010 },
    { title: 'The Matrix', genre: 'Science Fiction', year: 1999 },
    { title: 'The Silence of the Lambs', genre: 'Thriller', year: 1991 },
    { title: 'Saving Private Ryan', genre: 'War', year: 1998 },
    { title: 'Jurassic Park', genre: 'Science Fiction', year: 1993 },
    { title: 'Terminator 2: Judgment Day', genre: 'Science Fiction', year: 1991 },
    { title: 'The Lion King', genre: 'Animation', year: 1994 }
```

## Components Explanation
### App Component:
- Manages the main state for the application.
- Passes movies and genres arrays as props to the MovieList and GenreFilter components.

### MovieList Component:
- Receives the movies array as props and maps through it to display a table of movies with their titles, genres, and years.

### GenreFilter Component:
- Receives the genres array as props and maps through it to generate genre filter buttons. When a button is clicked, it logs the selected genre to the console.
