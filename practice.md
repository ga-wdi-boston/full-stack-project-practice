# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

Earlier this year I deleted my Facebook account. As an unexpected result, I forgot when everyone's birthday is.

My project idea is to build an app where users can store birthdays for friends and family.

I would use this app and other people who don't have Facebook may have it.


## Write between 3-5 user stories

A. Auth Stories- Functionality
  1. As a user, I want to be able to create an account on the Birthday App with my email as my username.
  2. As a user, I want to be able to create a password associated to my account so that no one else can see my birthdays I created
  3. As a user, I want to be able to sign into the Birthday App with the username and password I created.
  4. As a user, I want to be able to log out of the Birthday App when I am finished so that others using the same computer cannot access the account without my knowledge
B. Auth Stories- User Flow
  1. As a user, when I navigate to the Birthday App homepage, I want to be asked if I have an existing account.
    1.1. As a user, if I select that I don’t have an existing account, I want to be navigated to create an account.
    1.2. As a user, once I have successfully created an account, I want to be navigated to sign in functionality.
    1.3. As a user, if I select that I have an existing account, I want to be navigated to sign in.
  2. As a user, when I log out of the Birthday app, I want to be navigated back to the page where I was asked if I have an existing account.

C. Interface
   1. As a user, when I log into the Birthday App, I want to see if anyone’s birthday is today.
      1.1 Acceptance Criteria
        1.1.1 Display birthday, if birthday is the same date as today’s date:
            1.1.1.1 Today is <name> birthday!
        1.1.2 If nickname doesn’t exist, display first name (surname).
        1.1.3 If more than one birthday is *today*, display the same line again.
        1.1.4 Max return 3 line.
    2. As a user, when I log into the Birthday App, I want to see if anyone has a birthday coming up in the next 30 days.
      2.1 Acceptance Criteria
        2.1.1 Count the number of days in the next 30 days and display that number
          2.1.1.1 You have <number> birthdays coming up!
    3. As a user, I want to be able to click on the number of birthdays coming up and see whose     bday is coming is up so that I can go get gifts if necessary.
      3.1 Acceptance Criteria
        3.1.1 The number should be a hyperlink that, when clicked, displays the first name or nickname of the person’s bday coming up in a modal?
    4. As a user, I want to be able to add a birthday to the Birthday App.
      4.1 Acceptance Criteria
        4.1.1 User should be able to add a bday-fields include
            4.1.1.1 surname- required
            4.1.1.2 family_name- not required
            4.1.1.3 nickname-not required
            4.1.1.4 DOB- required: MM/DD/YYYY
        4.1.2 Form should clear after successful add
   5. As a user, I want to be able to delete or update a birthday from the Birthday App—-Not sure which yet— search first by name? then delete. this could be pretty hard
   6. As a user, I want to see all the bdays I have stored in the app. Not sure if I want to do this one
D. Out of Scope:
  1. Validating if a bday has already been added for the same person aka UI won’t stop the user from adding duplicate bdays


## Plan your tables and columns

Table: Birthdays
Columns: given_name, surname, nickname, dob, user_id

Table: Users
Columns: username, token


## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

One user has many birthdays

## Routing

What routes will you need to be able to make the proper request to your API?

INDEX- show all the bdays? Not sure I want to do this one.
SHOW- show bdays for that day
CREATE
UPDATE
DELETE- unsure if I want to do udpate or delete. I will both if I decide not to do show

## 3rd Party APIs

Do you plan to use any, if so what are they?

I have no plans to use any third party APIs for this project.

## Wireframes

http://imgur.com/a/hHxAj

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

1. Research how to compare the current date versus a birthday in Ruby
2. Authentication Pieces
3. Front end for authentication
3. API SHOW/INDEX
4. Front end for bdays
5. API Create
6. Front end for create
7. API Update/Delete
8. Front end for update/delete
