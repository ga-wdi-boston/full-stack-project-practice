# Full Stack Project Practice

You will be presenting this early next week.  Please have a brief presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is to create a meal database that could eventually be extended into a meal tracker and planner capable of letting the user track their calories and health related information.  At first, the scope is going to be much smaller, perhaps allowing the user to add meals to the database and maybe plan one day's worth of meals.  I came up with this because my fiancee uses an app to log her food to keep track of calories, but we often want to be able to plan our week's food with her goals in mind.  A stretch goal is to have it generate a shopping list based on the coming week's plan.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a new visitor, I can sign up to the site.
As a user, I can sign in and view my account info.
As a user, I can sign in and add a meal.
As a user, I can view my meals.
As a user, I can add a meal into a one day plan.
As a user, I can search through a list of ingredients to add to a meal.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?
I'm going to need a meals table, an ingredients table, and a join table that links them together.
Meals will have name, ingredients, and instructions.
Ingredients will have name and unit, eventually calories per unit.
Join table will have id's of both, and a quantity that is needed in the recipe.

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

http://imgur.com/a/f0AvR

## Routing

What routes will you need to be able to make the proper request to your API?
Users
  post '/sign-up' => 'users#signup'
  post '/sign-in' => 'users#signin'
  delete '/sign-out/:id' => 'users#signout'
  patch '/change-password/:id' => 'users#changepw'
Meals
  post 'meals' => 'meals#create'
  patch 'meals/:id' => 'meals#update'
  delete 'meals/:id' => 'meals#destroy'
  get 'meals' => 'meals#get'
  get 'meals/:id' => 'meals#get'
Ingredients
  post 'ingredients' => 'ingredients#create'
  patch 'ingredients/:id' => 'ingredients#update'
  delete 'ingredients/:id' => 'ingredients#destroy'
  get 'ingredients' => 'ingredients#get'
  get 'ingredients/:id' => 'ingredients#get'
Requirements (Join table)
  Not sure yet.

## 3rd Party APIs

Do you plan to use any, if so what are they?

Eventually I might try and connect a calendar so that I can add meals into an already existing calendar.

## Wireframes

Please create a wireframe of your planned front end.

http://imgur.com/kcYlLcN

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Before friday: model backend
Friday: Create the models and databases and fill them with some example data
Saturday: Create a basic front-end that allows me to interact with backend.
Sunday: Less work today, maybe some styling.
Monday: Lots of work on front end.  Make sure all the requirements are met.
Tuesday: Try and work on some stretch goals, make front end more robust.
