# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I plan to make a New Years Resolution list. The client will be able to set those
resolutions on a list and write and store a comment everytime he achieve one of
those goals. Every one can use it. I realized that I always make this kind of
list, but never stick to them and easily forget my goals. This app could be a
good way to stick to ideas and make them work all year round.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

- Be able to create an account and access its own info.
- Create and update a list of wishes.
- Mark a wish accomplished and comment on it.
- Access those comments to remember the feeling of achieving a goal.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

A users table, with basic info like: given_name, surname, born_on, email.
A wish table with: wishes(goals), accomplishment(true/false), comment

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

It is going to be a one to one relationship between the user credentials and
its own list. (not sure if this answers the question?)

## Routing

What routes will you need to be able to make the proper request to your API?

All the CRUD routes (Create, Read, Update and Destroy) are going to be used for
both authentication and data exchange with client and server.

## 3rd Party APIs

Do you plan to use any, if so what are they?

I believe I'll create the whole API for this project.

## Wireframes

Please create a wireframe of your planned front end.

http://imgur.com/zOdLFE6

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

2 days - create API (routes, controller, models and tables interaction)
2 days - work on front end
1 day - debbug
