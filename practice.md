# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is a crowd-sourced music-discovery platform. The platform hosts 'tournaments' organized around different music categories. For example, there might be a tournament organized to identify the best folk indie song released that month. A tournament called 'Best Folk Indie Song - April 2017' would begin, and users would have the option to enter a song into the tournament. Say it's a three round tournament; that requires 8 entrants, and once all the spots are filled, entry is closed and the tournament begins. Songs are then paired off into head to head competitions, where user voting determines who moves on to the next round.  After 3 rounds of head to head contests, one song emerges as the winner. It's a fun way to find new music, and to share the music you love.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

- As a user, I want to build a song catalog of my favorite songs.
- As a user, I want a user profile that shows me: my song catalog, any active contests I'm involved in, and a history of past contests
- As a user, I want to be able to see a list of open tournaments, for which I can enter a song.
- As a user, I want to be able to remove a song from my catalog.
- As a user, I want to be able to edit a song from my catalog to change, for example, the genre I've listed for that song.
- As a user, I want a user authorization system to protect the privacy of my account.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

User: ID, Email, User Name, Password, Song_Foreign_ID, Contest_Foreign_ID.

Song: ID, Song_Name, Artist_Name, Genre, URL

Contest: ID, Category, Song1, Song2, Song1VoteCount, Song2VoteCount, Over?


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

A user has many songs
A user has many contests
A contest has at least 2 users
A song has many users

## Routing

What routes will you need to be able to make the proper request to your API?

HiddenTracks/user/
HiddenTracks/user/:id

HiddenTracks/user/songs/
HiddenTracks/user/songs/:id

HiddenTracks/user/contests/
HiddenTracks/user/contests/:id


## 3rd Party APIs

Do you plan to use any, if so what are they?

Not to start.

## Wireframes

Please create a wireframe of your planned front end.

[HiddenTracks - Wireframe](http://i.imgur.com/DSaoAOK.jpg)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

1. HTML/CSS scaffold done by 4/21
2. Auth done by 4/23
3. User and Song Table created by 4/25, with joins
4. Contest Table created by 4/26
5. Application Logic by 4/28
