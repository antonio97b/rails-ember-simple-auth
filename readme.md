# rails-ember-simple-auth
By: Antonio Navarro

This is a working demo of using Ember.js (cli version 2.6.3) and Rails 4.2.4. It includes a template

## Prerequisites

You will need the following things properly installed on your computer.

Ember:
* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

Rails:
* [Rails 4.2.4](http://rubyonrails.org/)
* [Ruby 2.3.0](https://rvm.io/)
* [Postgresql](https://www.postgresql.org/download/)

## Installation

* `git clone https://github.com/antonio97b/rails-ember-simple-auth`
* `cd backend`
* `bundle`
* Make sure postgres is running
* `rake db:create`
* `rails c`
* create a new user by typing, `User.create!(email: "user@example.com", password: "password"`
* Exit the rails console and type `rails s`
* `cd ../frontend`
* `npm install`
* `bower install`

This is all that is needed to set up the program.

## Running / Development

* `ember s --proxy http://localhost:3000`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* You should now be able to login to your app using the user we created on the rails end (email: user@example.com password: password).

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
