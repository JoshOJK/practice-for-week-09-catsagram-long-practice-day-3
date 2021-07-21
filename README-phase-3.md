# Catsagram Phase 3: Store the application state in web storage

Your Catsagram app from day 2 will reset every time you reset the page. Today,
you will be storing the state of the application so the data does not get reset
every time your reload the page.

## Set up

You can either build off your Catsagram project from the previous days or
clone the practice for this day from the [starter].

## Instructions

Store the state of the information about the current image, the upvote counter,
and the comments, in `localStorage`.

Doing this prevents an accidental refresh from replacing the cute kitty you
were just looking at. This means that whenever the page loads, you will have to
check `localStorage` to see if there was a previous image and render the page
with that image data instead. Otherwise, your page should load in a fresh image
if it's the first time the user is accessing the page.

By the end of day 3, you should have the following features implemented:

- An image should load when a user arrives on Catstagram.
- If users want to fetch a new kitten image, then clicking the 'New Pic' button
  should load up a new image.
- The user can upvote and downvote the kitten image.
- The user can create a comment. When a comment is created, it gets appended
  below all the other existing comments.

Great job on implementing all the core features of Catstagram!

[starter]: https://github.com/appacademy/practice-for-week-09-catstagram-long-practice-day-3