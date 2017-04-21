# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My application will be called MindCloud. It will be like a SnapChat for ideas, where you put random thoughts, links and ideas throughout the day that you'd like to return to. I will either limit the number of ideas that can be saved to a handful, or purge the idea after 24 hours. The idea is to create some urgency around the things you put there. If you don't return to it with a certain time period, you probably never will. I came up with the idea looking through my apple notes app and seeing all of the random stuff I save there and never return to. Why let it clutter up your life if it isn't important?

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

- As a creative person with lots of ideas, I want a quick and simple way to capture a thought so that I can return to it later if it's truly of value to me.
- As a user of MindCloud, I want to be able to quickly remove thoughts/ideas that are no longer valuable to me.
- As a user of MindCloud, I'd want to see a preview of a link I save so I can quickly determine if it's something I want to revisit.
- As a user of MindCloud, I don't want old ideas and randome thoughts cluttering up my "cloud" space.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

- User table
  - Username
  - Password
  - User ID - Primary Key

- Links Table (storing link details)
  - URL
  - Optional text to describe it?
  - User ID - Foreign Key
  - Age of record (if plan to purge after x hours)

- Idea Table (storing comment details)
  - Comment details
  - User ID - Foreign Key
  - Age of record (if plan to purge after x hours)

- Doodle Table (storing drawings made by a user)
  - PDF/JPG details
  - User ID - Foreign Key
  - Age of record (if plan to purge after x hours)

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

![Sketches](imgs/Project Sketches.jpg)

## Routing

What routes will you need to be able to make the proper request to your API?

GET - Return all ideas for a user account
POST - Add new idea
DELETE - Remove ideas
PATCH - Edit an idea

## 3rd Party APIs

Do you plan to use any, if so what are they?

I don't plan to use a third party API at this point, but may consider it if I use this app for my capstone and build out further functionality.

## Wireframes

Please create a wireframe of your planned front end.

See above image under ERD.

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

- Authentication
  - Validate all routes on backend
  - Add forms to front end and validate routes
- Build out basic front end using HTML/CSS/Bootstrap etc.
- Create backend database
  - Create tables and relationships
  - Validate routes on backend
- Enhnace front end to support testing of API routes, as needed
  - Validate API routes for user actions
- Enhance design of frone end
