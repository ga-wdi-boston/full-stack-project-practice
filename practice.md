# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

Advice apps -- Take your own advice

Take your own advice is an app that randomly generates advice from a list of advice stored as strings associated with each user.  There is a library of default advice that you can access and add to your own advice library, or you can just add your own advice, delete individual stings of advice, or delete all your stored advice and start all over again.  When you click the “take my own advice” button you get the text for one piece of advice.  You can keep clicking the button to get more advice for as long as you want and keep getting more advice.

Extras – one I get the basics to work I would add
–	The ability to respond to advice, whether you took it or not, and get a record back of what percent of the time you are taking your own advice.
–	The ability to import other people’s advice libraries provided you get their username.
–	More additional stored loadable advice libraries with fun names, like advice from Mom, advice from fun friend, advice from a ten year old boy, ect.
–	The ability to edit strings of advice.


## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

1.) As a user I want it to be fun and easy to click through advice
2.) As a user I want it to be simple to add and subract advice
3.) As a user I want the sign in process to be easy.
4.) As a user I want the mobile version of the app to be readable

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

I will have one table 'users' that has user name, user password, and an id.
I will have another table 'advice' that has strings of advice, advice id, and a user id number as a reference key.
There will be two tables total, the relationship between them will be initally a one to many relationships of user to advice, but would become and many to many relationship in the second version of the game where users are able to access the advice of others users.

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

user table to advice table relationship is one to many

## Routing

What routes will you need to be able to make the proper request to your API?

post '/sign-up' => 'users#signup'
  lets users make account
post '/sign-in' => 'users#signin'
  lets users sign in
delete '/sign-out/:id' => 'users#signout'
  lets users sign out
post '/advice/seed_advice' => 'advice#seed'
  loads seed advice to user database when they first make an account
post '/advice/:id' => 'advice#index'
  lets user get one pieces of advice
post '/advice/' => 'advice#create'
  lets user create one string of advice
destroy 'advice/:id' => 'advice#delete'
  lets user delete one string of advice

--
additional routes
patch 'advice/:id' => 'users#update'
  lets user update strings of advice
 post '/advice/advice_user' => 'advice#advice_user'
  loads ones elses advice database, or a different preexsisitng database
patch 'user/take_advice' => 'user#take_advice'
  records if user took their own advice

## 3rd Party APIs

Do you plan to use any, if so what are they?

At the moment I do not plan to user any 3rd party APIs.

## Wireframes

Please create a wireframe of your planned front end.

http://imgur.com/a/0DX16

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Plan:
Now - May 1st: learning and planning.  Focused on learning the material and thinking about how to implement it for my specific idea, but don't start writing any code specifically for the project yet.
Starting May 1st, in order of how quickly things are accomplished
- build simple html and scss using bootstrap and handlebar to run the game in.  Build simpliest functional version.
- start doing user sign in / out back end api writing,
- connect user data table functionality to front end. Accomplish sign in and sign out.
- build advice table, make it possible for a signed in user to load a seed table of advice and retrieve some of it.
- build functionality for a user to add peices of advice.
- build functionality to delete individual advice
- build routes and functionality for a user to delete their whole advice library and start again
- evaluate how much time I have, if extra time is available.
  - work on graphics, add simple fun touches to make it more user friendly and fun
  - add additional libraries and the ability to important them
  - add a button to indicate if you have taken the advice or not, and return the precent of advice taken (requires adding an extra columns to the user table that counts total advice recieved and advice taken).
  - add ability to import the data from other users (requires changing relationship between the two tables to many to many)
