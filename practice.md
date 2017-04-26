# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

Honeybee Hive Management.
I'm a hobbyist beekeeper and need to perform hive inspections during peak season at least
once a week. I have a note book where I make notes on my observations. It would
be nice to be able to move these observations online.  This application could
be used by any hobbyist beekeeper.

For MVP I will implement the ability to create a hive and enter details about
that hive.

Stretch goal will be to create a log that will contain observations where
the user is allow to choose from preloaded 'observations'.  The ability to enter
additonal observations as text via micro-phone type API. Potentially add images
from observations.

## Write between 3-5 user stories
The normal signup/signin/signout/change password stories

Story: As a User, I want to add a hive, So that I can manage it.
Story: As a User, I want to add what type of queen the hive has, So that I know
what type of queen this have has.
Story: As a User, I want to add the year the queen was reared, So that I know
how old she is.
Story: As a User, I want my know how many brood supers per hive, So that I can
plan on replacing frames for my IPM.

Other User Stories:
Story: As a User, I want to add a date that my drone comb was added, So that I
can remove it before they hatch.
Story: As a User, I want to be sent an alerted when I need to remove the drone
comb, So that I don't forget.
Story: As a User, I want to know how many frames of honey I harvested, so that
I can know how productive a hive is.
Story: As a User, I want to record observations from a hive inspection, So that
I can track any issues.
Story: As a User, I want to record if any eggs were observed, So that I know
when the queen was last laying.
Story As A User, I want to record if any swarm cells were observerd, So that I
can preventing swarming.
Story As A User, I want to record how many frames of brood, So that I know if
I need to add more supers.
Story As A User, I want to record if I saw any hive beetles, So that I can
treat for them.
Story As A User, I want to record if I saw any honey bee diseases, So that I can
manage them.
Story As A User, I want to know when I added a honey super, So that I can add
another, So that I know the bees have enough room.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?
Standard user tables.
Hive Table:
queen_type
frames_harvested
honey_supers
brood_supers

Queen Table:
Russian
Italian
Buckfast

Observation Table:
eggs_observerd
swarm_cells
frames_of_brood
hive_beetles
diseases
drone_comb_installed

Disease Table:
Fool Brood
Chalk Brood

Honey Super Table:
Medium
Deep
Shallow


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

http://i.imgur.com/sGyoD9N.png

## Routing

What routes will you need to be able to make the proper request to your API?

## 3rd Party APIs

Do you plan to use any, if so what are they?

Not Sure Yet.

## Wireframes

Please create a wireframe of your planned front end.

Not sure yet...but want to be able to select from dropdown for certain items.
Would the choices be stored in a DB table and set to the client to be displayed?

http://i.imgur.com/HLqrOfv.jpg

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Identify what is needed for MVP.
Determine what DB tables are required and relationships
Build MVP UI for sign up/in/out/password
Build out rails scaffold for new tables to support features.
Implement routes and controllers along with curl scripts for support features
Build MVP UI for adding hive and hive supers.
Refactor basic UI to improve appearance.
