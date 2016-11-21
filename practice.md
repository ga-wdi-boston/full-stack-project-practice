# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I want to make an app to help a user track their medication intake. The other day I was helping my girlfriend put together her medications and she got mad at me for forgetting to tell her that she needed to refill one. It would be for people who take lots of different medications and nutritional supplements, especially ones taken on an as needed basis

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

I'm a user and I want to be reminded to refill my prescriptions when I'm almost out so that I never miss a day.

I'm a user and I want to see how often I actually take my as needed meds, so that I can figure out if they're a good solution or not.

I'm a user, and I want to add and delete my meds as they change.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Users:
id, name, password, token

Meds:
id, name, dosage, dosage units, frequency, directions, user_id, med_id, count


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

One user has many meds

## Routing

What routes will you need to be able to make the proper request to your API?

User:
Post -- sign-up
post -- sign-in
patch -- change password
delete -- sign out

Med:
post -- new-med
get -- index
get -- show
patch -- take-med
patch -- edit-med
delete -- delete-med

## 3rd Party APIs

Do you plan to use any, if so what are they?

nope!

## Wireframes

Please create a wireframe of your planned front end.

http://imgur.com/a/WPwk2

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

have a front-end put together by late next week, back end after that, work on apis next, then each model
