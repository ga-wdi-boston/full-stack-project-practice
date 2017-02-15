# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea? How did you come up with it? Why? Who would use it?

My project idea is to create an app that will record plays of individual sesisons
of board games and your enjoyment of each play session.  I love board games,
but I've found that BoardGameGeek, the biggest resource for board games on the
internet, has a rather clumsy interface for recording game sessions.  Additionally,
I'm very interested in using this data to determine what games I have the most
fun playing with differing numbers of players.

## Write between 3-5 user stories

I want to be able to log in to access my data
I want to be able to log a game (played)
I want to be able to see my logged games
I want to be able to see an average score for a particular board game
I want to a score for a game based on the number of players that played
I want to see what games have scored well at a certain player count

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Player: id

Game: player_count, length

Session: player_id, game_id, rating, headcount, notes

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

http://i.imgur.com/DUazS3t.jpg

## Routing

What routes will you need to be able to make the proper request to your API?

Player: show, create //if I come up with more data for players, this will grow

Game: index, show, create, update, destroy

Session: index, show, create, destroy

## 3rd Party APIs

Do you plan to use any, if so what are they?

I have a dream of also using the BoardGameGeek API to cross post games, but
I'm not going to do any research into this until after my app is functional.

## Wireframes

Please create a wireframe of your planned front end.
http://i.imgur.com/hI33Ye4.jpg

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Priority 1 create tables, test and make sure all routes are working in rails
  -players table
  -games table
  -sessions table
Priority 2 create incredibly ugly HTML front end and connect it to the API
  - be able to create new user/log in/change password/log out
  - be able to add games to database
  - be able to search for games in database
  - be able to create new play sessions
  - be able to retrieve play sessions from database
  - be able to remove play sessions
Priority 3 make HTML fit wireframes / beautify / handlebars template for retrieving
  play sesions for a game
Priority 4 advanced functionality
  - improve log session form (create game if game not found)
  - sort through logs to show high scores based on player count
  - be able to cross post sessions to BGG
