# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?
My project is a chore tracker designed for use in shared live-in spaces. Frequently, menial tasks in shared spaces go undone. Roommates passively push off the responsibilities until someone can't take it anymore and they complete the task. My app work in accordance with the below wireframe. A roommate notices a chore and adds it. It gets assigned to whoever has the least amount of chores. This way it is unbiased. In an ideal world, I will make it so you can also rate difficulty and the difficulty level will be compiled and chores will be assigned based off of who has the least amount of work. For example Roommate1 has to take out the trash which as a rating of 1 and clean the toilet which has a rating of 5. Roomate2 has to clean that weird pink line from the shower which is three. So, R1 has a responsibility level of 6 while R2 has one of 3. So, vaccuming the kitchen is a 2 will go to R2.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.
A user will be able to add a chore
A user will be able to mark a chore as complete
A user will be able to see everyone else chores
A user will get chores assigned to them

## Plan your tables and columns

Chores and User tables.
Chores will have columns of difficulty, due-date and the chore itself.
User will have a column for name and what they have assigned to them

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

http://framebox.org/ZCbT

## Routing

What routes will you need to be able to make the proper request to your API?

get chore (index)
get chore/:id (show)
post chore (c)
patch chore (u)
delete chore (d)

get user
post user (c)
patch user (u)
delete user (d)

BONUS
get otherLocation
post otherLocation (c)
patch otherLocation (u)
delete otherLocation (d)

## 3rd Party APIs

As of right now I only plan to use Ruby

## Wireframes

Please create a wireframe of your planned front end.
http://framebox.org/ZCbT

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Create all Rails related details (models, controllers, routes)
Make chores and users database
Get a basic front end
Get login information working
Get functionality of front end working with back end
BONUS:
Make it so multiple users can change their locations
