# About

This example shows one way to use Typescript and Angular 2 in a
monolithic Rails 4 application *without* using the asset pipeline.

The Angular 2 app lives in the ng-app folder. ng-app/\*.ts is compiled
to public/\*.js using tsc -w via npm start. See package.json for
details.

# Develope
- write Angular 2 app to ng-app folder
- write Angular 2 html file and css file to public folder

# Installation

* bundle install

* npm install

# If the typings directory doesn't exist after npm install:

* npm run typings install


# Starting the server and compiling the typescript to js

* npm start

* rails s

* visit http://localhost:3000/ in a browser to see the angular 2 page
