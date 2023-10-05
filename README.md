# EsLintThree

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.3.

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

# INSTALL PRETTIER ESLINT


1. command: `ng add @angular-eslint/schematics`


## Install and configure Prettier
2. command: `npm install prettier --save-dev`
3. Add .prettierignore and .prettierrc files with the configuration data


## Configure Prettier to be used as an ESLint plugin
4. command: `npm install prettier-eslint eslint-config-prettier eslint-plugin-prettier`
5. Add a line in `extends` property of .eslintrc.json file:
...
`plugin:prettier/recommended`
...

6. command: `ng lint`
