# rails-stimulus-sass

Epic Ruby On Rails Starter SaaS preconfigured boilerplate with Bootstrap 5, Devise, Noticed, Announcements, Madmin, Stimulus JS and Action Cable, with Redis Caching

https://stimulus.hotwired.dev/

https://docs.stimulusreflex.com/

Combine with Hotwire and Strada

https://hotwired.dev/

Also can be easily used with React/Vue via $rails webpacker:install:react (or vue) if required

Style kept minimal so Bootstrap 5 can be swapped out for other CSS or UI if required

* Ruby version

Ruby 3.0.0

Rails 6.1.0

* Setup

 bundle install/update (if change any gems)
 npm i
 yarn
 rails db:migrate  (sqlite3)
 rails stimulus_reflex:install
 rails dev:cache
 rails g madmin:install  (if not, have to alter nav)
 rails g madmin:views

* Start server
 rails s

* Todo

Add Minitest

(For other cmds see  related docs/links)



* ...
