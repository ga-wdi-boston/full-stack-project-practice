# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My idea is to build a pregnancy tracker. Becoming a new mother is daunting - my
sister is expecting and uses 3-5 apps daily to help her keep track of her
symptoms, how her baby is growing, what food she should eat etc. I was inspired
by that!

This project would of course be a super simplified version. It will
have the mother-to-be input how many weeks pregnant she is --> user will get a
response telling her how big her baby is now (I'm thinking of something like
"your baby is now the size of a macaron!")

Any pregnant woman could use it as a fun way way to track the growth of their
baby.

## Write between 3-5 user stories

* As a guest, I can sign up to use this app.
* As a registered user, I can change my password and sign out.
* As a registered user, I can keep track of how long I’ve been pregnant.
* As a registered user, I can see an estimate of how large my baby is at a
certain point in time.
* As a registered user, I can choose a week and see what size my baby was at
that time.
* As a registered user, I can see all my weeks and how my baby has grown over
that time.

## Plan your tables and columns

Table 1: users
  Column 1 - id
  Column 2 - email
  Column 3 - name

Table 2: babies
  Column 1 - user_id
  Column 2 - age (in weeks)
  Column 3 - size

## Create an ERD (entity relationship diagram)

![Entity Relationship Diagram] (http://imgur.com/a/oMQko)

## Routing

post '/sign-up' => 'users#signup'
post '/sign-in' => 'users#signin'
delete '/sign-out/:id' => 'users#signout'
patch '/change-password/:id' => 'users#changepw'
resources :users, only: %i[index show]
resources :babies, only: %i[index show destroy update create]

## 3rd Party APIs

Do you plan to use any, if so what are they?

No, I do not.

## Wireframes

Please create a wireframe of your planned front end.

![Project Two Wireframe] (http://imgur.com/a/UZBdp)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

I hope to do most of the basic HTML tomorrow (Friday); finish the authentication
portion over the weekend, and then spend most of next week working on the user
and babies database and connecting the two, using the information we are
currently learning. Then after meeting requirements, I hope to work on styling
and making the UI better.
