# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

A deck builder for a card game that will determine which card combinations will work and what they will do.

## Write between 3-5 user stories

Create User / Log in?
Be able to get a random selection of cards
Be able to enter card combos and get their results
Get all combinations given a selection of cards
Create a deck
Save a deck

## Plan your tables and columns

Tables: Cards | Combinations | Available

## Create an ERD (entity relationship diagram)

Get All Cards => server => cardsController => cardsModel => cardsController => server => frontEnd
Get Deck => server => deckController => deckModel => deckController => server => frontEnd
get combinations => server => comboController => comboModel => comboController => server => frontEnd

## Routing

/login /logout?
/cards: list of all cards
/decks: list of user made decks
/combos: list of card combinations

## 3rd Party APIs

Do you plan to use any, if so what are they?

## Wireframes

In this repo as wireframe.png

## Timetable

DAY 1:
Basic setup of font and backend
DAY 2:
Implement app functions
Day 3: Finish and cleanup
