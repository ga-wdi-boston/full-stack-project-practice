# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

I'm developing an app that allows you to make a list but also check the nutrition
facts using a third party api. I came up with the idea because I'm always making to-do lists and always check nutrition labels on the food I'm eating specifically the total calories and protien. Anybody that needs to make a list. If you plan on making a shopping list with food you will get the nutrition facts for each item.
## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user, I want to be able to sign up.
As a user, I want to be able to sign in.
As a user, I want to make a list.
As a user, I want to save a list.
As a user, I want to add food items to my list.
As a user, I want to delete items on my list.
As a user, I want to check any items nutrition facts.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?
Users - Id, email, password
Ingredients - Id, Title, Nutritional Information, user_id(foriegn_key)
## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

User has many ingredients

## Routing

What routes will you need to be able to make the proper request to your API?
 get '/ingredients/' => 'ingredients#index'
 patch '/ingredients/:id' => 'ingredients#update'
 post '/ingredients/' => 'ingredients#create'
 delete 'ingredients/:id' => 'ingredients#destroy'
 post '/sign-up' => 'users#signup'
 post '/sign-in' => 'users#signin'
 delete '/sign-out/:id' => 'users#signout'
 patch '/change-password/:id' => 'users#changepw'
 resources :users, only: [:index, :show]

## 3rd Party APIs

Do you plan to use any, if so what are they?

I would like to use a 3rd party nutrition api when you add a list item the nutrition facts will appear.

## Wireframes

Please create a wireframe of your planned front end.

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Build front - end then move on to building back - end. 
