# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
blog post
title string title
              author
cat string    body text
              blog_id
blog has many post
post belongs to blog


        index 
          |
        App (nav routes)
          |
          navbar
  home   about 404  blogs (HOC) 
                      |
                blogForm bloglist
                            |   
                          blog
                            |
                          Posts (HOC) 
                      post form  post list 
                                  | 
                                  post