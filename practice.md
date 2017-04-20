# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?
My project idea is a SPA where a user can log in and type something in to store it.
It's called Hopes N Dreams and will have a form for the user to add in the following entries:

What (there hopes/dreams are, so, a "title"),
What's the stopper (why ($, time, convenience))
Backstory
Special Notes

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

1.  The user will only be able to log in, log out upon first navigating to the site
  but after signing in, will be able to sign out or change password or use the
  site functionality once signed-in.

2.  The user will be able to create entries for their "own" list of hopes
  and dreams.

3.  The user will be able to view all entries or one entry in their "own" list of
  hopes and dreams.

4.  The user will be able to update one entry at a time from their "own" list of
  hopes and dreams.

5.  The user will be able to check off entries and retrieve completed entries
   from their "own" list of hopes and dreams.

6.  The user will be able to delete entries and retrieve the deleted entries
  from their "own" list of hopes and dreams.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

I will need a table for users with the following columns:
 username
 email
 password
 token
 last-logged-in timestamp

I will need a table for the users' hopes and dreams with the following columns:
 title of hope/dream
 backstory of hope/dream (optional)
 preventers of hope/dream
 update/
 progress
 deleted flag
 username_id (references users table)

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

http://imgur.com/8BPw6qv

## Routing

What routes will you need to be able to make the proper request to your API?
create, index, show, update, destroy but I'm not letting the user destroy at
this point.

## 3rd Party APIs

Do you plan to use any, if so what are they?
I am not sure yet.  I *think* it is a document or set of standards to make
integration with another site easier.

## Wireframes

Please create a wireframe of your planned front end.

http://imgur.com/a/G4Gr3

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

4/25  begin building api
4/26  continue building api
4/27  begin building front end
4/28  continue building front end
4/29  make sure front end/back end are working
4/30  finish/polish front end
5/1   testing, edit
5/2   testing
5/3   present
