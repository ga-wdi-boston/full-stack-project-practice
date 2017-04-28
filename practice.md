# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

A to do list app that has a different to do list for each day of the week.
Several consultants/instructors mentioned that a to do list was a good idea
for this project.

I'm usually not satisfied with the note taking/to do apps that
I've used. I would like to use a simple weekly to do app. I think others who
desire a simple way to organize their to do lists would use this

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

Given I am a user
When I first enter the page
Then I should be able to create an account

Given I am a user
If have made an account or already have an account
I should be able to sign in

Given I am a user
When I sign in
I should see tabs to change between days of the week

Given I am a user
When I select a day of the week
I should be able to create a to-do item

Given I am a user
When I select a day of the week
I should be able to delete a to-do item


## Plan your tables and columns

What tables will you need? What will the columns on the table be?

users table

id column
username column
password column

todos table

id column
content column
day of the week column

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).


user has a one to many relationship with todo

## Routing

What routes will you need to be able to make the proper request to your API?
POST 'api/signup'
POST 'api/signin'
DELETE 'api/signout'
PATCH 'api/changepassword'

GET '/api/todos'
GET 'api/todos/:id'
PATCH 'api/todos/:id'
POST 'api/todo'
DELETE 'api/todo/:id'

## 3rd Party APIs

Do you plan to use any, if so what are they?'

No

## Wireframes

Please create a wireframe of your planned front end.
[Wire Frame 1](http://imgur.com/fq5xNlj)
[Wire Frame 2](http://imgur.com/tTYikxC)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Before project week: planning, Make a client side todo list in react.
Day 1 & 2 api
Day 3 connect the front end
day 4 buffer / styling
day 5 Documentation, styling.
