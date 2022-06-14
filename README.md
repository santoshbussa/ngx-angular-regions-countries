# Angular application - NgRx regions countries


A demo Angular application with tests - Uses an API to display a list of regions, countries and the details of a selected country. NgRx libraries are implemented to manage the state of the app, Jasmine, Karma and Cypress for unit and e2e tests and Angular Material for presentation.


### Technologies

- [@ngrx/store](https://ngrx.io/guide/store) - RxJS powered state management for Angular apps, inspired by Redux
- [@ngrx/effects](https://ngrx.io/guide/effects) - Side effect model for @ngrx/store
- [@ngrx/store-devtools](https://ngrx.io/guide/store-devtools) - Instrumentation for @ngrx/store enabling time-travel debugging
- [@angular/router](https://angular.io/guide/router) - Angular Router
- [@angular/material](https://github.com/angular/material2) - Angular Material

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.6.

The project has been updated to Angular version 12.0.1

### Installation

```Markdown

# Clone the repository
git clone https://github.com/santoshbussa/ngx-angular-regions-countries

# Navigate to the app's root directory
cd ngx-angular-regions-countries
# Install the dependencies
npm install

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

# Run the application
ng serve

**Description of how the application work**

open in browser http://localhost:4200/ade



 1)once application opens Drop down that contains the “Region” with options Europe and Asia  will display

2)On selecting any region a second drop down should  will shown  populated with “Countries” based on the API

response from above URLs

3)On selecting the any “Country”

4)it display a simple table that contains the

a. Name

b. Capital

c. Population

d. Currencies

e. Flag
```


### Running unit tests

Run `ng test` to execute the unit tests via Karma.

### Running end-to-end tests

Run `ng e2e` to execute end-to-end tests via Cypress.
