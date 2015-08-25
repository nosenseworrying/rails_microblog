# Ruby on Rails Microblog

## Description
This Microblog site is a basic Twitter clone that is based off of the tutorials found at [https://www.railstutorial.org](https://www.railstutorial.org)

## Concepts Learned
* Basic Rails concepts
* MVC
* Validation
* Users and Authentication in Rails
* Database relationships in Rails
* Git (Version Control)
* Using BitBucket/GitHub
* Heroku
* Testing
* Twitter Bootstrap

## Models
#### User
Represents a real-world user in the application.

Users have many Microposts and Relationships (followers and those followed).

#### Micropost
Represents a small status post, viewable by users who are followers.

Microposts belong to a User.

#### Relationship
Represents an existing relationship between two Users

Relationships contain the User ID of the follower, as well as the followed user.

