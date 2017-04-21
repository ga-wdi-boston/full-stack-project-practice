# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is an app that allows a user to create Trip lists in which they
can add or remove cities to a list. A user can create many different Trips and
each Trip can consist of many cities. I want to build this app because today
I manage all my trips in Google Sheets and wanted to experiment with developing
my own simple Trip management application. In this case it's more of a trip
wish list. As I simplified the design I determined this would be useful for a
user who wants to plan a trip and needs to determine what cities they would like
to include in one trip.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

-   As a user I want to be able to create an account
-   As a user I want to be able to sign into my account so I can create and view Trips
-   As a user I want to be able to create Trips
-   As a user I want to be able to add city locations to a Trip
-   As a user I want to be able to remove city locations from a Trip
-   As a user I want to be able to delete a Trip
-   As a user I want to be able to change my password
-   As a user I want to be able to sign out of my account so my Trips are no longer visible

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

I will have three tables - Users, Trips, Cities.

Users - id, given_name, family_name
Trips - id, trip_name, user_id (fk)
Cities - id, state, country, trip_id (fk)

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

A User can have 1 to many Trips.
A Trip can have 1 User associated.
A Trip can have 1 to many Cities.
A City can only be associated to 1 Trip.

## Routing

What routes will you need to be able to make the proper request to your API?
I will need index, create, show, update, destroy

## 3rd Party APIs

Do you plan to use any, if so what are they?

If I have time and capacity I want to utilize any APIs available that provides lists
of cities, for now I plan to hardcode a list of 20 cities.

## Wireframes

Please create a wireframe of your planned front end.
[Imgur](http://i.imgur.com/mUv0GiT.jpg)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.
1. Create user stories and wireframes (~2 hours)
2. Create database table design (~3 hours)
3. Create simple UI using HTML/CSS/bootstrap (1 day)
4. Create API backend (3 days)
5. Create front end/client (2 days)
