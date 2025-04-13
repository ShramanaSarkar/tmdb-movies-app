# TMDB MOVIES APP
Create a project in ReactJS, Redux and Material UI:
Build a web app with two tabs in sidebar – Home and My List – using TMDB (The Movie Database) API
(https://developer.themoviedb.org/reference/intro/getting-started).

## Web App Structure
Sidebar Tabs:
* Home - Displays movies in various sections.
* My List - Displays movies saved by the user.

## Home Tab
Use TMDB APls to fetch the following categories of movies:
* Now Playing(/movie/now_playing)  
* Popular(/movie/popular)  
* Top Rated(/movie/top_rated)  
* Upcoming(Imovie/upcoming)

## Ul for Each Section:
Each movie item should show:
* Thumbnail image (poster)  
* Title  
* Rating  

Display these sections vertically one after another, with each section having a vertical scroll for movies and should be responsive.

## Movie Details Page:
When the user taps on any movie from the Home tab:
Show the following details using the Apis:-
("/movie/{movie_id}",/movie/{movie_id}/credits)
* Thumbnail (poster image)  
* Movie title  
* Rating  
* Overview  
* Cast names  
* Director  

### Add to My List:
* A button to Add/Remove this movie from the user's My List.

### Show Similar Movies:
* Api end point: /movie/{movie_id}/similar

* At the bottom, show a section titled "Similar Movies" using TMDB's similar movies API.
* Display similar movies with:  
    * Thumbnail  
    * Title  
    * Rating

## My List Tab
Only shows the movies that the user added using the "Add to My List" button.
* Each movie item in the list:  
    * Thumbnail image  
    * Title  
    * Rating  
* Show it in a vertical list format.
