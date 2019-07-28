# IpmsWeb

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.5.

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







Upgrade / degrade

Clear NPM's cache:

## Code scaffolding
sudo npm cache clean -f
Install a little helper called 'n'

## Code scaffolding
sudo npm install -g n

Install latest stable Node.js version
## Code scaffolding
sudo n stable

Alternatively pick a specific version and install like this:
## Code scaffolding
sudo n 0.8.20



## Build process...
ng build --prod --base-href="/ipms/"
ng build --prod 

## ERROR
ERROR Error: "No component factory found for ExpensesCreateComponent. Did you add it to @NgModule.entryComponents?"
## SOLUTION
import { ModalModule } from "ngx-bootstrap";
ModalModule.forRoot()"# ipms" 
