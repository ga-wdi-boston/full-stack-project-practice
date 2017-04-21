# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is a jukebox app for customers and establishments (i.e bars, resturants).
Customers get one version of the app that allows them to search and add songs to the bars
queue of upcoming songs (this is what i will be focusing on for project 2) There will also
be a paid version for the establishments that allows them to choose what songs to have
in their jukebox and manage the queue. I have had this idea for a while now, sitting at
places and thinking man it would be cool to be able to pick this places songs and see
what other people are putting up their as well.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a bar customer i would like to be able to search for songs i would like to play
so that i can add them to a queue
As a bar customer i would like to be able to add songs to the bar's queue so that they can be played
As a bar customer i would like to be able to see what song I have specifically added to the queue
so i can keep track of songs i am added
As a bar customer i would like to be able to have my queue refreshed everytime i login
so that i can have a fresh start at each bar.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?
Users
  emails
  passwords
  tokens
Songs
  title
  artist
  queue_id
Queues
  personal
  songs
  user

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

Users -< Queues  Songs >-< Queues  Users  Songs

Users has many queues, queues belong to users
Songs has many queues, queues has many songs
Users and Songs have no reference
## Routing

What routes will you need to be able to make the proper request to your API?
everything except new and edit

## 3rd Party APIs

Do you plan to use any, if so what are they?
Not in this iteration. But in the future a google maps API

## Wireframes

Please create a wireframe of your planned front end.
Do i need to upload pictures?

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Have the backend done by early next week
have the front end hooked in by late next week
have some time to put the finishing touches on it early the next week before the project is due
