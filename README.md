# Ruby on Rails Tutorial: first application

This is the first application for the
[*Ruby on Rails Tutorial*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).

### How to install this project
Clone the repository to your local machine
```sh
cd apps
git clone https://github.com/jacobtarr/first_app.git
cd first_app
```
Install the necessary dependencies for Rails
```sh
bundle install --without production
bundle exec rake db:migrate
```
Start the server
```sh
rails s
```
