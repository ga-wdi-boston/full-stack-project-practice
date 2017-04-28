# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

- A recipe list that allows the user to access recipes and check off items as they cook (eg
   add them to the pot/pan/microwave - whatever)
- The main reason I came up with this is that I am not overly fond of math, and I want
  this app to eventually allow users to tap/click a function that will slice the quantities in half, 1/3, 1/4 or double or triple - whatever they want.
- Anyone who doesn't like math, but likes to cook would use it.  Novice chefs and
  experienced chefs could use it.  Busy parents won't have to worry about which
  step in the recipe they're at - it's an easy way to keep track of cooking steps.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.
  ### User Story #1
  - As a user, I want to be able to manage my recipes so I can have a place for them.
  - I want to be able to create, store, edit, locate and read my recipes with ingredients listed
  - I want the recipes I choose to be available to me.  I don't want to sort through an entire website, I just want mine.
  - I want my own user name and password, and to be able to log in and out of the SPA.
  - Eventually, I want a function that will scale the recipes as I desire (reduce or increase serving size)

## Plan your tables and columns

What tables will you need? What will the columns on the table be?
  - As of 04-27-2017 planning, I believe I will need 2 tables:
    - Ingredients (with 3 rows: QTY, UNIT, NAME)
    - RECIPE (1 row: DESCRIPTION)
  - I will need to JOIN them

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

[ERD Model from 04-27-2017](http://imgur.com/lkWw3KP)

## Routing

What routes will you need to be able to make the proper request to your API?
  - update/PATCH: update recipe, change recipe
  - create/POST: create new recipe, create new user
  - show/GET: get recipe
  - destroy/DELETE: delete recipe, change pw

## 3rd Party APIs

Do you plan to use any, if so what are they?
  - No plans to use them as of 04-27-2017

## Wireframes

Please create a wireframe of your planned front end.
[Wireframe link](http://imgur.com/MIngnNX)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

### Rough timetable (Need to get into more specifics)

Before Day 1:
  - I want to have the simple HTML and CSS finished
  - I want my ERD model complete and ready for review with a consultant.
  - Both repos (front-end and back-end) set up, README files started.
  - Have seed data ready (canned recipes each user will start with)

Day 1:
  - Review ERD model with consultant
  - Get Heroku up and running
  - Set up API's using API template
    - Have sign-up/POST, sign-in/POST, change-password/PATCH, sign-out/DELETE userIndex/GET, userID/GET finished.
  - Begin setting up back-end endpoints, hopefully finish

Day 2:
  - Continue working on back-end endpoints, hopefully finish
  - IF back-end endpoints are complete, then begin front-end app (JavaScript, jQuery, AJAX)

Day 3:
  - Work on back-end endpoints has to be done on Day 3, if not already.
  - Work on front-end app has to start on Day 3, if not already.

Day 4:
  - Continue working on front-end app
