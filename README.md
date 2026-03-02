# my_repo — Angular 15 Starter Application

This repository contains an **Angular 15** single-page application generated with the [Angular CLI](https://github.com/angular/angular-cli) (version 15.0.x). It is configured for deployment to [Vercel](https://vercel.com) with zero extra configuration.

## Project structure

```
my_repo/
├── src/
│   ├── app/
│   │   ├── app.component.css          # Root component styles (empty)
│   │   ├── app.component.html         # Root component template (default Angular welcome page)
│   │   ├── app.component.spec.ts      # Unit tests for the root component
│   │   ├── app.component.ts           # Root component class (title = 'angular-test')
│   │   ├── app.module.ts              # Root NgModule (BrowserModule + AppRoutingModule)
│   │   └── app-routing.module.ts      # Router module (no routes defined yet)
│   ├── assets/                        # Static assets folder
│   ├── favicon.ico                    # App favicon
│   ├── index.html                     # HTML shell (<app-root> entry point)
│   ├── main.ts                        # Application bootstrap
│   └── styles.css                     # Global styles (empty)
├── angular.json                       # Angular CLI workspace configuration
├── package.json                       # NPM dependencies and scripts
├── tsconfig.json                      # Base TypeScript configuration
├── tsconfig.app.json                  # TypeScript config for the app build
├── tsconfig.spec.json                 # TypeScript config for unit tests
└── .editorconfig                      # Editor formatting rules
```

## Key technologies

| Technology | Version |
|---|---|
| Angular | ^15.0.0 |
| TypeScript | ~4.8.2 |
| RxJS | ~7.5.0 |
| Karma + Jasmine | unit testing |
| Angular CLI | ~15.0.0 |

## Getting started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Install dependencies

```bash
npm install
```

### Development server

```bash
npm start          # or: ng serve
```

Navigate to `http://localhost:4200/`. The application reloads automatically when source files change.

## Available scripts

| Command | Description |
|---|---|
| `npm start` | Start the development server |
| `npm run build` | Build the app for production (output: `dist/`) |
| `npm run watch` | Build in watch mode (development configuration) |
| `npm test` | Run unit tests via [Karma](https://karma-runner.github.io) |

## Code scaffolding

Use the Angular CLI to generate new building blocks:

```bash
ng generate component component-name
ng generate directive|pipe|service|class|guard|interface|enum|module
```

## Build

```bash
ng build
```

Build artifacts are stored in the `dist/angular-test/` directory.

## Running unit tests

```bash
ng test
```

Executes the unit tests via [Karma](https://karma-runner.github.io).

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Lucifer-AI-666/my_repo)

The project is pre-configured for Vercel. Push to your connected branch and Vercel will build and deploy automatically.

## Further help

- [Angular CLI documentation](https://angular.io/cli)
- [Angular documentation](https://angular.io/docs)
