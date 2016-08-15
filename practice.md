# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is to create a programmable drum sequencer app.  This will
playback the rhythmic patterns the user created and will allow the
user to save these patterns to be recalled whenever a user is signed in.

My first thoughts about a web-based sequencer date back to before I became a
developer.  When practicing on a guitar, I wished I was able to access a drum
machine through my computer on the fly to program or load up drum beats to practice
along to.  Using actual recording or playback software usually requires a user
to close all other programs, or the program uses too many system resources to
be able to do anything else on the computer simultaneously. Also, a user's audio
program will usually be dedicated to a particular computer, so a user would be
unable to create these drum beats on any other computer.
Online metronomes are available, but the sound quality is usually poor.
I believe that this device would be welcome to any practicing musician with web
access who wants to create drum rhythm patterns quickly and easily.  I also think
that a broader audience of the public would enjoy this app for entertainment
purposes.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

User stories:
-I want an app that allows me to quickly and easily create drum beats.
-It should have an adjustable tempo meter.
-This drum machine should be able to store my rhythm patterns, and after
signing in, I should be able to call any of those patterns up.
-Ideally, I want to be able to have at least two of my saved patterns stored
that I can choose from during playback.
-I need this to keep time as accurately as possible!
-I want to be able to share my drum beats with other users.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?
I will need a table for Users: user ID, email, name.
I will need a table for Patterns: drum pattern id, drum pattern name,
tempo.
A join table for any user and any drum patterns.

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).  There will be a many-to-many relationship
because the user will be able to access other people's beats.
http://imgur.com/a/7nN0I

## Routing

What routes will you need to be able to make the proper request to your API?
The routes will be between users and rhythm patterns.

## 3rd Party APIs

Do you plan to use any, if so what are they?
If I time after completing the requirements, I may use the Web Audio API
to record new audio from the created beats and email it to the user.  The
Web Audio API also allows for better sound manipulation possibilities.  It is more
challenging to use than the HTML5 audio tags I am currently using for this project.

## Wireframes

Please create a wireframe of your planned front end.
http://imgur.com/a/iRCxP

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.
I will complete the sequencer programming as quickly as possible so that I'm able
to design the back end.  The tempo and playback could be the most challenging
part of the front end of this program, so I will be researching that after building
and storing each drum as an array of sounds. 
