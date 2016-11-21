# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

Music Theory Interval Training. The idea is simple, the app plays two notes to
the user and the user has to guess the interval between them. It would be an
educational application for anyone interested in learning music theory, so
obviously primarily musicians. Another way to think of this project is a
"Music Theory Relative Pitch" application.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

-As a user, I wish to improve my interval identification so I can easier
hear and understand chords and scales.

-As a user, I wish to be able to view my past history statistics, and progress

-As a user, I wish to be able to 'play' on phone and/or browser

-As a user, I wish to have multiple difficulty settings for learning

-As a user, I wish to be able to re-play exercises

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Users table: Columns: user_id, username, password, game_stats (object?)

Game table: game_id, user_id


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

Users >----< Games   many to many relationship

## Routing

What routes will you need to be able to make the proper request to your API?

Sign-Up - > user controller
Sign-In - > user controller
Sign-Out - > user controller
change password - > user controller
New Game - > game controller
Update Game - > game controller
Retry/Replay - > game controller

## 3rd Party APIs

Do you plan to use any, if so what are they?

No plans for 3rd Party APIs yet

## Wireframes

Please create a wireframe of your planned front end.



## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

- No more than 1 hour on a specific topic without a break
- 10 minute breaks
