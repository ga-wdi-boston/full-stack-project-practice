# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I will be building a UI for audio show producers to enter and keep track of their
shows (i.e. description, RSS feeds, actors, etc).  I am often asked in interviews
about a show and it would be nice to have a quick place to refer to (instead of
Evernote).

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

The User should have the ability to log in & log out.
The User should have the ability to select 'Shows' or 'Voice Artists'.
The User should have the ability to view all previously entered show names.
The User should have the ability to enter a previously entered show's data.
The User should have the ability to delete a previous show.
The User should have the ability to add a new show.
The User should have the ability to view all previously entered VA names.
The User should have the ability to enter a previously entered VA's data.
The User should have the ability to delete a previous VA.
The User should have the ability to add a new VA.


## Plan your tables and columns

What tables will you need? What will the columns on the table be?
I will need two tables with a many to many relationship.  One for shows and one
for VAs.  (SEE ERD image for column names).



## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

http://evolutiontalk.com/images/show_entry_erd.png

## Routing

What routes will you need to be able to make the proper request to your API?
shows & voice_artists

## 3rd Party APIs

Do you plan to use any, if so what are they?
I would like to integrate an iTunes podcast API given time.

## Wireframes

Please create a wireframe of your planned front end.

http://evolutiontalk.com/images/1_view.jpeg
http://evolutiontalk.com/images/2_va_entry.jpeg
http://evolutiontalk.com/images/3_show_entry.jpeg
http://evolutiontalk.com/images/4_show_links.jpeg

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

DAY 1 - Create Simple Front End Template to Get Sign-In working
DAY 2 - Create DB structure and Front End Connection (seed data)
DAY 3 - Test DB connections (create, read, update, destroy)
DAY 4 - Enable Front End display of Data
DAY 5 - UI Design
DAY 6 - UI Design
DAY 7 - Test
