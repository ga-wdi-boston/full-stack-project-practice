# Full Stack Project Practice

You will be presenting this early next week. Please have a brief presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I am looking to create an application that will show and store food/wine
pairings.  I enjoy food and wine and thought of the one-to-many table
relationship while doing the RAILS-API-ONE-TO-MANY demo/code along/lab.

Anyone passionate about wine including foodies, wineies, and sommeliers would
use the application which would have endless options for scalability and
enhancements such as enhanced searching and social media capabilities.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

1.  As an user, I want to sign up, so that I can use the application.
2.  As an user, I want to sign in, so that I can login and use the application.
3.  As an user, I want to change a password, so that I can protect my login
     credentials.
4.  As an user, I want to sign out, so that I can sign out of the application.
5.  As an user, I want to be able to log a new food/wine pairing to the food/wine
     database.
6.  As an user, I want to play multiple games one at a time, so that I can have
    fun.
7.  As an user, I want to sign in again so that I can use the application if I
     typed in an incorrect password.
8.  As an user, I want to sign up again so that I can use the application if I
     typed in 2 different passwords at sign up.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

`User Authentication`:
  - User ID
  - Credentials
      - Email
      - Password
      - Password Confirmation
  - User Token (to be sent as authentication to Food/Wine engine)

`Foods` table:
  - Category (Beef)

`Wines` table:
  - Color (Red/White)
  - Country (USA, Italy)
  - State_Region (Oregon, Tuscany)
  - Variety (Pinot Noir, Merlot)
  - Vintage (2012, 2013)
  - Producer (Dundee Hills, Castello di Ama)
  - Comments (open text form)

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, etc).

https://imgur.com/gallery/ydVIS

## Routing

What routes will you need to be able to make the proper request to your API?

post '/sign-up' => 'users#signup'
post '/sign-in' => 'users#signin'
delete '/sign-out/:id' => 'users#signout'
patch '/change-password/:id' => 'users#changepw'
resources :users, only: [:index, :show]
resources :foods, except: [:new, :edit]
resources :wines, except: [:new, :edit]

## 3rd Party APIs

Do you plan to use any, if so what are they?

Not at this time due to the time constraints for this project but I may research
this for a later project.

## Wireframes

Please create a wireframe of your planned front end.

https://imgur.com/gallery/6qUV3

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Wed Apr 19  - Review Full Stack API project requirements
               https://github.com/ga-wdi-boston/full-stack-project

Thur Apr 20 - Review Full Stack API project practice (scoping and
               brainstorming practice)
               https://github.com/ga-wdi-boston/full-stack-project-practice

               User stories, wireframes, ERD, tables and their structures,
               initial project schedule

            - Review project repo templates:
                Project-api - USE RAILS-API-TEMPLATE
                  https://github.com/ga-wdi-boston/rails-api-template
                Project-client - USE BROWSER-TEMPLATE
                  https://github.com/ga-wdi-boston/browser-template

Fri Apr 21 - Sun Apr 23 - OFF

Mon Apr 24  - Test authentication built-ins from RAILS-API-TEMPLATE
            - Design API backend calls for `Foods` and `Wines` tables following
               the Rails-API-One-To-Many demo/code-along/lab exercises

Tues Apr 25 - Build and Implement API backend calls for `Foods` and `Wines` tables
               following the Rails-API-One-To-Many demo/code-along/lab
               exercises (Test all CURL CRUD (create, read, update, delete)
               requests as well as verify localhost output)

Wed Apr 26  - Re-review project requirements
            - Design objects needed to pass as data to back end API
            - Design forms needed to load objects to pass as data to back end API

Thur Apr 27 - Project Workshop #1
            - Design stub HTML and CSS from wireframe including modals for getting
               user input for food (FoodInputModal) and wine (WineInputModal)
            - Build/implement stub HTML and CSS from wireframe including modals
               for getting user input for `Foods` (FoodInputModal) and `Wines`
               (WineInputModal)

Fri Apr 28  - Project Workshop #2
            - Continue build/implement stub HTML and CSS from wireframe including
               modals for getting user input for `Foods` (FoodInputModal) and
               `Wines` (WineInputModal)
            - Test Food/Wine CRUD modal buttons work with back end API AJAX calls
               verifying localhost (front-end and back-end) output

Sat Apr 29 - Sun Apr 30
            - Review status to date
            - Catch up time (if needed)
            - Get sleep!  :-)

Mon May 1   - Project Workshop #3
            - Update READMEs in both repos
            - Verify all requirements are met
            - Enhance front-end (CSS - Add background image)

Tues May 2  - Project Workshop #4
            - Update documentation
            - Get sleep!  :-)

Wed May 3   - Project Presentation
