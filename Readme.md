This is a movie app made with HTML, CSS, JavaScript, jQuery, and Bootstrap using API calls from The Movie Database. It uses API calls to get movies from The Movie Database. Users can view the most popular movies, arrange them by genre, or use the search function to find other titles. When visiting this URL, the user is greeted with a page of the latest movies that are now playing in theaters.

Clicking on each movie opens up its details in a modal. Within the modal, users can view the trailer or see the times that the movies are playing at Popcorn Bits. Overviews, release dates and ratings for the movie are also visible.

To get the data for each movie, I had to run $.getJSON twice, once for the results and the second time to get particular data for each of those results. Additionally, I used a "for" loop after the first one to target where the data from movieSearchResults is. To make it possible for the app to display movies categorized by genre and searched movies, I initiated an empty HTML string and then built a new HTML string to overwrite it (using .append() To change the label on the page accordingly, I had it attached via .html()to themovieGenreLabelid from theindex.htmlfile. You can seeconsole.log() throughout the code snippet, because I was testing my code at every point to make pinpointing bugs easier.

Technologies
The following languages, frameworks and APIs were used:

HTML

CSS

Javascript

jQuery

Bootstrap

The Movie Database API


SCREENSHOTS of THE PROJECT

![image](https://github.com/maity563/MOVIE/assets/105879104/afff03a4-9959-4051-8eec-cc795757203f)

