<div style="font-size: 17px;background: black;padding: 2rem;">

# Functional Requirements

- <b style="color: Salmon;">Home Page:</b> By default a genre-partitioned-grid-view of movies should be there in which each row will correspond to a genre and top-30 highest IMDB rated movies of that specific genre in random order (think over this one, may be latest releases could be used instead of IMDB Rating). On hovering over a movie for 3 seconds, a small modal should open like Netflix and on clicking it, big modal should open which should have following stuff related to movies: 
    - Embedded YouTube Trailer
    - Trailer views and likes
    - Worldwide box office collection / Footfalls
    - OTT Platforms on which they are available and on clicking, it should be redirect to them
    - Views of that movie on that OTT Platform (if possible)
    - IMDB Rating and total number of votes
    - Rotten tomatos rating
    - Bookmyshow rating
    - Movie length
    - Year released
    - Country
    - Language
    - Cast
    - Director
    - Production house
    - Plot summary
    - Genre
    - No of times that movie was searched on Google/YouTube

- <b style="color: Salmon;">Filters:</b> When any filter is selected, default view i.e. genre-partitioned-grid-view will be removed and normal list grid/views will be applied. Both views should be togglable.
    - **Normal Filters:** `Country`, `Genre`, `OTT Platform`, `Year released`, `Movie length`, `Language`
    - **Sortable filters:** `Trailer views and likes`, `WW Box Office`, `IMDB rating`, `Rotten Tomatoes`, `BookMyShow`, `Google/YouTube Searches`

- <b style="color: Salmon;">Search Bar:</b> List of actors, directors and films should be displayed on entering text in search bar. If user selects a/an:
    - **Actor/Director:** List of films of that actor should be displayed.
    - **Film:** List should remain unchanged and modal of movie should open.

- Check if it is possible to fetch free movies available on youtube with above filters applicable. If not, make it a section of freely available movies manually.

- Add some games like guess the movie, guess the song, etc: Make it online game.

<br>

# Non-Functional Requirements

- Theme (dark/light/custom ones(some superheroes pre-created))
- Error Handling
- Hosting the website
- User Interaction: Allow users to create accounts, rate movies, and save favorite movies.
- Recommendations: Use algorithms to suggest movies based on user preferences and watch history.

<br>

# Tech

- HTML5
- Scss
- Tailwind CSS
- TypeScript (and JavaScript)
- React
- Redux
- Axios
- TanStack Query (react-query)
- GraphQL
- Next UI
- Framer Motion / React Spring / React Motion
- Vite integration (*later)

</div>