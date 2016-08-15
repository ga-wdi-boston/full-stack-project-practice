# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My idea is an app where you can keep track of your favorite basketball player's
stats and social media accounts. I came up with it because I love the NBA but I
usually have to go to separate team's web sites to check out how player's are
doing that don't play for the celtics.

It would be cool to just go to one place and be able to see my favorite celtic
and non celtics player's stats together. There is also a lot of players that
have multiple social media accounts that they use frequently but I don't have
any social media accounts so I can't subscribe to any of them. This way I could
include links to their individual platforms so that I could check them when I
wanted to without having to sign up for the services.

Fans of the NBA would use this.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a User I want to see all my favorite players' stats together.
As a User I want to be able to save and edit my list of favorite players.
As a User I want to be able to browse a list of teams and their players.
As an Admin I want users to be able to see other users' lists without editing
them.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Table: Users
Columns: id, username, password, fav players(references)

Table: Players
Columns: id, given name, surname, team, position, points per game, rebounds per
game, assists per game, steals per game, blocks per game, etc.

Table: User's Fav Players
Columns: id, player_id(ref), player_id(ref), etc.

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

Each User will have one list of favorites
Each Fav List will belong to one user

|Users| 1---1 |Fav List|

Each List can have multiple players on it
Every player can belong to multiple lists

|Fav List| *---E |Players|

## Routing

What routes will you need to be able to make the proper request to your API?

the user will be able to sign up, sign in, change their password
and sign out using post, patch, and delete requests. The users will also be
able to select players to add to their favorites list, and delete players from
their list. Users also can use get requests to see their list and other users'
lists as well. May also make it so users can have multiple lists so they can
delete an entire list or just update a list.

## 3rd Party APIs

Do you plan to use any, if so what are they?

Ideally I would like to connect to the nba stats api so it can
actually be up to date with each player's stats during the
season. Will attempt this if I have time.

## Wireframes

Please create a wireframe of your planned front end.

<http://imgur.com/a/eEWvm>

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

I will create a wire frame first.

I will make a basic HTML and CSS structure to work with.

After that the functionality of the sign in process, including
the front end and back end. The front end should be easier this
time around having my tic tac toe sign in as a reference.
Hopefully integrating that with handling the back end aspect of
it as well won't prove too challenging.

I will set up my data-base with teams and players.

After that I will make the system of selecting your favorite players so that
they will be displayed on your personal user screen.

Next I will allow users to select other users so they can see
their favorite team and list of favorite players.

Finally I will go in and try to make the app look really nice
since by then all my functionality will be good to go.

If I have time after that or after the project has been submitted I will see
how to go about using the nba stats api to fill the player's data in with up to
date information each time the user signs in.
