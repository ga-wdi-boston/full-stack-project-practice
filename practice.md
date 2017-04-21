# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

fridgeTrackr is an app to help people remember what is in their fridge. When I'm out of the house, I often forget what I have in the fridge and it's more likely that I'll buy something I already have. In addition, fridgeTrackr can help you keep track of when food will expire. My hope is that we can reduce accidental food waste if people are more aware of what is in their fridge.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

I want to host a browser application on Heroku, deploy online, and share my work through GitHub git repositories (API, client).

I want to maintain a commit history with detailed commit messages and produce documentation in the form of a README.

I want to create a mobile-first single-page application called foodTrackr, which will track the contents of a user's refrigerator and help reduce accidental food waste.

I want my users to have login, logout, and change password functionality.

I want to build a front-end Javascript application that can render, read, and write from a securely accessible API.

I want actions that change data to be authenticated, and "owned" by the user performing the change.

I want to utilize an ORM to create a database table structure and interact with user fridge data.

I want to create at least 4 RESTful routes for GET/POST/PATCH/DELETE requests.

I want my application to be free of bugs and console messages.

I want to use semantic HTML and practice separation of concerns.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

THE FRIDGE (current state of the fridge):
- food_id -> unique identifier for each of the foods
- name_of_food -> name of food
- date_bought -> date on which the food was bought
- exp_date -> expiration date of product
- store_bought -> store where the food was bought
- delete_i -> indicate whether the food has been eaten/finished

THE GROCERY LIST
- food_id -> unique identifier for each of the foods
- name_of_food -> name of food
- store_bought -> store where the food was bought
- purchase_i -> indicate whether the food has been purchased

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

[Imgur](http://i.imgur.com/Ck0zP2p.jpg)

## Routing

What routes will you need to be able to make the proper request to your API?
POST (create new food item)
GET (get foods in the fridge, get foods on the grocery list)
PATCH (update row when they have been eaten or purchased)

DELETE (remove row from FRIDGE table when food has been eaten)
POST (add row to GROCERY LIST table when food has been eaten)

DELETE (remove row from GROCERY LIST table when food has been bought)
POST (add row to FRIDGE table when food has been bought)

## 3rd Party APIs

Do you plan to use any, if so what are they?

I am not planning to use any 3rd party APIs for this project.

## Wireframes

Please create a wireframe of your planned front end.

[Imgur](http://i.imgur.com/Ck0zP2p.jpg)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

April 21 - 22: Logic Planning & Addtl Wireframes
April 23 - 25: Client Skeleton (HTML/CS/JS)
April 26 - 30: API
May 01 - 02: Test, Debug, Improve UI
