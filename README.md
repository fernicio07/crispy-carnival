# ProductApp

A simple Angular application that displays a list of products and their details using Angular's component-based architecture, services, and routing.

## Project Setup

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.5.

### Installation

1. Create a new Angular project:
```
ng new product-app
cd product-app
```

2. Generate components and services:
```
ng generate component components/product-list
ng generate component components/product-detail
ng generate component components/product-card
ng generate service services/product
```

3. Install dependencies:
```
npm install
```

## Application Structure

- **ProductCardComponent**: Displays individual product details with input/output bindings
- **ProductListComponent**: Shows all products using the ProductService
- **ProductDetailComponent**: Shows detailed information for a selected product
- **ProductService**: Provides product data asynchronously using RxJS Observables

## Features

- Component-based architecture with proper input/output bindings
- Service for data handling with RxJS Observables
- Angular routing with parameter-based navigation
- Responsive design with CSS Grid
- Loading states and error handling

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
