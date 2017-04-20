# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

### Project - Openers

My project is to allow users to post their best 'openers' i.e. opening lines they would use to start talking with someone whether it's in person or on one of the various dating apps.

Example: "Hey how's your day going?"

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

### Opener - User Stories

#### Authentication

-   [User sign up](https://github.com/jim-moody/opener-api/issues/1)
-   [User sign in](https://github.com/jim-moody/opener-api/issues/2)
-   [User sign out](https://github.com/jim-moody/opener-api/issues/3)
-   [User change password](https://github.com/jim-moody/opener-api/issues/9)

#### Posts

-   [Create posts](https://github.com/jim-moody/opener-api/issues/4)
-   [Vote on posts](https://github.com/jim-moody/opener-api/issues/5)
-   [Update posts](https://github.com/jim-moody/opener-api/issues/7)
-   [Delete posts](https://github.com/jim-moody/opener-api/issues/8)

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

| User     | Posts     |
| -------- | --------- |
| id       | id        |
| email    | message   |
| age      | user_id   |
| gender   | upvotes   |
| password | downvotes |

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

### Opener - ERD

Posts>-|-User

-   `Post` belongs to `User`
-   `User` has many `Posts`

## Routing

What routes will you need to be able to make the proper request to your API?

### Opener - Routing

-   /signup
-   /signin
-   /changepassword
-   /signout
-   /posts

## 3rd Party APIs

Do you plan to use any, if so what are they?

-   Nope

## Wireframes

Please create a wireframe of your planned front end.

### Opener - Wireframe

-   [Proto.io Wireframe](https://pr.to/1N29MD/)

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

-   Day 1 - Finish Posts API
-   Day 2 - Finish Auth API and relate posts to auth
-   Day 3 - Create client for posts
-   Day 4 - Create client for auth
-   Day 5 - Add styling and cleanup bugs
