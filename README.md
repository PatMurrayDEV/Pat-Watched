# Pat Watched Tumblog Theme
Theme to create a Tumblog identical to watched.patmurray.co

There are some specific steps that need to be taken for the theme to work and look best.

## Installing

1. Make sure to update link URLs, including the link to `scroller.js` (which you will need to upload to Tumblr).
2. To adjust the colour scheme of the site, change the `color:` and `background-color:` tags throughout the css. Exclude changing the colours of the `.wrapper` elements. This is black for the hover effect.
3. Manually add the years links in the header for all the years you are cataloguing. This will need to be adjusted each year manually. 


## Posting a New Movie
1. **Find poster art online**. I tend to use [theMovieDB](//themoviedb.org) as they have the best selection of high quality posters that lack superfluous text.
2. **Start a new Photo post in Tumblr**. Make sure it’s a photo post. You can then paste in the URL of the poster found in step 1. (If you downloaded the image, now is the time to upload it).
3. **Type in tags**. For the start rating and the hover effect the post needs to be correctly tagged. **This is very important**.  
The tags are, in order:  
    1. **Name of the movie**: prefixed with `title_ ` (this allows the javascript to know which tag is definitely the title. 
    2. **Star Rating**: a 1 to 5 rating of the film. Used to create the ★★★★★ hover effect.
    3. **Year of rating**: this allows for sorting of the list by year using tags. 
    4. **Other tags**: The Tumblr search exclusively searches tags of posts. This means if you want posts to be indexed easier add extra tags. An example is adding the tag `fast and furious` to the film *"Furious 7"*.
4. **For movies with reviews**: If you’ve written a review of a movie somewhere (e.g., on [your blog](http://words.patmurraydev.com/post/133103656353/spectre)) paste the URL in the post’s `Content Source`. This is hidden under the cog in the post page. Posts with reviews will have a review banner placed across the poster, and will be hyperlinked to the review.


## Dividing a New Year
1. Create a new text post
2. Title the year that just ended
3. Thats it. Everything else is taken care of.

(There is no way of having a current year banner at the top of the page, though a permanent one could be put in the theme pretty easily. I just don’t want the for my site).

## About
Inspired by [Alex Watched](//watched.alexforey.com). Read about it on my blog: [here](http://words.patmurraydev.com/post/132992016023/pat-watched).




