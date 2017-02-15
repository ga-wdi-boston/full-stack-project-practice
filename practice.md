# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

My project idea is to create a handy music reminder app that allows me to post, for myself or for others, albums or songs that I discover and want to remember for later. I thought of this app by repeatedly walking into music stores and immedietly forgetting what albums I have wanted to buy. It is very annoying. Ideally this would be a mobile app that would allow me to post the names of albums and songs that I want so that when I walk into a music store I can quickly pull it up and remember what albums I have listened to in the past that I want to purchase. I would use it and my friends would definitely use it as they are music lovers. Other music lovers would also find this app handy. If it seems feasable during the production of this project I would also like to add a feature where a user can post what he or she is currently listening to so that other can view it and possibly check it out later.
## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.
As a user I want to be able to post an album that I dont own so I can save the name of it for later.
As a user I want to be able to post the names of a song I am listening to (that I dont have in my music library) so i can look it up later.
As a user I want the ability to post what I am currently listening to so others can access that information.
As a user I want the ability to access a list of albums that I saved so I can look them up when I ready to purchase music.
As a user I want the ability to look up another users list of saved albums so I can see if there is anything that I like in it.
As a user I want to be able to comment on other users saved albums.
As a user I want to be able to delete albums that I have purchased so I can check what albums I have already bought


## Plan your tables and columns

What tables will you need? What will the columns on the table be?

I will need the following tables with the following columns:
Users table:
first_name
surname

Music table:
artist_name
album_name (optional)
song_name (optional)
comments

SavedMusic
user_id
album_id
album_comments

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

|Users|-|-------------<|Music|
    T                     T
    |----<|SavedMusic|>---|

## Routing

What routes will you need to be able to make the proper request to your API?

index	Return a list of all resource instances.	GET	/album
create	Create a new instance of a resource.	POST	/albums
show	Return a single instance of a resource.	GET	/album/:id
update	Update a single instance of a resource.	PATCH	/albums/:id
destroy	Destroy a single instance of a resource.	DELETE	/albums/:id

## 3rd Party APIs

Do you plan to use any, if so what are they?

Not planning on using any as of yet

## Wireframes

Please create a wireframe of your planned front end.
http://imgur.com/a/kr8su

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.
My timetable is to first do all of the authentication stuff then I will create all of the tables then make example data. I will try to create all of the models, controllers, serializers, and routes. Finally when I am satisfied with how the tables are constructed I will then work on my jquery and front end of the application modifying the backend if necessary as I am creating my front end.
