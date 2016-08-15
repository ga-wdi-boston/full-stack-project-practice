# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project will provide a platform for user to write diary. People who prefer typing than handwriting will use this app to record their diary.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user, I want to create new diary so that I can write diary every day.
As a user, I want to upload photos so that I can add photos in my diary.
As a user, I want to save the diary so that I can review my previous diary.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

user table: username, password, diary
diary table: text, photo, weather, location

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

user-diary: one to many

## Routing

What routes will you need to be able to make the proper request to your API?

user: /sign-in, /sign-up, /change-password,/sign-out
diary: ／diarys, /new, /diarys/:id

## 3rd Party APIs

Do you plan to use any, if so what are they?

I will try to use the weather and location api.

## Wireframes

Please create a wireframe of your planned front end.

User Navbar; Diary Navbar; New Diary Form

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Frist day: Build app api
Second day: Frontend connects to the api
Third day: Finish the frontend
