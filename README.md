# TestPbuttonNgUniversal

## Reproducing the pButton issue
* git clone https://github.com/myonara/test-pbutton-ng-universal.git
* npm run dev:ssr
* navigate to http://localhost:4200 
* error is occuring on the console.

## Setup
* This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.1.
* ng generate module app-routing --flat --module=app
* ng g component start
* (changed app.component.html added routing and an a-link to start, changed app-routing.module.ts)
* npm install primeng primeicons --save
* (changed a-link to button/pButton)
* ng add @nguniversal/express-engine
* (Testing with npm run dev:ssr)
* error occuring in the console during opening http://localhost:4200 




# TestPbuttonNgUniversal (Angular)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
