# Angular 01

## Table Of Contents

- [Angular 01](#angular-01)
  - [Table Of Contents](#table-of-contents)
  - [Description](#description)
  - [UTBM Proxy](#utbm-proxy)
  - [Command](#command)
  - [Development server](#development-server)
  - [Code scaffolding](#code-scaffolding)
  - [Build](#build)
  - [Running unit tests](#running-unit-tests)
  - [Running end-to-end tests](#running-end-to-end-tests)
  - [Further help](#further-help)

## Description

Front End Angular for Rails Back End.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.25.

## UTBM Proxy

    npm config set proxy http://proxy.utbm.fr:3128
    npm config set https-proxy http://proxy.utbm.fr:3128

## Command

    npm install -g @angular/cli@8     # Global Install
    npm install @angular/cli@8

    npx ng new burger --directory=.
      y
      CSS => Enter
    
    npm start

    npx ng build --prod

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
