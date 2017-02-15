# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project will be a live music playlist generator based off of user band and associated song preferences. A user will have 'liked' bands, and 'liked' song preferences for each band(preferences such as length, age, frequency). A user should be able to create an account, log-in, select his/her favorite bands(from a given selection), and denote what kind of songs they want compiled into a randomly order playlist. After the user is done listening to said playlist, user can delete and or save and create another playlist with similar or different preferences.

I chose this because I like new music and would like to have an application that would create playlists for me based on my listening preferences.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

User can create an account.

User can select favorite bands.

User can select specific information about certain band's catalog to preference in playlist creation.
  User can preference artist albums to draw from.
  User can preference songs with length < or > Xmin to draw from.
  User can preference songs first/last played after a certain last_time_played/first_time played

User can save a created playlist.

User can delete a created playlist.


## Plan your tables and columns

User table(name, bands, song_type_preferences)

Bands(name,song lists)

Songs table (band, albums, song_length, date_first_played, date_last_played)


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

In notes.

## Routing

What routes will you need to be able to make the proper request to your API?

Show, create, upate, destroy, index.

## 3rd Party APIs

Do you plan to use any, if so what are they?

Potentially. Nugs.net, LivePhish, Wikipedia. Otherwise I was thinking, for simplicities sake, creating file that houses a collection of songs that I input on my own.

## Wireframes

Please create a wireframe of your planned front end.

In Notes

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

In notes
