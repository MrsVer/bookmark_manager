# bookmark_manager

### [Makers Academy](http://www.makersacademy.com) - Week 4 Pair Programming Project
#### Technologies: Ruby, Rspec, Sinatra, Heroku, HTML, CSS, Postgres, SQL, DataMapper


Specification:

- Show a list of bookmarks
- Add new bookmarks
- Delete bookmarks
- Update bookmarks
- Comment on bookmarks
- Tag bookmarks into categories
- Filter bookmarks by tag
- Users are restricted to manage only their own bookmarks

### User stories

```
As a user
So that I can quickly go to web sites I regularly visit
I can see the list of bookmarks

As a user
So that links I discovered recently can be saved in my bookmark list
I can add a new bookmark

As a user
So that sites I no longer visit regularly can be removed
I can delete a bookmark from my list

As a user
So that changes in the URL can be reflected in my bookmarks
I can update an existing bookmark

As a user
So that I can keep track of my thoughts 
I can add a comment to an existing bookmark

As a user
So that I can make changes to my notes about a bookmark
I can update a comment to an existing bookmark

As a user
So that I can remove an existing note  
I can delete a comment from an existing bookmark

As a user
So that I can group my existing bookmarks
I can add tag bookmarks into categories

As a user
So that I can see only links I am interested in
I can filter my existinging categories

As a user
So that I can manage my bookmarks only
I can modify bookmarks I own

```

### Domain Model
![Domain model](./attachments/bookmark_manager_1.png)

Anyone needing to setup the database from scratch will need to do the following things:

1. Connect to `psql`
2. Create the database using the `psql` command `CREATE DATABASE bookmark_manager;`
3. Connect to the database using the `pqsl` command `\c bookmark_manager;`
4. Run the query we have saved in the file `01_create_bookmarks_table.sql`