# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?
My idea, which I hope to also improve on for my final project, is to build out a
Wine Cellar Tracking application.

## Write between 3-5 user stories
As a user, I would want to register for a new acccount.
As a user, I would want to be able to sign in and sign out.
As a user, I would want to change my password.
As a user, I would like to CREATE a new listing for a bottle of wine.
As a user, I would like to READ a complete listing of my wine cellar.
As a user, I would like to READ a listing of my wine cellar that meets certains conditions.As a user, I would like to UPDATE an existing listing for a bottle of wine when I buy more of the same wine.
As a user, I would like to DELETE a bottle of wine when I drink the bottle in my cellar.
As a user, I would like to give a rating to a bottle of wine upon DELETING it from my cellar.



We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

## Plan your tables and columns
What tables will you need? What will the columns on the table be?
USER TABLE
user_id (PK)
user_first_name
user_last_name
user_email

PASSWORD TABLE:
password_id (pk)
user_id (FK)
password

WINE TABLE
wine_id (PK)
user_id {FK)}
producer (Joel Gott)
type (Zinfandel)
year (2013)
Country (USA)
Region (Sonoma)

SELLER TABLE
seller_id (PK)
user_id {FK}
name
phone_number
email
price
date_of_purchase

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).
There is a 1:1 relationship between USER and PASSWORD
There is a 0:N replationship between USER and WINE
There is a 0:N replationship between USER and SELLER. 

## Routing

What routes will you need to be able to make the proper request to your API?
I plan to use the following for my user stories. [:index, :show, :create, :update, :destroy]

## 3rd Party APIs

Do you plan to use any, if so what are they?
Not sure at this point, but doubtful I will try to take this on for project 2.

## Wireframes

Please create a wireframe of your planned front end.
https://imgur.com/a/To9FL


## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.
I plan to start the client side this weekend and mock up the front end to give me
sufficient time to work on all the new back end and RAIL material mid next week.
I know this will be very challenging for me to complete given that the first project
took me a massive amount of time. So for now:

Sat and Sunday and Monday planning out a rough front end.
Tuesday: Start planning out hte RAILS components.
Thursday - start project.
