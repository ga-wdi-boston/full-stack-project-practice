Project Idea
A web app that runs cellular automatons. The app would allow users to change the rules of how the cells behave, such as how long it takes a cell to 'die' or how many cells are 'born' when cells 'breed'.
I came up with the idea after playing around with Conway's Game of Life during class. I found it interesting and thought that it could actually be useful as a simple model for various things such as infection patterns, birth rates, or other things. I imagine people who would use it would be those who are interested in modeling various problems or who are just curious as to how certain scenarios play out.

User Stories
As a user, I can set rules for automatons.
As a user, I can save rules I make.
As a user, I can see the history of steps/ticks/frames.
As a user, I can change the way cells are displayed.

Tables
User Table
Columns are password and username
Ruleset Table
Columns for the values of various 'rules'
Rows are the Rulesets or 'profiles' saved by the user

ERD

Routing
Routes to POST new rulesets, PATCH update rulesets, DELETE rulesets, and GET rulesets

3rd Party APIs
D3.js

Wireframes

Timetable
Plan
Make front-end and back-end templates
Create basic cellular automata
Add Comment
