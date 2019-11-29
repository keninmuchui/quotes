# Quotes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.19.

## By Kenin Muchui Ncunge

# Project Description
User can add, vote and delete quote. For adding new quote there is form with required input fields. To vote user can vote liked quotes and unliked votes using buttons with thumbsup and thumbsdown.

# Setup/Installation Requirements
1. Internet connection.
2. Angular installation.
3. Node Installation.
4. Clone https://github.com/keninmuchui/quotes.git
5. Go inside the folder that contains the project.
6. Run `ng serve` for a dev server. Navigate to a browser and `http://localhost:4200/`.
7. Otherwise check link deployed page: https://keninmuchui.github.io/quotes/

# Specifications
|INPUT|OUTPUT|DISPLAY|
|-----|------|-------|
|Empty|Author is required|Error|
|Empty|Publisher is required|Error|
|Empty|Quote is required|Error|
|Submit Button|Data Saved|All fields, 2 buttons for vote and Delete button|
|Delete Button|Confirmation box|Deletes if yes or cancel|
|Thumbsup Button|Add 1 like vote|1 or greater on thumbsup button|
|thumbsdown Button|Add unlike vode|1 or greater on thumbsdown button

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
