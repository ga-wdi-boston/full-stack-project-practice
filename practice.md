# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I'd like to design a map of the top Instagram-able spots in a given location, usually a major city or something of the like. It would show the top 10 restaurants, parks, museums, coffee shops, etc in a sidebar list and would have small pins with images showing these same top 10 spots on the map itself.

I came up with this after in two parts. The first part of this grew out of having friends ask me repeatedly for restaurant/coffee shop/museum recommendations for Montreal, Paris, and Brooklyn, and realizing I didn't have a good way to keep track of and then revisit the places I had been to without going into the depths of my Instagram. The second part happened after visiting Iceland and realizing how difficult it was to find cool, hip spots to visit, and wishing I could find a list of cool places with images. I realized that of the existing resources I had been using, TripAdvisor is geared towards white, suburban, American baby boomers and their families, and doesn't represent the milennial push to visit more understated and unexplored spots, while Yelp doesn't exist in most international places, not to mention that the former only really evaluates hotels accurately and the latter only restaurants.

My ideal user base would be the 18-35 age range, namely individuals who use social media (especially image-heavy apps like Instagram/Snapchat/Twitter) and want to find unique places to visit and document.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user I want to be able to see a list of the top ten places in a given city.
As a user I want to be able to search for a given type of place (restaurants, museums, etc) and see a top ten list.
As a user I want to be able to see the pictures associated with each place and list.
As a user I want to be able to see local Instagram profiles affiliated with the images.
As a user I want to be able to create a profile and log in.
As a user I want to be able to save interesting places for future reference.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Locations, Places, and Images, with descending one to many relationships. The column names can be seen in the ERD below.

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

(http://i.imgur.com/sXt07Ac.png)

## Routing

What routes will you need to be able to make the proper request to your API?

Locations to find a given city with general top ten places, places to find a list of a specific type of places, and then images to find corresponding images.

## 3rd Party APIs

Do you plan to use any, if so what are they?

Instagram, Google Maps (?)

## Wireframes

Please create a wireframe of your planned front end.

(http://i.imgur.com/tIrqxR8.png)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.
