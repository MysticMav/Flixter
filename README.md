# Project 2 - Flix
**Flix** is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

Submitted by: **Maverick Abreu**

Time spent: **7** hours spent in total

## Flix Part 2

### User Stories

#### REQUIRED (10pts)

:heavy_check_mark: (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.  
:heavy_check_mark: (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [ ] Implement a shared element transition when user clicks into the details of a movie (1 point).
- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply data binding for views to help remove boilerplate code. (1 point)
- [ ] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF
Here's a walkthrough of implemented user stories:  
<img src="Movies2.gif" width=250><br>

### Notes

I made the application responsive in both landscape and portrait mode. I also removed the ActionBar to give the viewers a larger screen.  
Some issues I faced while making this application was that I attempted to complete the stretch stories by following the guides, but with no luck, was unable to implement them. For instances, the shared element transition caused my movie images to disapear, and was unable to even implement intent because I wasn't sure if I was placing it in the corect source file to begin with.
## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android


## Flix Part 1


### User Stories
#### REQUIRED (10pts)
- :heavy_check_mark: (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [ ] (2pts) Views should be responsive for both landscape/portrait mode.
   - [ ] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [ ] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [ ] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [ ] (2pts) Improved the user interface by experimenting with styling and coloring.
- [ ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF
Here's a walkthrough of implemented user stories:  

<img src='Movie.gif' title='App Walkthrough' width='' alt='app walkthrough' />

### Notes
The first movie had such a large overview text that it seemed to expand that entire column. I tried fixing that little issue, but was unsuccessful.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
