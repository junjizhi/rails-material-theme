# README

This project provides a base Rails app with [Material Theme](https://daemonite.github.io/material/) theme. The app also comes with basic
functionalities like User Sign-up and Log-in.

With a few steps, you can customize the app for your own needs.

## Screenshots
![Rails-Material-Screenshot-1](https://user-images.githubusercontent.com/2715151/52524310-a13f9e00-2c69-11e9-8c2d-4f52aad082ce.png)
![Rails-Material-Screenshot-2](https://user-images.githubusercontent.com/2715151/52524311-a13f9e00-2c69-11e9-8772-da3207b5fa24.png)

## Dependencies

Below is the environment I tested on:

```
$ ruby -v
ruby 2.5.0p0 (2017-12-25 revision 61468) [x86_64-darwin17]

$ rails --version
Rails 5.2.1

```

By default, the app depends on postgres v9.6.

## Database creation & initialization

```
bundle exec rake db:create
bundle exec rake db:migrate
```

Note: The user model is created with the
[Devise](https://github.com/plataformatec/devise) gem.

## Running the app locally


```
export DATABASE_URL=postgres://<DB_USER>:<DB_PASS>@localhost:5432/rails-material-dev
export RAILS_ENV=development
bundle exec rails s
```

Visit the page: http://localhost:3000/

## Gems already installed

- Bootstrap
- Devise
- jquery
- material-sass
- bootstrap_form

## Customize the app

- Rename the app (search and replace `hotpot` with your app's name)
- Tweak the front end for you needs

## Contributing

To contribute, follow the steps:

- Fork this repo and clone to your local machine
- Create your feature branch (`git checkout -b my-awesome-feature`)
- Commit your changes (`git commit -am 'Implement blah'`)
- Push to your branch (`git push origin my-awesome-feature`)
- Create a new pull pequest (PR) with a brief description of what and why.
- Get notified when your PR is merged!

Issues and pull requests are always welcome!
