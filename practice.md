# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is making a Japanese/English language flashcard web app.
I came up with it because this app would be a good starting point for a
Japanese/English dictionary app that I would like to build in the future. Before
joining GA, I found a set of data made public that consists of Japanese words/phrases matched with definitions in English and Japanese and imported it
into a database I built in MySQL, but had difficulty representing Japanese unicode characters. I decided to take this opportunity to work on a project that allows
me to work on overcoming this difficulty so that I could apply what I learn onto
my future project.

My flashcard web app will be used by people who would like to memorize Japanese
words and phrases via repetition.



## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

1. As a user, I want to sign up so that I can sign in
2. As a user, I want to sign in so that I can create new flashcards and access them for studying.
3. As a user, I want to change my password so that
4. As a user, I want to create a new flashcard with a definition so that I can study more words.
5. As a user, I want to view all flashcards that I made so that I can study words.
6. As a user, I want the definitions to be hidden at first but shown when I click on each card so that I can practice defining words.
7. As a user, I want to randomize the order of words so that I can memorize words
without having to rely on patterns.
8. As a user, I want to search for a word I’ve created so that I can make edits to the word and definition.
9. As a user, I want to make edits to a flashcard so that I have the correct words and definitions.
10. As a user, I want to delete flashcards so that I so that I can have only the words I need to study.
11. As a user, I want to add other users' flashcards into my own deck so that I can study more words.
12. As a user, I want to sign out so that I can have only the words I need to study.


## Plan your tables and columns

What tables will you need? What will the columns on the table be?

#### users
| Column       |     Type     |
|--------------|--------------|
| id           | primary key  |
| username     | text         |
| password     | text         |

#### authors
| Column       |     Type     |
|--------------|--------------|
| id           | primary key  |
| given_name   | text         |
| family_name  | text         |


#### flashcards
| Column       |     Type     |
|--------------|--------------|
| id           | primary key  |
| word         | text         |
| definition   | text         |
| author_id    | foreign key  |


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

The relationship between authors and words will be one to many.
An author has many flashcards, and a flashcard belongs to an author.

(authors)-|-----<(flashcards)


If I have time, I may make it so that authors can get other users' flashcards.
This would involve a many to many relationship implemented through a join table,
decks.

one to many between authors and cards:
  - an author has many cards
  - a card belongs to an author

many to many between authors and cards, through decks:
  - an author has access to many cards through (other users') deck
  - a card has many authors through deck

## Routing

What routes will you need to be able to make the proper request to your API?

#### Users
| Verb   | URI Pattern          | Controller#Action |
|--------|----------------------|-------------------|
| POST   | /sign-up             | users#signup      |
| POST   | /sign-in             | users#signin      |
| DELETE | /sign-out/:id        | users#signout     |
| PATCH  | /change-password/:id | users#changepw    |

- post '/sign-up' => 'users#signup'
- post '/sign-in' => 'users#signin'
- delete '/sign-out/:id' => 'users#signout'
- patch '/change-password/:id' => 'users#changepw'

#### Words
| Verb   | URI Pattern | Controller#Action |
|--------|-------------|-------------------|
| GET    | /words      | words#index       |
| POST   | /words      | words#create      |
| GET    | /words/:id  | words#show        |
| PATCH  | /words/:id  | words#update      |
| DELETE | /words/:id  | words#destroy     |

- get '/flashcards/' => 'flashcards#index'
- post '/flashcards/' => 'flashcards#create'
- get '/flashcards/:id' => 'flashcards#show'
- patch '/flashcards/:id' => 'flashcards#update'
- delete 'flashcards/:id' => 'flashcards#destroy'


## 3rd Party APIs

Do you plan to use any, if so what are they?

At the moment, I do not play to use 3rd party APIs.

## Wireframes

Please create a wireframe of your planned front end.

![Wireframe]https://drive.google.com/file/d/0B085YpY7Y_tmdV9JbjlpVU5haXNDYzh6NDBZb2dPbndzb0Jz/view?usp=sharing

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

1. Create 2 repos on GitHub, add READMEs to both
2. Build simple HTML/CSS based on wireframe
3. Build user-authentication API
4. Build database (and seed data)
5. Build flashcard API
6. Build front-end with Javascript to communicate with API
7. Add content in the README files
8. Add extra CSS/jQuery styling features if time allows
