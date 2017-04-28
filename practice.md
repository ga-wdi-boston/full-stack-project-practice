# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

I have been frustrated when looking for information in all the gabillions of repos
you guys have given us.   My project is to provide an interface to look at all
our repos, the table of contents of the READMEs, hopefully some tagging (here I
come many-to-many!) and whatever else I can squeeze in.

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

As a GA student sitting at the end of the firehose, I want to:
-  display a list of all my repos
-  be able to tell what each one was about
-  group them by subject
-  tag or flag certain repos
-  delete any repo i don't care about


## Plan your tables and columns

a table of repos

``| repo name |  repo url  |  repo TOC |``

a table of tags

``| tags |``

a table of users

``| email | password | github name |``


## Create an ERD (entity relationship diagram)


user owns many repos (one to many)

repos has and belongs to many tags


## Routing

What routes will you need to be able to make the proper request to your API?

-  repos#show
-  repos#index
-  repos#destroy
-  repo#udpate

- users#signup, signin, signout, change password

-  tags#show
-  tags#index
-  tags#create


## 3rd Party APIs


If I can, I would use the github API to get the list of user's repos.

## Wireframes

Please create a wireframe of your planned front end.

## Timetable


```
loop
  type like crazy
  test like crazy
  commit
end```

don't have a timetable yet but here are some things on my to do list:

repo table
-  create the repo table
-  hand-generate a list of repos
-  off of the repo list, generate a TOC for each README
-  seed the table with this stuff
-  controller/model to index/show/create?/add? repos

tags
-  create a tag table
-  seed it with some data
-  controller/model to index/show/create/add tags
