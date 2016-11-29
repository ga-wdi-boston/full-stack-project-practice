# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

In the city I grew up in it can be trick to find bars and restaurants that are
non-smoking. My project idea is to use google maps API to map out all the
smoke free restaurants so that non-smokers, and smokers too, can find smoke free
restaurants with a nice atmosphere.


## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

I am a user and I want to:
||  search for smoke free restaurants.
||  find smoke free restaurants on a map.
||  add a restaurants to the map.
||  add ratings (how clean the air inside is generally)

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

table: Bar_Restaurants
ID, Name, Type, Location, Address, Phone, Rating, Reviews, Review_ID

table: Users
ID, Name, UserName, Ratings Given, Reviews Given, Reputation

table: Ratings
ID, Score

table: Reviews
ID, Text


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

Many to Many
Between Restaurants and Reviews

## Routing

What routes will you need to be able to make the proper request to your API?

## 3rd Party APIs

https://developers.google.com/maps/documentation/javascript/examples/map-geolocation

## Wireframes

Let me draw them for you

## Timetable

HTML - get a map showing

Build restaurants Table.

Get pins of restaurants to show up on maps.

Build other tables

Get tables linked.
