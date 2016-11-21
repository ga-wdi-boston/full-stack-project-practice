# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is to create app that acts as a gallery for graffiti. I came up with the idea because I was recently redecorating my apt and decided to go with a more modern theme and I found that I had to search through a bunch of different sites in order to find multiple images I liked.

I like the idea because of all the sites I found, very few allowed users to upload their own images. They we're mostly concerned with popular graffiti artist's works - very few amateur-produced pieces.

Anyone interested in photography or graffiti could use it as a location to find new styles, talk about their preferences, share images of their local graffiti and create a general community.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a user, I want to be able to sign up / sign in / sign out and change passwords.
As a user, I want to be able to upload pictures to the gallery and details on those pictures (location, date, what was used to take the picture, etc).
As a user, I want to be able to comment on each picture.
As a user, I want to be able to click a button to 'favorite' a picture.

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

Images:
- Image name
- Description
- Date taken
- Artist
- Image type

Location:
- City
- State
- Street
- Country

User info:
- First Name
- Last Name
- Camera type
- Expertise level

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

One to One:
Image - location
User info - location

One to Many:
User info - images

## Routing

What routes will you need to be able to make the proper request to your API?

Locations to find a given picture's location, user info to find out who uploaded the image, and images to find the mentioned image.

## 3rd Party APIs

Do you plan to use any, if so what are they?

Google maps if possible. Instragram for sharing.

## Wireframes

Please create a wireframe of your planned front end.

The wireframe is super simple because the website's main purpose is to display images.

http://imgur.com/q5PWU6r

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

Have a solid timetable in mind. Going to get all of the API stuff out of the way first and hopefully get any looming questions out of the way early. The HTML of the site wont be too intensive since its mostly going to be concerned with images. The css also shouldnt take too long. Primarily going to focus on the user associations for commeting / uploading initially.
