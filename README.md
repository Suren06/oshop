# Oshop

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


ng new oshop
cd oshop
ng serve 
npm i --save firebase@4.2.0 angularfire2@4.0.0-rc.1

## To fix this (ERROR in node_modules/angularfire2/auth/auth.d.ts(3,10): error TS2305: Module '"../../rxjs/Observable"' has no exported member 'Observable'.)
npm i --save rxjs-compat 

npm i --save bootstrap

## Uncaught ReferenceError: global is not defined
IN polyfills.ts file add below line
(window as any).global = window;

ng g c bs-navbar

## Components generated
ng g c my-orders
ng g c order-success
ng g c check-out
ng g c shopping-cart
ng g c products
ng g c home
ng g c admin/admin-products
ng g c admin/admin-orders
ng g c login

sudo npm install --save @ng-bootstrap/ng-bootstrap

sudo npm install -g firebase-tools

firebase init
---Hosting
What do you want to use as your public directory? oshop
n, n, n, n(just select n for all question..)

ng build --prod
firebase deploy


Hosting URL: https://oshop-e5197.web.app