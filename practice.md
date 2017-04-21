# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

Project idea is a web app for a virtual food pantry for the home or office.
It allows the user to log everything in their pantry.

Why: The goal is for the user to be able to see what they have in their pantry
at anytime. This would be useful when food or supply shopping to know:
    1) if an item is in the pantry
    2) how much of an item is in the pantry
    3) if the item is still fresh/not expired

How: Came across the idea when shopping for food. Forgot if I had certain items,
and for items I did have, was not sure they were still fresh.

Audience: Any user that does food/supply shopping.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

1.  As a user, I would like to keep track of an item in the pantry. The item can
    be perishable or non-perishable.
1.  As a user, I would be able log details about the pantry item such as
    i) quantity
    ii) date purchased
    iii) item type
    iv) price
1.  As a user, I can create a virtual pantry that will keep track of all my
  pantry items.
1.  As a user, I can update items already in my pantry.
1.  As a user, I can have multiple pantries.
1.  As a user, I can share my pantry with others as read-only. (stretch?)
1.  As a user, I can get a recipe recommendation based on my pantry contents. (stretch?)
1.  As a user, I can add other users to a friends list. (stretch?)


## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Users Table
  -user id
  -email
  -password

Friends Table (stretch?)
  -friend list id
  -user_id (fk) [too keep things simple, a user can have only 1 friends list]
  -friends

Pantries Table
  -pantry id
  -user_id (fk) [1 user can have many pantries?? ]
  -shared_with (other user IDs)


Items Table
  -item id
  -pantry_id (fk) [many items in 1 pantry]
  -perishable (yes/no)
  -item name
  -item quantity (when purchased)
  -item purchase date
  -item expiration/best by
  -item price
  -item category (veg, meat, dairy, etc.)


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

1 User to Many Pantries
1 Pantry to Many Items


## Routing

What routes will you need to be able to make the proper request to your API?

Users routing:
  sign-in
  sign-out
  change password
  sign-up

Pantries routing:
  create pantry
  show all pantries
  show specific pantry
  update pantry
  delete pantry

Items routing:
  Create item
  show all items
  show specific item
  update item
  delete item

## 3rd Party APIs

Do you plan to use any, if so what are they?
  N/A at the moment.

## Wireframes

Please create a wireframe of your planned front end.

Initial wireframe link: http://imgur.com/a/m4QAB

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.
  1 Day - HTML shell
  1 Day - database & tables design/creation
  1 Day - Rails API
  1 Day - backend/pantry logic handling
  2 Days - Front-end to back-end integration
  1 Day - styling
  1 Day - debugging
  .5 Day - deploy testing
  .5 Day - README
