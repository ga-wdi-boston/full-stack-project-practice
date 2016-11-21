# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

A digital bookshelf. I want a way to search the list of all the books I've read, so that I don't accidentally buy or borrow the same book twice. I would definitely use it, but I also think that other people who are always looking for a new book to read would use it as well.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

* As a user I want to be able to search my list of books.
* As a user, I want to be able to add new books that I've read to my list.
* As a user, I want to be able to remember how much I enjoyed reading the books that are on my list, for future reccomendations.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Books: titile, rating, isbn
Authors: first name, last name, alias first name, alias last name
Publisher: name
Imprints: name of imprint, genre of book

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

a book has many authors
an author has many books
a book belongs to one publisher
a publisher has many authors
an author has many publishers

## Routing

What routes will you need to be able to make the proper request to your API?

* user - create/post, update/patch, delete
* book - get one, get all, create, update, delete
* author - get one, get all, create, update, delete
* publisher - get one, get all, create, update, delete
* rating - get one, get all, create, update, delete

## 3rd Party APIs

Do you plan to use any, if so what are they?

* Open Library Books API
* Goodreads API

## Wireframes

Please create a wireframe of your planned front end.


## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

6 hours - breaking down user stories
8 hours - set up API
4 hours - design front end asthetics
8 hours - figure out and implement connects between tables and get proper returns
8 hours - fixing bugs and troubleshooting
