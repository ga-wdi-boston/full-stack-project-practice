# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I would like to develop a website for borrowing used books, cds and records.
Users can sign in and select books, cds and records from other users. Users can
decide on the length of the rental and loctaion to exchange resource.

I exchange books and cds with friends all the time. Sometimes though, I never
get my stuff back. I've had the idea of keeping a spreadsheet among us
friends so that we don't lose each others' books and cds, nor do we forget who
we borrowed it from in the first place.

Anyone with resource can use this website. Some of us would like to hold on to
our favorite books, but at the same time borrow it to friends so they don't
have to buy it if they don't want to own it.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user, I can
- create an account
- sign in
- change password
- sign out
- Add resources (books, cds or records)
- Choose a resource from another user
<!-- - Mark my resources available/unavailable -->
- Decide the duration of rental.
- Choose a meeting point for exchange.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

There will be five tables, two of them will be master tables.
- The users table will contain columns - given_name, last_name, username,
  password(secretkey), pincode.
- The resources table will contain userId(Foriegnkey from users table), name,
  type(ForeignKey from resourceTypes table)
- The resourceTypes table will be a master table with reource types(books, cds
  and records).
- The requests table will hold columns for sentby(ForeignKey from users table),
  sentTo(ForeignKey from users table), status(ForeignKey from status table),
  duration, dropofflocation, pickuplocation, requesteditem(ForeignKey from
  resources table), receivingitem(ForeignKey from resources table)
- The status table will be a master table with columns pending accepted and
  rejected.

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

<!-- pending -->

## Routing

What routes will you need to be able to make the proper request to your API?

post <signup>
get <signin>
patch <change password>
delete <signout>
get <resources>
post <add resources>
post <reserve resources>
post <accept resources>
patch <release resource>
patch <update resource>

## 3rd Party APIs

Do you plan to use any, if so what are they?

I do not plan to use any third party APIs now.

## Wireframes

Please create a wireframe of your planned front end.

<!-- pending -->

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Design the database.
Design the APIs
Design the front end
User testing
