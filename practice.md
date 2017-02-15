# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

My idea is an animal sighting log, for users to keep a record of animals they encounter in nature, on hikes, etc.  I came up with the idea because I like animals and biology and was trying to think of an app that is simple enough that I don't get overwhelmed, but still is interesting.  I think anyone who enjoys nature and animals would enjoy using this app.

## Write between 3-5 user stories

As a user, I want to create an account so that I can sign in and view all of my posts.
As a user, I want to be able to make a post so that I can have a log of all the animals I've seen.
As a user, I want to be able to have a list of my favorite posts, so that I can quickly view my most memorable sightings.
As a user, I want to be able to view posts by animal type, so I can organize my posts.
As a user, if I don't like a post I made I want to be able to delete it.

## Plan your tables and columns

Users:
- ID (primary serial key)
- first name (string)
- last name (string)
- email (string)

Posts:
- ID (primaty serial key)
- ID of user who created the post (integer)
- animal type (string)
- species (string)
- time/date seen (timestamp)
- location seen (string)
- description (string)
- link to image (string)
Favorites:
A user would have a list of their favorite posts (unsure yet if it would be their favorites of their own posts, or favorites of all user's posts.  The latter is preferable but im not sure how hard that is to implement.)

Animal_Type:
This table would be constant, one column would be ID, and the other would be animal type (mammal, fish, reptile, bird, amphibian, invertebrate).  Im also unsure of if this table is needed.


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

A user has many posts
An animal type has many posts
A user has many animal types through posts
An animal type has many users through posts

A user has many favorites
A post can be on many user's favorites (but do we want this to be a many-to-many? A user would want to see their favorites, but why would we need to show which user's favorites list each post is on?)


## Routing

resources :users, except: [:new, :edit]
resources :animal_types, only: [:index, :show]
resources :posts, except: [:new, :edit]

## 3rd Party APIs

As of now, I do not plan on using 3rd party APIs

## Wireframes

http://imgur.com/a/HnXQW

## Timetable

- Set up basic html
- Set up user auth (sign up, sign in, change password, sign out)
- Set up api for creating a new post
- Make serializer return proper JSON for getting posts
  - Parse JSON to display it on the html
- Add animal types table and confirm relationships
- Add favorites join table
- Update html and add styling
