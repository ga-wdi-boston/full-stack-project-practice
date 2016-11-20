# Full Stack Project Practice

You will be presenting this early next week.  Please have a brief presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

```md
I had fun with the last game, so I decided to do another one.  This game will be
a Word Scramble with Easy, Medium and Hard difficulty choices (based on the
length of the word).  It would be used by anyone who enjoys solving Word Scrambles.
```
## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

```md
As a user I want...
1. the ability to create an account so I can save my game information
2. the ability to login so I can get my game state and pick up where I left off
3. the ability to change my password so my account is more secure
4. an intuitive interface so I know what I'm expected to do
5. the ability to choose my difficulty level so I can make the game harder or easier
```

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

```md
I'll be making use of the User table to grab the user's email address.  I'll also
be creating two of my own tables:

Table: Words
Columns: id (SERIAL), word (VARCHAR), difficulty (VARCHAR), level (INTEGER)

Table: Completed_Words
Columns: id (SERIAL), user_id (ref to users.id), word_id (ref to words.id)
```

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

```md
My ERD can be seen here:
https://www.lucidchart.com/invitations/accept/9f4dfced-5b25-44ae-8709-9977224c42aa
```

## Routing

What routes will you need to be able to make the proper request to your API?

```md
The routes I plan to use can be seen here:
https://www.lucidchart.com/invitations/accept/08f7e1cd-c3b6-4278-a4a2-65e4d4ab89b6

I'm still trying to figure out how to incorporate the PATCH route into the game.
```

## 3rd Party APIs

Do you plan to use any, if so what are they?

```md
No, I don't plan on using any 3rd party APIs.
```

## Wireframes

Please create a wireframe of your planned front end.

```md
My wireframes can be seen here:
https://www.lucidchart.com/invitations/accept/bd952fbf-1278-4c78-bda6-d8b382272de8

Each tab shows a different view I'd like to show the user.
```

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

```md
UI and auth API - 1 day
Game API - 1 day
Game Logic - 1 day
Testing, bug fixes, general improvements - 1 day
```
