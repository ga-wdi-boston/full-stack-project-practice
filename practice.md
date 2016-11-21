# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I came up with a vote app. To vote (+1 or -1) for something written or a
picture that you like. Possibly like to show a whole bunch of quotes, or pictures
and people would like them, similar to how people use twitter or an app like that.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

I can log in, I can see a whole bunch of quotes, something written, or pictures,
and I press a button to like the ones, which will add to the likes on that post.

As a user, I can see posts.

As a user, I can vote on posts.
## Plan your tables and columns

What tables will you need? What will the columns on the table be?

people with accounts:
their name or username.

content:
author, description


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

| content  | -+---------+-|users|
one user likes many posts. Post can be associated with multiple users by being liked by them.

## Routing

What routes will you need to be able to make the proper request to your API?
GET /content in order to show content
POST content in order to post a new image file or quote or something.
PATCH /content/id in order to update an image/quote etc.
DELETE /content/id in order to delete a image/quote etc.



## 3rd Party APIs

Do you plan to use any, if so what are they?

Don't know what I would use other than the rails api template that was given so I will
use that. https://github.com/ga-wdi-boston/rails-api-template

## Wireframes

Please create a wireframe of your planned front end.

https://www.gliffy.com/go/share/skqce6o7jxaw7gs4ihy1
or
http://imgur.com/xDn7fZR

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan

try to create the basic page layout first with html and css.
commit upon new working features, often as some feature changes or works.
Deploy often.
then go into detail thinking about what data that I need and how I will store it.
make a repository for the front end and clone the back end one so that they are separate.
Make sure both have read me files.
Check to make sure my ERD makes sense with a consultant
begin to create it upon their thumbs up.
create upon the rails template for representing the data with models and migrations.
create the back end first to help with diagnosing problems with the front-end.
Create font end with javascript, jquery and ajax.
