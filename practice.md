# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is an ambient sound mixer. I wanted to create something that I'd actually
use. I use sound mixers and music to concentrate and sleep a lot a I know there are others
that do the same.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user I can adjust the volumes so that I may mute and unmute sounds
As a user I can save my preset so that I may retrieve them later
As a user I can change the name of my preset


## Plan your tables and columns

What tables will you need? What will the columns on the table be?

I will need a user table to contain general user data and a table of sound presets. The table of sound
presets will have the the volume values of each track with a name that will be chosen
by the user. There maybe a table for presets to begin onReady.

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

one to many - one user to many presets

## Routing

What routes will you need to be able to make the proper request to your API?

I will need the usual user routes. For the  presets I will need to make routes for everything exept new and edit.
get '/presets' => 'presets#index'
OR
resources :presets, except: [:new, :edit]

## 3rd Party APIs

Do you plan to use any, if so what are they?

I may need to get my audio from outside sources. I am unsure how much audio I can use.
I also had the idea of connecting to a music api to also play music with these sounds.

## Wireframes

Please create a wireframe of your planned front end.

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

1. connect sound audio to page and have volume sliders active
2. check and see if it can be duplicated 4+ times
3. create user and sounds tables
4. work on user ajax
5. work on get and post for sound presets
6. patch for preset names
7. html & css

bonus
add playlist audio to be played over sounds
