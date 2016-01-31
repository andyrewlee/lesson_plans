# Database Design

### When should we design our database?
Build the clickable prototype first before coming up with the database design.
By building the front end, we will get a better understanding of what our
application needs.

### Why is database design important?
Might be the most important step.

### Why should we set up relationships?
Because we can use SQL to use these tables and their relationships to generate
any table that we might need in the future. For example if we wanted a users
table with all of their information in one huge table, we can make that happen
with SQL but also be able to make all these other tables as well.

### What about Mongodb?
Mongodb is not a NoSQL database. However we will go over SQL because you will be
dealing with a relational database for most applications. The quick difference
is that with a NoSQL database, you can have more freedom with the data that you
store. For example I can store two completely different attributes for two users
and they would still be in the users table. On the other hand every row in a SQL
database have the same columns.

### What are some ways we can store the data on this site?
* has one
  * One user has one classroom
* has many
  * One user has many panels. One panel belongs to a user
* many to many
  * One user can fan many people and can be fanned by many people
    * Need another table to represent this relationship
* Correctly answerings these questions is more important than learning the
  syntax, you can always look them up later. As long as the design is correct
  we can literally use those terms when we use ActiveRecord, the ORM used by 
  Rails

    class User < ActiveRecord::Base
      has_one :classroom
      has_many :panels
      # ...
    end

    class Panel < ActiveRecord::Base
      belongs_to :user
      # ...
    end

    class Fanships
      belongs_to :usea, foreign_key: 'user_id', class_name: 'User'
      belongs_to: :fan, foreign_key: 'fan_id', class_name: 'User'
      # ...
    end

### How do we look at a wireframe and come up with the database design?
* Break them out into individual tables first
* Then ask a question has many? belongs to? with every table

# Workout Level 1
Create an ERD diagram for a blog
