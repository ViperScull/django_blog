In our blog

Features
=========
Blog will have the following features

1. Post (Table in database)
2. Categories (Table in databes)
3. Tag (Table in our database)
4. Author (Table in our database)

Let us make a relation between our tables
=========================================
1. Post can have many categories, and categories can have many posts (Relation between Post and Category tables - Many to many)

2. A tag can have many posts and a post can many tags (Many to many)

3. An author can have many posts but a post can only have a single author (One to many)

Attributes for tables
=====================
1. Title
2. Created date
3. Body
4. Tags
5. Categories
6. Author

Categories
==========
1. Cat_name
2. Cat_description

Author
=======
1. Name
2. Email (not mandatory)
3. Bio

Tag
===
tag_name