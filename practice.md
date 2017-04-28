# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project is called: "Movie Night".  The basic premise is that it's a way for users to create and
maintain an online repository of movies and associated user-customizable meta data.

I thought of this idea because from time to time my wife and I will sit down to
watch a movie and have a tough time figuring out what to watch.  Should we watch
an old favorite or something new?  What was that movie we said we wanted to watch
6 months ago but have since forgotten the name of?  Which movies have we purchased on
iTunes/blu ray versus rented?

On top of that, our daughter likes to watch an assortment of kids movies.  I would
like to be able to track which ones she has seen, how many times, and how recently.

I think anyone who is a movie fan, especially those with large movie libraries, would
be interested in using this app.


## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user, I want to be able to:
1.	See a list of movies that I could potentially watch, and filter by the fields above to answer questions like the following:
  a.	What movies have I watched recently?
  b.	What movies have I not watched in a while?
  c.	What movies should I consider watching that I haven’t before?
  d.	What movies have I watched many times?
  e.	What movies do I rate the highest?
2.	Have the DB pick a random movie for me to watch
3.	Easily record each time I watch a movie. Timestamp should auto-update and counter should increment.
4.	Update user ratings for movies
5.	Record when I purchase a movie and how (disc, iTunes, etc.)

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

I think I basically need 2 tables - 1 for users and 1 for movies:

1.	Users
  a.	Name
  b.	ID
  c.	Password
2.	Movies
  a.	ID
  b.	Name
  c.	Year released
  d.	MPAA Rating
  e.	User grade
  f.	Length (min)
  g.	Whether the user owns it
    1)	If yes, whether physical disc, iTunes, other, etc.
  h.	Last time watched
  i.	How many times watched
  j.	Stretch goal – bring it additional data from 3rd party API, like Rotten Tomatoes or IMDB.


## Create an ERD (entity relationship diagram)

I'm a little unclear on whether I should have 1 movie table for each user (in which case
the relationshop would be 1 user has multiple movies) or 1 big movie table that contains
movies for all users.  I'm not sure how to accomplish the latter since we haven't yet
done many to many relationships.  That's something I'll need to clear up in the next few days.
For the time being, I've created the one to many relationship in the ERD in this repo.


## Routing

What routes will you need to be able to make the proper request to your API?

I'll need to flesh this out a big, but I think I will need at least the following:

For user authentication:
post '/sign-up' => 'users#signup'
post '/sign-in' => 'users#signin'
delete '/sign-out/:id' => 'users#signout'
patch '/change-password/:id' => 'users#changepw'

For querying the movie database:
post a new movie
patch for updates to a movie
delete a movie
index to show all movies
show to show certain movies subject to certain parameters


## 3rd Party APIs

Do you plan to use any, if so what are they?

I would love to get some meta data in there from a third party site.

Looks like Rotten Tomatoes will allow you to use their API if you get approval first.
Not sure they will grant one in this case.

I don't think IMDB has an official API but it looks like a few people offer something
similar.  I will look into this time permitting at the end.

## Wireframes

Please create a wireframe of your planned front end.

Scan included in this repo.

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Hard to come up with a timetable since we don't know the exact schedule yet, but I think Jeff
mentioned that the presentations were scheduled for May 10 at this point.

Assuming we have 5 days to work on this, I would like to complete the following:
Day 1:
  - Set up browser template
  - Deploy to GitHub pages
  - Basic HTML and CSS layout.
  - Start work on JavaScript for user interation
Day 2:
  - Build API databases
  - User authentication
  - Continue JavaScript work
Day 3:
  - Movie database querying and displaying of results.
Day 4:
  - Finalize work on JavaScript/API and HTML/CSS to display results
Day 5:
  - Spillover work.
  - Integrating 3rd party APIs (optional).
  - Readme
