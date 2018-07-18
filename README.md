# AngularDemo

## Installation
 - Start by installing angular-cli: `npm i -g angular-cli`
 - Generate a project using: `ng new angular-demo --style=scss`
 - Change into dir: `cd angular-demo`
 - Install project deps: `npm i`

## 1-housekeeping
 - Added box-sizing reset to `src/style.scss`
 - Delete contents of `src/app/app.component.html`

## 2-home-page
 - Create home component using `ng generate component home`
 - Go over all the files generated, and the changes to the `app.module.ts` file
 - Add home component to `app.component.html` using `app-home`
 - Create a `pages` dir under `app` and move the home component to `pages`
 - The page should be broken now (may need to restart `ng serve` to make this happen)
 - Explain the changes that need to be made to `app.module.ts`
 - Add some data to the `home.component.ts` file and display that data in `home.component.html`

## 3-routing-and-multiple-pages
 - Create an about and contact page without using the cli generator
 - Explain how to create files and what was being generated for you
 - After creating the contact page, explain two-way data, attr, and event binding
 - Ensure that the FormsModule is included in the `app.modules.ts` file.
 - Add RouterModule to the `app.module.ts` file
 - Add `<router-outlet></router-outlet>` to the `app.component.html` file.
 - Define routes for the three pages and a catch all route
 - Create a components dir
 - In the components dir, create a header component to house page nagviation.
 - Add `<app-header />` to `app.component.html`.

---
# Docs generated by Angular-cli
---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
