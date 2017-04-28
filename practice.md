# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I was thinking of making a to do list that will consistently send reminders.  It will be able to also scan your email and suggest things to put on your to do list.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user, I want to be able to sign up
As a user, I want to be able to log in/log out
As a user, I want to be emailed when a due date is close
As a user, I want to be able to get reminders on a preset basis until it is checked off the list


## Plan your tables and columns

What tables will you need? What will the columns on the table be?
table: user
column: name
column: age
column: email

table:
column: tasks
column: due date
column: reminder frequency


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

I don't have the exact diagram planned out yet but it will most likely be one to many

## Routing

What routes will you need to be able to make the proper request to your API?

+post '/sign-up' => 'users#signup'
 +post '/sign-in' => 'users#signin'
 +delete '/sign-out/:id' => 'users#signout'
 +patch '/task-update/:id' => 'users#tasks'
 +resources :users, only: %i[index show]
 +resources :tasks, only: %i[index show destroy update create]

## 3rd Party APIs

Do you plan to use any, if so what are they?

I'm not sure yet

## Wireframes

Please create a wireframe of your planned front end.

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

My goal is to start planning this weekend, creating a wireframe, and figuring out what APIs if any I will use.
