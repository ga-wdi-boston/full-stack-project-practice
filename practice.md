# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?
My idea is to create a Bucket List application where user can log things they
want to do before they die. I came up with it because ever since I was young I've
liked having life goals and getting to check them off. I thought it would be fun to
have an application where users could go to log such things and update them over time.
I feel like every person could use this bucket list app, it only requires someone who
has life goals!

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user, I want to be able to create an account so that I can log in to the application.

As a user, when I log into the application, I want to be able to create a new bucket list item
and type a description so that I can document my goal.

As a user, I want to be able to edit my bucket list item so that I can change the
content if I desire.

As a user, I want to be able to delete a bucket list item so that I can remove
items that I am no longer interested in.

As a user, I want there to be categories for my bucket list items so that I can
more easily organize them.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Table 1 - Bucket List Item List
Columns - id (int - primary key), description (string), category_key (foreign), status_key (foreign), date_completed (date)

Table 2 - Category List
Columns - id (int - primary key), category_name (string)

Table 3 - Status List
Columns - id (int - primary key), status name (string)

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

[ERD](http://imgur.com/a/vGWsj)


## Routing

What routes will you need to be able to make the proper request to your API?

-Users
-List

## 3rd Party APIs

Do you plan to use any, if so what are they?

I do not plan to use any.

## Wireframes

Please create a wireframe of your planned front end.

[Wireframes](http://imgur.com/a/Gpa2R)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Finalize initial user stories and wireframes by next Wednesday.
Thursday - Create initial web page with HTML and CSS to mimic wireframes. Confirm with consultant that ERD data models work.
Build models and migrations for data. Test API endpoints.
Friday - Begin work on front end connections to back end. Ensure all are working. Complete first deploy.
Monday - Add more complex CSS and Handlebars to front end.
Tuesday - Complete documentation.
