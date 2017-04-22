# Full Stack Project Practice

You will be presenting this early next week.  Please have a breif presentation
planned.  Presentations should be between 5 - 10 minutes long.

You may use GitHub, PowerPoint, Keynote, or any other tools you desire to
complete any part of this.

## Project Idea

What is your project idea?  How did you come up with it? Why? Who would use it?

```
Project idea: List of notes that can take attachments

I thought about my previous project team that struggled with the notes with
attachments. What was implemented was one attachment per note. In the business
area, the help desk has a need to attach documents to notes for audit purposes.
```

## Write between 3-5 user stories

We have gone over this before. Please refer to your notes, previous repos or the
google machine if you need further assistance.

```
* As a user, I want to save a note so that I can reference it later and not have
to rely on my memory.
* As a user, I want to save attachments with my note so that I can reference the
attachment later.
* As a user, I want to be able to keep certain notes of my choosing ordered
sequentially at the top of my list so that I know which of my notes are more
important than others.
* As a user, I want the other notes that are not specially selected to be
display in the order of oldest to the newest note so that I can find a note
by date.
* As a user, I want to be able to search for notes that match a keyword.
```

## Plan your tables and columns

What tables will you need? What will the columns on the table be?

```
Users
  id
  email
  password
  first_name
  surname

Notes
  id
  keep_on_top_rank
  note_title
  note_text
  number_of_attachments (fk)

Attachments
  id
  note_id (fk)
  attachment_data
```

## Create an ERD (entity relationship diagram)

These are the diagrams that show how your tables are related to one another.
(one to many, many to many, ect).
<https://drive.google.com/open?id=0B-2RTwybdRVxZ3lqTjRCcTNmcTQ>

## Routing

What routes will you need to be able to make the proper request to your API?
```
resources :users, except:[:new, :edit]
resources :notes, except:[:new, :edit]
resources :attachments, except:[:new,:edit]
```

## 3rd Party APIs

Do you plan to use any, if so what are they?
```
Maybe. I still need to research how to transform files into text.
```

## Wireframes

Please create a wireframe of your planned front end.

<https://docs.google.com/presentation/d/1j49LmMBXOH2be_nlWbRV1rNbQpJVzUhry6JTQhsC05Q/edit?usp=sharing>

## Timetable

Write a basic timetable for yourself, you don't have to stick to it but it
helps to go in with a plan.

```
Day 1 - Plan and design: wireframe, user stories, ERM
        Set up front end repository
        Set up back end repository
Day 2 - Design front end user/page interaction. Design backend based on front
        end user/page interaction. Code MVP (simple notes db w/out attachments)
Day 3 - Research and code attachments feature (and perhaps storing and displaying
        URL as a link in the note)
Day 4 - Refine, final testing
```
