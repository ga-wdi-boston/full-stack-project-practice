# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

```txt
A tabletop games map maker.

I wanted to make a tabletop game that you could play on the computer, but I
realized that making a full game would take too long, so now I'm going to make
a site that lets you create and save maps.

Someone who is planning an adventure could use this to save his ideas without
having to draw them out with their crappy drawing skills.
```

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

```txt
As a user I want to save my maps so that I can come back to it later.
As a user I want to delete a map.
As a user I want name my maps.
As a user I want to see all of the maps I've created.
As an admin I want to only prevent others from accessing other people's maps.
```

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

```txt
TableName: ColumnNames
User: id
Maps: id, mapName, grid(array), userId(reference)
```

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).

```txt
  ----------          ----------
  -  User  - -------E -  Maps  -
  ----------          ----------
  -        -          -        -
  -        -          -        -
  -        -          -        -
  ----------          ----------
```

## Routing

What routes will you need to be able to make the proper request to your API?

```txt
User: Post, Patch, Index, Delete
Maps: Post, Patch, Index, Show, Delete
```

## 3rd Party APIs

Do you plan to use any, if so what are they?

```txt
Nope
```

## Wireframes

Please create a wireframe of your planned front end.

```md
Wireframe: https://wireframe.cc/trdNcg
```

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

```txt
Create the wireframe.
  Start off with a grid of 5x5, go to 10x10 eventually.
Create the database using rails
  Make a user(rails makes this)
  Make a maps table
Create ajax for user
Create logic for clicking on the grid
Create ajax for maps
Include graphics for grid (trees, rocks, grass)
Clean up code and make pretty

Bonus:
Search for other people's maps
Rate other people's maps
Include a dropdown selector for types for terrain
  -grass
  -sand
  -cave
  -buildings
  -monsters
Convert to a pdf so that you can print it.
  (maybe you dont have to convert to pdf to make it printable.)
Variable map sizes
  Independently variable lengths and widths
Generate a random map
```
