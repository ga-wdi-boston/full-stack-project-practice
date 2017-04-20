# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project will be a hangman game.
My wife gave me the idea after playing my tic-tac-toe game.
Why? Are you kidding me?  To keep maama happy.
Anyone that is sick of tic-tac-toe.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

1. as a future player I would like to signup so I could play hangman at a later time.
2. as a signed up player I would like to sign in to play a hangman game now.
3. as a signed in player, I would like to change my password so I don't get hacked.
4. as a signed in player, I would like to play the game so I am selecting play.
5. as a great hangman player, I would like to see my playing record so I will select show stats.
6. as a frustrated hangman player, I would like to have a drink with friends so I am selecting the log out

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

users
  id
  email
  password
  token

games
  id
  player_id
  word_id
  game_status
  game_outcome

words
  id
  word_content
  content_level

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

see erd.jpg

## Routing

What routes will you need to be able to make the proper request to your API?

resources :users, except: [:new, :edit]
resources :games, except: [:new, :edit, :destroy]

## 3rd Party APIs

Do you plan to use any, if so what are they?

Not at this point, but maybe if time permits

## Wireframes

Please create a wireframe of your planned front end.

see wireframe.jpg

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

1 day html and css
1 day user functions
1 day game functions
1 day backend work

this timetable includes time for coding and debugging
