# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

http://top50.topsters.net/
Basically this, but with movies and dumbed waaaay down.
I'd like to have it be a list of your favorite movies with the ability to return stats about your favorite movies (specifically, the year they were released, who directed them)

People would use it to tell other people on the internet with quantitative precision that your taste in music is terrible.

People trying to show off their taste in film on the internet.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a pretentious cinephile, I really need to list my favorite movies and show you how much better my taste in film is than yours.

As a data-driven individual, I need to be able to break down when my favorite movies were made and who made them.

As a bigshot hollywood producer, I need to see which directors, genres and periods have produced the most popular films

As a general assembly developer, I need to create a product which will pass muster.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Films
  Title
  Director
  Year
  Genre

Users (I imagine this is prebuilt, but were I working from scratch, this would be how I'd do it)
  Username
  Email address
  Password

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

http://imgur.com/gPUrPmF

## Routing

What routes will you need to be able to make the proper request to your API?

I imagine the routes used in this project will mimic the routes used by the sample API. In authentication, the routes seem pre-defined. For the actual app API methods, my plan is to ape the sample APIs using

resources :movies, only: %i[index show destroy update]

to implement the same CRUD functionality.

## 3rd Party APIs

Do you plan to use any, if so what are they?

I do not.

## Wireframes

Please create a wireframe of your planned front end.

http://imgur.com/LvmZ3xS

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

As it stands, I have begun to work on planning and building out my project. I am using the checklist written into the project requirements. Beyond getting a primitive front end built out this weekend, I have no set in stone time table. I will simply move forward towards the goal one strategic objective at a time without creating overly limiting timetables in advance.
