# Instructions for running this server locally
1) Install [NodeJS](https://nodejs.org/)

2) Install AngularCLI
~~~
npm install @angular/cli@latest -g
~~~

3) Install nodemon
~~~
npm install -g nodemon
~~~

4) Download or clone this repository

5) Open the NodeJS Terminal. Run 
~~~
npm install
~~~
 to add the needed files into the node_modules folder

6) Run 
~~~
ng build
~~~
to compile the Angular front-end components into the `dist` folder

7) Run 

~~~
node server.js
~~~

**NOTE: You can also run the following command to have the Angular built and server restarted when code changes**
~~~
npm start-dev
~~~

8) Open [localhost:3000](http://localhost:3000/) in your browser. You should see a basic Angular app displayed. You are now running a local server. 




# How this app was created
## Install Angular
~~~
npm install @angular/cli@latest -g
~~~
### Update TypeScript
> Note: the following was necessary to get the Angular installer to work. In future this may not be necessary.  
~~~
npm install --save-dev typescript@2.6.2
~~~
## Create the app
~~~
ng new app-name-goes-here
~~~
## Compile Angular and check that it works
~~~
cd app-name-goes-here
ng serve
~~~
Visit [http:localhost:4200](http:localhost:4200)
## Install Express and Body Parser
~~~
npm install express body-parser --save
~~~
## Add the server.js file



# NOTE: the below information was created as part of the 'ng build' process

# SimplestAngularNodejsServer

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
