# Full Stack Project Practice

You will be presenting this early next week.  Please have a brief presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

- A place for gifters to create lists of gift ideas for their giftees
- Real life issues remembering ideas (bookmarking/favoriting didn't work, wishlists are make by giftee not gifter)
- Anyone who gives gifts to people and
  - needs help remembering what gift ideas they've had
  - is a super planner and wants to organize their gift plans

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

♣	As a user, I want to be able to [Sign Up] in order to create my unique profile
♣	As a user, I want to be able to [Sign In] in order to access my unique profile
♣	As a user, I want to be able to [Change Password] in order to update my password
♣	As a user, I want to be able to [Sign Out] in order to ensure that a session is over

♣	As a user, I want to be able to create/update/remove [Giftee] in order to create a unique list for a specific person I plan to give gifts to:
  ♣	As a user, I want to be able to make a list have a name [Giftee Name] so I clearly know who the ideas are for
    ♣	As a user, I want to be able to add [Notes] regarding the giftee's so I can refer to them for future  gifts
    ♣	"" [Clothing Brands] ""
    ♣	"" [Shoe Brands] ""
    ♣	"" [Food] ""
    ♣	"" [Candy] ""
    ♣	"" [Drinks] ""
    ♣	"" [Sizes] ""
      ♣	"" [Notes] ""
      ♣	"" [Tops] ""
      ♣	"" [Bottoms] ""
      ♣	"" [Dresses] ""
      ♣	"" [Shoes] ""
♣	As a user, I want to be able to add/update/remove [Gift Ideas] to a giftee in order to  (see below)
  ♣	"" [Title] ""
  ♣	"" [Source] "" (link)
  ♣	"" [Price] ""
  ♣	"" [Notes] ""
  ♣	"" [Occasion] ""
    ♣ default list (see below for stretch)
  ♣	"" [Status] ""
    ♣ (pending, removed, given)

STRETCH GOALS
♣  STRETCH Occasion
  ♣	Default list of holidays + birthday + anniversary + graduation with inputs for specific dates
♣	STRETCH Occasion tracker
  ♣	List of upcoming holidays/events based on date
♣	STRETCH User should be able to see past gifts purchased for a giftee


## Plan your tables and columns

What tables will you need? What will the columns on the table be?

GIFTER
id | username | giftee_id

GIFTEE
id | name | notes columns galore | gift_idea_id

GIFT IDEAS
id | title | source | price | notes | occasion_id

OCCASION
id | name | date

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).


GIFTER -|---< GIFTEE
GIFTEE -|---< GIFT IDEAS
GIFT IDEA -|---|- OCCASION

## Routing

What routes will you need to be able to make the proper request to your API?

Rails.application.routes.draw do
  resources :gift_ideas
  resources :gifter, except: [:new, :edit]
  resources :giftee, except: [:new, :edit]

  post '/sign-up' => 'users#signup'
  post '/sign-in' => 'users#signin'
  delete '/sign-out/:id' => 'users#signout'
  patch '/change-password/:id' => 'users#changepw'
  resources :users, only: [:index, :show]
end

## 3rd Party APIs

Do you plan to use any, if so what are they?

If time allows I want to look into calendar/holiday APIs to see if I can allow gift ideas to be sorted by closest occasion date

## Wireframes

Please create a wireframe of your planned front end.
https://raw.githubusercontent.com/ga-wdi-boston/full-stack-project-practice/f5c4dbdec5af74cec2b99a3216fd2a83e7194e22/wireframe.jpg

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

- HTML layout (1 day)
- Backend (2-4 days)
  - account access (.5-1 day)
  - giftee list control (1 day)
  - gift idea list control (1 day)
    - allow view of past gifts (.5 day)
  - STRETCH occasions (1 day)
- CSS/styling (1 day)
- Polish (1-2 days)
